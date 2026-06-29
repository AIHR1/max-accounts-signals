# Master digest log index - 2026-W27

**Review period:** June 23, 2026 through June 29, 2026 inclusive  
**Run date:** June 29, 2026  
**Run id:** `2026-W27`

## Work order

1. Created and used `runs/2026-W27/`.
2. Used `run-manifest-2026-W27.md` as the run manifest.
3. Planned three 15-row batches per signal, for 18 total lane logs.
4. Ran all six signal lanes for all 45 account rows using sequential equivalent execution because subagent spawning was not available in this environment.
5. Checked lane logs for placeholder text and checkpoints before merging.
6. Merged verified Part A entries into `master-digest-2026-W27.md`.
7. Scanned cross-signal hints across all lane logs; no additional entries were added because candidates were already included under `[hiring-trends]`, outside the review window, or did not pass the target child SOP.
8. Completed the HR / HR-tech trade media sweep and recorded outcomes in the manifest.
9. Filled the manifest matrix last from the lane logs.
10. Performed max-digest-verifier-equivalent checks against the run bundle.

## Batch lane logs

| Batch id | Signal | Account rows | Lane log |
| -------- | ------ | ------------ | -------- |
| S1-B01 | [chro-statement] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W27-s1-b01.md` |
| S1-B02 | [chro-statement] | Emirates group through Orange SA | `master-digest-log-2026-W27-s1-b02.md` |
| S1-B03 | [chro-statement] | Orange Business through Woolworths | `master-digest-log-2026-W27-s1-b03.md` |
| S2-B01 | [leadership-appointment] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W27-s2-b01.md` |
| S2-B02 | [leadership-appointment] | Emirates group through Orange SA | `master-digest-log-2026-W27-s2-b02.md` |
| S2-B03 | [leadership-appointment] | Orange Business through Woolworths | `master-digest-log-2026-W27-s2-b03.md` |
| S3-B01 | [transformation-initiative] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W27-s3-b01.md` |
| S3-B02 | [transformation-initiative] | Emirates group through Orange SA | `master-digest-log-2026-W27-s3-b02.md` |
| S3-B03 | [transformation-initiative] | Orange Business through Woolworths | `master-digest-log-2026-W27-s3-b03.md` |
| S4-B01 | [hiring-trends] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W27-s4-b01.md` |
| S4-B02 | [hiring-trends] | Emirates group through Orange SA | `master-digest-log-2026-W27-s4-b02.md` |
| S4-B03 | [hiring-trends] | Orange Business through Woolworths | `master-digest-log-2026-W27-s4-b03.md` |
| S5-B01 | [skills-gaps] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W27-s5-b01.md` |
| S5-B02 | [skills-gaps] | Emirates group through Orange SA | `master-digest-log-2026-W27-s5-b02.md` |
| S5-B03 | [skills-gaps] | Orange Business through Woolworths | `master-digest-log-2026-W27-s5-b03.md` |
| S6-B01 | [hr-technology] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W27-s6-b01.md` |
| S6-B02 | [hr-technology] | Emirates group through Orange SA | `master-digest-log-2026-W27-s6-b02.md` |
| S6-B03 | [hr-technology] | Orange Business through Woolworths | `master-digest-log-2026-W27-s6-b03.md` |

## Per-signal summary

- Signal 1 produced 1 verified entries: Schneider Electric.
- Signal 2 produced 0 verified entries: none.
- Signal 3 produced 1 verified entries: Schneider Electric.
- Signal 4 produced 5 verified entries: Capitec bank, Gallagher, Galaxy Entertainment Group, Schneider Electric, Viasat.
- Signal 5 produced 0 verified entries: none.
- Signal 6 produced 0 verified entries: none.

## Cross-signal harvest

All lane logs were scanned for non-empty cross-signal hints. No new Part A entries were added from cross-signal harvest. The Galaxy Entertainment Group and Viasat S6 hints were already represented by S4 hiring-trend entries and did not meet Signal 6 go-live requirements. Other strong cross-signal-looking sources for ENGIE, Orange, DHL and Capitec were outside the June 23-29 review period.

## Trade media sweep summary

The trade sweep covered HR Dive, UNLEASH, People Matters, Human Resource Executive, HCM Technology Report, Reworked, People Management (CIPD), HR Grapevine and an Economic Times / ETHRWorld targeted route. One Schneider Electric CHRO source was included from the targeted route; no additional Part A entries were added from the general outlet sweep. The detailed audit table is in `run-manifest-2026-W27.md`.

## Part B flag index

- RF-SILENCE-ROW: 40 rows with no verified Part A entry after all six lanes were attempted.
- RF-PAYWALL: 1 trade sweep item (People Management / Schneider Electric) could not be verified beyond the member-only page.
- RF-CLASSIFICATION: Galaxy Entertainment Group and Viasat HR technology-adjacent evidence was kept under `[hiring-trends]` because it proved active capability hiring, not an in-window technology go-live.
- Cross-signal hints: S6 lane hints for Galaxy Entertainment Group and Viasat were reviewed; no new uplift was added because S4 already represented the same facts and S6 did not pass.

## Verifier result

PASS WITH NOTES — self-check confirmed full row × signal matrix coverage, 18 lane logs on disk, no placeholder Part L filler, completed trade sweep, and required Part A commercial-gate fields. Notes: several live careers pages exposed limited bodies through automated fetch/search snippets, so the next run should use browser verification for richer ATS capture.
