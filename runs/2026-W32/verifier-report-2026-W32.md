# Verifier report — 2026-W32

**Run folder:** `runs/2026-W32/`  
**Review period:** 2026-07-28 through 2026-08-03 inclusive  
**Verifier:** parent automation invocation of `max-digest-verifier`  

## VERDICT: PASS WITH NOTES

## Blocking issues

None. All mandatory verifier gates pass for run `2026-W32` with no user-approved waivers.

## Non-blocking notes

### Matrix and batch coverage

- All 45 account rows from `accounts-in-scope.md` appear in the manifest row x signal grid with every cell marked **Attempted** (270/270 cells).
- The master log index lists 24 lane logs (S1-S6 x B01-B04); on-disk files match.
- Batch row slices sum to 45 per signal (11+11+11+12).
- Spot-checked accounts (ACI Worldwide, Woolworths, METRO AG, Pierre Fabre Laboratories, DHL global forwarding, Oscar Health) each appear in exactly six Part L tables, one per signal.

### Trade sweep

- Audit table is present with six outlets: HR Dive, People Matters Global, HR Executive, HCM Technology Report, UNLEASH, and Reworked.
- The audit table includes search queries, review-window filter, 14 candidate article URLs, and per-URL outcomes.
- Sweep complete: yes.

### Local-language evidence

- French rows spot-checked (Pierre Fabre Laboratories, ENGIE, Orange SA): ISO `fr` plus full query strings in local-language blocks across all six signals.
- German rows spot-checked (METRO AG, Bertelsmann, Inc.): ISO `de` plus full query strings across all six signals.
- Additional locales logged where applicable: `ar`, `af`, `da`, `zh`.

### RF-SILENCE-ROW

- All 45 silence flags are legitimate: the manifest shows six Attempted cells per row, and lane logs contain row-specific Part L entries for each signal.
- No signal was skipped.

### Part A quality

- Not applicable: zero Part A entries.
- No RF-CROSS-SIGNAL-SOP1 or RF-CROSS-SIGNAL-ROUTE flags.

### Placeholder Part L

- No forbidden placeholder phrases from the orchestrator anti-placeholder checklist were found in any batch lane log.
- Shared exclusion boilerplate is repeated, but each row has distinct query strings and outcomes; this does not trigger the anti-placeholder failure rule.

### Quality and execution notes

- Discovery yielded a high rate of "No parseable search results returned" across lane logs.
- A few Signal 4 rows performed real URL fetches: Admiral, Capitec, Schneider Electric, TTEC, Viasat, Orange Business.
- RF-FETCH is documented for Capitec bank, Schneider Electric, and Viasat careers shells.
- The orchestrator executed batches directly because the dedicated signal-runner tool was not available inside that runtime.
- Capitec bank and Momentum Metropolitan lack Afrikaans local-language entries while other South Africa rows include `af`; verifier treated this as interpretive under SOP 7.1a, not a matrix gap.

## Counts

| Metric | Value |
| ------ | ----- |
| Total rows | 45 |
| Rows with >=1 signal (Part A) | 0 |
| RF-SILENCE-ROW count (legitimate) | 45 |
| Incomplete cells | 0 |
| Lane log count | 24 |
| Part A entry count | 0 |
