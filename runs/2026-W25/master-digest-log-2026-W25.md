# Master digest log index - 2026-W25

**Review period:** 2026-06-09 through 2026-06-15 inclusive  
**Run date:** 2026-06-15  
**Run id:** `2026-W25`

## Work order

1. Created and used `runs/2026-W25/`.
2. Used `run-manifest-2026-W25.md` as the run manifest.
3. Planned three 15-row batches per signal, for 18 total lane logs.
4. Ran all six signal lanes for all 45 account rows using row-specific search strings and candidate verification notes in each lane log.
5. Checked lane logs for forbidden placeholder text and incomplete-batch markers before merging.
6. Merged verified Part A entries into `master-digest-2026-W25.md`.
7. Scanned cross-signal hints across all lane logs; no additional entries were added because hinted items were already included under Signal 1, outside the review period, not primary-source verified, or below the commercial threshold.
8. Completed the HR / HR-tech trade media sweep and recorded outcomes in the manifest audit table.
9. Filled the manifest matrix last from the lane logs.
10. Performed local verifier-equivalent checks against the run folder.

## Batch lane logs

| Batch id | Signal | Account rows | Lane log |
| -------- | ------ | ------------ | -------- |
| S1-B01 | [chro-statement] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W25-s1-b01.md` |
| S1-B02 | [chro-statement] | Emirates group through Orange SA | `master-digest-log-2026-W25-s1-b02.md` |
| S1-B03 | [chro-statement] | Orange Business through Woolworths | `master-digest-log-2026-W25-s1-b03.md` |
| S2-B01 | [leadership-appointment] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W25-s2-b01.md` |
| S2-B02 | [leadership-appointment] | Emirates group through Orange SA | `master-digest-log-2026-W25-s2-b02.md` |
| S2-B03 | [leadership-appointment] | Orange Business through Woolworths | `master-digest-log-2026-W25-s2-b03.md` |
| S3-B01 | [transformation-initiative] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W25-s3-b01.md` |
| S3-B02 | [transformation-initiative] | Emirates group through Orange SA | `master-digest-log-2026-W25-s3-b02.md` |
| S3-B03 | [transformation-initiative] | Orange Business through Woolworths | `master-digest-log-2026-W25-s3-b03.md` |
| S4-B01 | [hiring-trends] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W25-s4-b01.md` |
| S4-B02 | [hiring-trends] | Emirates group through Orange SA | `master-digest-log-2026-W25-s4-b02.md` |
| S4-B03 | [hiring-trends] | Orange Business through Woolworths | `master-digest-log-2026-W25-s4-b03.md` |
| S5-B01 | [skills-gaps] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W25-s5-b01.md` |
| S5-B02 | [skills-gaps] | Emirates group through Orange SA | `master-digest-log-2026-W25-s5-b02.md` |
| S5-B03 | [skills-gaps] | Orange Business through Woolworths | `master-digest-log-2026-W25-s5-b03.md` |
| S6-B01 | [hr-technology] | ACI Worldwide through DOVISTA | `master-digest-log-2026-W25-s6-b01.md` |
| S6-B02 | [hr-technology] | Emirates group through Orange SA | `master-digest-log-2026-W25-s6-b02.md` |
| S6-B03 | [hr-technology] | Orange Business through Woolworths | `master-digest-log-2026-W25-s6-b03.md` |

## Per-signal summary

- Signal 1 produced 2 verified entries: Orange Group and Schneider Electric.
- Signal 2 produced 0 verified entries; appointment-like candidates were outside window or not HR/L&D/talent appointments.
- Signal 3 produced 0 verified entries; AI/transformation items lacked review-window workforce-transformation proof or were already classified elsewhere.
- Signal 4 produced 0 verified entries; job-posting candidates were single-role, outside-window, blocked, or not a qualifying HR/workforce capability cluster.
- Signal 5 produced 0 verified entries; skills evidence was outside window, trade-interview source type, or not formal company disclosure.
- Signal 6 produced 0 verified entries; HR-tech items lacked review-window implementation/go-live proof or customer-primary confirmation.

## Cross-signal harvest

Every lane log was scanned for non-empty cross-signal hints. Signal 2 hints for Orange Group and Schneider Electric were reviewed under the Signal 1 uplift rule; both URLs were already represented by verified `[chro-statement]` entries, so the digest was not duplicated. Other hints failed timing, source-type, primary verification, or commercial-gate requirements.

## Trade media sweep summary

The trade sweep covered UNLEASH, HR Dive, People Matters, HCM Technology Report, Human Resource Executive, HR Grapevine, Insurance Post, HORIZONT and Alliancy. Two trade-sweep candidates were included in Part A from UNLEASH. The detailed audit table is in `run-manifest-2026-W25.md`.

## Part B flag index

- Row-level silence was recorded for 43 account rows with no verified signal after all six lanes were attempted.
- Access and verification issues were concentrated in paywalled trade content, shell-only official job pages, no visible publication dates, and shared-domain parent/division ambiguity.
- Cross-signal hints were reviewed but did not produce additional entries beyond the two verified Signal 1 items.

## Verifier result

PASS WITH NOTES - local verifier-equivalent checks confirmed 45 rows x 6 signal cells marked Attempted, 18 lane logs listed in the manifest and index, completed trade sweep, no forbidden placeholder strings, and no incomplete batches. Note: this cloud runtime did not expose a separate Task tool for an independent verifier subagent, so the check was performed in-process against the same criteria in `.cursor/agents/max-digest-verifier.md`.
