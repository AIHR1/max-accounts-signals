# Runs — one folder per master execution

Every **master digest run** uses **exactly one subfolder** under `runs/`, named by **`{run-id}`** (same stem as your digest, e.g. `2026-03`, `2026-04`, or `2026-03-15`).

## What goes in `runs/{run-id}/`

| Artifact | Filename pattern |
| -------- | ---------------- |
| Combined digest (Part A + B) | `master-digest-{run-id}.md` |
| Master log index | `master-digest-log-{run-id}.md` |
| Run manifest | `run-manifest-{run-id}.md` |
| Batch lane logs | `master-digest-log-{run-id}-s{N}-b{MM}.md` |
| Optional refined single-signal digests | e.g. `sop1-digest-{run-id}.md` |

**Do not** place these files in the vault root next to `accounts-in-scope.md` for new runs—keep each run **self-contained** under its folder.

## What stays outside `runs/`

- **`sops/`** — all procedure SOPs (`sop-master-digest`, `sop-1-…` through `sop-6-…`)
- **`accounts-in-scope.md`** — shared account table
- **`templates/`** — blank templates to copy **into** `runs/{run-id}/`

## Workflow

See **`sops/sop-master-digest.md`** Section 7.3 (orchestrator merge order). Each **`max-signal-sop-runner`** batch is expected to **write its own** `master-digest-log-{run-id}-s{N}-b{MM}.md` under this folder (orchestrator verifies Part L is not placeholder text before merge).
