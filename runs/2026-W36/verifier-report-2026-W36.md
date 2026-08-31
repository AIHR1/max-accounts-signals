# Verifier report — 2026-W36

**Independent check:** `max-digest-verifier` against `runs/2026-W36/` after merge, harvest, and trade-press sweep.

**VERDICT: PASS WITH NOTES**

## Blocking issues

None.

## Non-blocking notes

- All 45 account rows × six signals are Attempted in the manifest (270/270). Eighteen lane logs are on disk and listed in the master index. Part L is row-specific (queries, URLs, outcomes). Signal 2 uses per-account headings instead of a table; coverage is still 15/15 per batch.
- Trade-press sweep is complete in the manifest audit table (ten outlets plus a Pierre Fabre wire follow-up).
- Local-language queries with August-window tokens are present for French, German, Afrikaans, Arabic, Danish, and Chinese sample rows.
- Part A spot-check (Admiral, Gallagher, TTEC) has working or documented primary links, in-window verification dates, commercial-gate fields, and passing scores.
- Cross-signal hints were reviewed and not uplifted (Sony vacancy vs appointment; Gallagher HRIS hiring vs go-live; TTEC 24 Aug wire one day early; Pierre Fabre commercial CEO).
- Schneider Electric hiring cluster relies in part on search-indexed job bodies where Jibe HTML 404’d (logged as a fetch failure). Several batch files still say the trade-press sweep was pending at write time; the orchestrator finished it in the manifest.

## Counts

- Total rows: 45
- Rows with ≥1 Part A signal: 6
- RF-SILENCE-ROW (after all six signals attempted): 39
- Incomplete cells: 0
- User-approved waivers: none
