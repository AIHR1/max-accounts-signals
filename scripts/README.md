# Optional scripts

## `post-digest-slack-webhook.mjs`

**Primary path for weekly notifications to Max:** configure **Slack MCP** on the automation and follow `AGENTS.md` (post to his channel via `slack_send_message` and **`MAX_SLACK_CHANNEL_ID`** from **`.cursor/environment.json`** → `env`). **Do not** rely on Cursor’s built-in **Send to Slack** for that destination.

Use this webhook helper only when:

- You prefer Slack **Incoming Webhooks** stored as a Cloud Agent secret (`SLACK_WEBHOOK_URL`), or
- You are testing locally and already have a webhook URL.

**Setup:** Create an Incoming Webhook in Slack for the target channel, then add `SLACK_WEBHOOK_URL` under [Cloud Agents secrets](https://cursor.com/dashboard/cloud-agents) (or export it locally).

**Run from repo root** (`max-accounts-signals/`):

```bash
export SLACK_WEBHOOK_URL="https://hooks.slack.com/services/..."
node scripts/post-digest-slack-webhook.mjs --file runs/2026-W18/slack-summary-2026-W18.md
```

Requires **Node.js 18+** (global `fetch`).