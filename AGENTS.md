# Cursor Cloud specific instructions

This repository is an Obsidian-friendly **markdown vault** for **max-accounts-signals**: SOP-driven research digests for a fixed account list. There is no application build step; artifacts are files under `runs/{run-id}/`.

When you run **inside Cursor Cloud** (including **Cursor Automations**), treat this file as binding in addition to `sops/`, `.cursor/rules/max-accounts-signals-execution.mdc`, and the agent prompts under `.cursor/agents/`.

## Weekly automation (master digest)

Follow the **mandatory checklist** and tone rules in `.cursor/agents/max-digest-orchestrator.md`. Procedure truth is `sops/sop-master-digest.md` (merge order, cross-signal harvest, trade sweep, manifest last). Account rows live in `accounts-in-scope.md`.

**Run id:** Choose a single `run-id` for this execution (for example `2026-05` for a calendar month, or `2026-W18` for an ISO week). Use the **same** stem in every filename under `runs/{run-id}/`, per `runs/README.md`.

**Parallel batches:** If your runtime cannot spawn separate subagents the way the desktop orchestrator does with the Task tool, still complete **every** row for **every** signal by running **sequential** batch slices (roughly 8–15 account rows per batch). Do not skip rows to save time.

**Compliance:** Do not mark the manifest **Attempted** until each batch lane log passes the anti-placeholder rules in the orchestrator file. Before claiming the run is complete, apply `.cursor/agents/max-digest-verifier.md` (or perform the same checks yourself) against the whole `runs/{run-id}/` folder.

## Git / pull request

When **Open pull request** is enabled on the automation, create a **branch** (for example `automation/digest-{run-id}`), commit **only** the new or updated files for this run under `runs/{run-id}/` plus any intentional template or doc updates, and open a PR with a clear title and description. The PR description should name the review period, `run-id`, and the verifier outcome in plain language.

If the automation is configured to push without a PR, still make a **single coherent commit** with the same scope discipline.

## Slack — notify Max (Slack MCP, not Cursor’s Send to Slack)

Max is **not** a Cursor user, so the digest must reach him in Slack via your workspace’s **Slack MCP** (`slack_send_message`, `slack_search_channels`, etc.). **Do not** use Cursor Automations’ built-in **Send to Slack** action for this notification.

**Automation wiring:** On the scheduled automation, enable **MCP** and attach the **Slack** MCP server your team uses for cloud runs ([MCP on cloud agents](https://cursor.com/docs/cloud-agent/capabilities)). If the automation is **team-owned**, complete Slack / MCP OAuth under the **automations service account** so posting to the target channel is allowed—personal OAuth on someone else’s account will break when the automation runs unattended ([permissions / billing](https://cursor.com/docs/cloud-agent/automations)). Prefer an **HTTP** Slack MCP configuration when your setup allows it; otherwise use the supported team configuration from [Cloud Agents / MCP settings](https://cursor.com/agents).

**Channel target:** Post to the **Slack channel** Max uses for digests. The channel id (typically `C…`; in Slack: channel details → copy link or *Copy channel ID*) is set in **`.cursor/environment.json`** under **`env.MAX_SLACK_CHANNEL_ID`**. Cloud agents load that map into the VM environment ([Cloud agent setup](https://cursor.com/docs/cloud-agent/setup)). Replace the placeholder value with the real id before production runs. **Security:** the id is committed with the repo—acceptable for a private vault; avoid publishing this file to a public repository if you want the channel reference non-obvious. Before sending, read it with a shell check such as `printenv MAX_SLACK_CHANNEL_ID` and pass it as **`channel_id`** to **`slack_send_message`**. If it is still the placeholder or unset, use **`slack_search_channels`** to find the right channel and **confirm** the destination before posting.

**Message content** — write for a busy reader: short paragraphs, plain English, no internal gate jargon without explanation. Include:

1. **Review period** and **`run-id`**.
2. **Top 5–10** Part A headlines (account + what changed + why it matters), each with its primary link from the digest.
3. **Red flags / Part B** themes in one short paragraph if any.
4. **Verifier** outcome (pass / pass with notes / fail) and what to do next if not a clean pass.
5. **Links** to `runs/{run-id}/master-digest-{run-id}.md`, `runs/{run-id}/run-manifest-{run-id}.md`, and the **GitHub PR** URL if one exists.

The `slack_send_message` tool applies a **length limit** (on the order of thousands of characters). If the summary is too long, send **multiple** sequential messages to the same channel or trim to highlights and rely on the GitHub links for detail. You may write a scratch file such as `runs/{run-id}/slack-summary-{run-id}.md` for your own editing; **do not** put tokens or webhook URLs in committed files.

**Fallback:** If Slack MCP is unavailable and only a webhook exists, `SLACK_WEBHOOK_URL` plus `node scripts/post-digest-slack-webhook.mjs` stays available for a fixed channel—see `scripts/README.md`.

## Environment

This repo has **no** npm dependencies for the digest itself. **`.cursor/environment.json`** sets a no-op **`install`** command and **`env.MAX_SLACK_CHANNEL_ID`** for Slack MCP posts. If you add tooling later, extend that file’s `install` command to match.