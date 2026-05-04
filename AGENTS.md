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

Max is **not** a Cursor user, so the digest must reach him as a normal Slack DM from your workspace’s **Slack MCP** integration (same tool family as in the Cursor desktop MCP catalog: `slack_send_message`, `slack_search_users`, etc.). **Do not** use Cursor Automations’ built-in **Send to Slack** action for Max’s notification.

**Automation wiring:** On the scheduled automation, enable **MCP** and attach the **Slack** MCP server your team uses for cloud runs ([MCP on cloud agents](https://cursor.com/docs/cloud-agent/capabilities)). If the automation is **team-owned**, complete Slack / MCP OAuth under the **automations service account** so DMs are allowed—personal OAuth on someone else’s account will break when the automation runs unattended ([permissions / billing](https://cursor.com/docs/cloud-agent/automations)). Prefer an **HTTP** Slack MCP configuration when your setup allows it; otherwise use the supported team configuration from [Cloud Agents / MCP settings](https://cursor.com/agents).

**DM target:** In Slack, a DM uses the member’s **`user` id** (looks like `U…`) as `channel_id` for `slack_send_message`. Add a Cloud Agent secret **`MAX_SLACK_MEMBER_ID`** set to Max’s Slack member id (from Slack profile → *Copy member ID*). Before sending, obtain that value with a read-only shell check (for example `printenv MAX_SLACK_MEMBER_ID`) so it is never pasted into committed files. If the secret is missing, you may use **`slack_search_users`** and **confirm** you have the right person before DMing.

**Message content** — write for a busy reader: short paragraphs, plain English, no internal gate jargon without explanation. Include:

1. **Review period** and **`run-id`**.
2. **Top 5–10** Part A headlines (account + what changed + why it matters), each with its primary link from the digest.
3. **Red flags / Part B** themes in one short paragraph if any.
4. **Verifier** outcome (pass / pass with notes / fail) and what to do next if not a clean pass.
5. **Links** to `runs/{run-id}/master-digest-{run-id}.md`, `runs/{run-id}/run-manifest-{run-id}.md`, and the **GitHub PR** URL if one exists.

The `slack_send_message` tool applies a **length limit** (on the order of thousands of characters). If the summary is too long, send **multiple** sequential DMs or trim to highlights and rely on the GitHub links for detail. You may write a scratch file such as `runs/{run-id}/slack-summary-{run-id}.md` for your own editing, but **do not commit secrets** into it.

**Fallback:** If Slack MCP is unavailable and only a webhook exists, `SLACK_WEBHOOK_URL` plus `node scripts/post-digest-slack-webhook.mjs` remains an optional last resort (usually posts to one fixed channel, not a DM)—see `scripts/README.md`.

## Environment

This repo has **no** npm dependencies for the digest itself. `.cursor/environment.json` runs a no-op install so cloud machines start quickly. If you add tooling later, update that file’s `install` command to match.

**Node.js:** Not pre-installed on Cloud Agent VMs. Only needed for `scripts/post-digest-slack-webhook.mjs` (optional Slack webhook fallback). If you need it, install Node 18+ at the start of your session (`curl -fsSL https://deb.nodesource.com/setup_20.x | bash - && apt-get install -y nodejs`). The primary Slack path uses the Slack MCP server and does not require Node.

**Lint / test / build:** There are no linter, test suite, or build commands for this vault. Correctness is validated per-run by the `max-digest-verifier` agent (`.cursor/agents/max-digest-verifier.md`), which checks the `runs/{run-id}/` folder for completeness against the run manifest.
