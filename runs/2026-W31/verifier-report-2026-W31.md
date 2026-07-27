# Verifier report - 2026-W31

**Review period:** 2026-07-21 through 2026-07-27 inclusive  
**Run id:** `2026-W31`  
**Verifier:** independent parent-level `max-digest-verifier`

## VERDICT

PASS WITH NOTES

## Blocking issues

None.

## Non-blocking notes

- Matrix: all 45 account rows x 6 signals are marked Attempted in `run-manifest-2026-W31.md` (270/270 cells). No blanks and no waiver codes.
- Batch evidence: all 30 lane logs exist and are listed by the master index. Spot checks found row-specific query strings and outcomes.
- Trade sweep: audit table is complete, with nine candidate URLs and documented included/excluded/paywall outcomes.
- Local language: French and German rows show ISO language labels and full local-language query strings in spot-checked lane logs.
- Part A quality: sampled Admiral Group Plc, Capitec bank, and TTEC entries. Each has a primary link, `[hiring-trends]` tag, required commercial fields, and a passing score.
- Cross-signal: no cross-signal entries were claimed; all Part L cross-signal hint cells were empty.
- Placeholder check: no forbidden placeholder phrases or off-file evidence references found. Repeated exclusion phrasing is acceptable because queries and URLs are row-specific.
- Documented quality flags: Capitec skills PDF timeout and one Schneider careers URL 404 are recorded in Part B.

## Counts

| Metric | Value |
| ------ | ----- |
| Total rows | 45 |
| Rows with >=1 signal (Part A) | 5 |
| RF-SILENCE-ROW | 40 |
| Incomplete cells | 0 |
