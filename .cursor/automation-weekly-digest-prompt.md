# Paste into Cursor Automations → prompt (weekly max-accounts-signals digest)

Use this as the **body** of a **scheduled** automation pointed at the GitHub repo and default branch that contains this folder.

**Required tools on the automation:** **Open pull request** (if you want reviewable output on GitHub), **MCP → Slack** (mandatory: use `slack_send_message` to post to Max’s channel per `AGENTS.md` — do **not** use Cursor’s built-in **Send to Slack** for this), plus any **web / browser / computer use** tools your team enables for research. Only attach MCP servers you trust with this data.

---

You are running the **weekly master digest** for **max-accounts-signals**.

1. Read **`AGENTS.md`** at the repository root (this project) and follow it.
2. Execute the full pipeline described in **`.cursor/agents/max-digest-orchestrator.md`**, using **`sops/sop-master-digest.md`** for merge order and **`accounts-in-scope.md`** for all account rows.
3. Pick a **`run-id`** for this week’s execution (for example `2026-W18` or `2026-05`) and write **all** artifacts under **`runs/{run-id}/`** only.
4. Run the **verifier** checks from **`.cursor/agents/max-digest-verifier.md`** before you stop. If anything blocks a pass, say so clearly for the human.
5. Commit the new `runs/{run-id}/` files on a dedicated branch and **open a pull request** (if that tool is enabled).
6. Notify **Max** by posting to his Slack conversation using **`slack_send_message`**: set **`channel_id`** to **`D01DFNA0GBH`** (documented in **`sops/sop-master-digest.md` section 7.4**; same value as **`MAX_SLACK_CHANNEL_ID`** in **`.cursor/environment.json`** if your runtime loads it). Include: review period, `run-id`, top stories with links, Part B themes if material, verifier outcome, links to the digest file and manifest on GitHub, and the PR URL. Split into multiple messages if you hit length limits. Use normal language, not internal codes only.

If you cannot finish, leave an explicit checkpoint: which batches or rows are unfinished and what must be rerun.

---

**Scheduling:** In the automation UI, attach this repo and branch, set your weekly cron, and confirm [Cloud agent setup](https://cursor.com/docs/cloud-agent/setup) (including team Slack MCP OAuth if the automation is team-owned). The Max digest **`channel_id`** is **`D01DFNA0GBH`** per **`sops/sop-master-digest.md` section 7.4**; **`.cursor/environment.json`** should keep **`MAX_SLACK_CHANNEL_ID`** in sync for env-based tools. See [Automations](https://cursor.com/docs/cloud-agent/automations).
