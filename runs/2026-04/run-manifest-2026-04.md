# Run manifest — master digest (copy per run)

**Review period:** 2026-04-01–2026-04-30 (publication / disclosure date rule per child SOP §6)  
**Run id:** `2026-04`  
**User-approved waivers (quote or link to message):** _none_

## Instructions

- **Location:** this file lives in **`runs/{run-id}/run-manifest-{run-id}.md`** (not the vault root).  
- **Fill this file last** in the orchestrator workflow: after all batch lane logs for the run exist and Part A / Part B are merged. See [[sop-master-digest]] Section 7.3.
- **Attempted** = child SOP §7 minimum discovery executed for that row + signal **and** a **batch lane log** (`master-digest-log-{run}-s{N}-b{MM}.md` or path under `runs/`) contains that row with the required families and query strings for that signal. Do not mark **Attempted** from memory or from unsubmerged subagent chat alone.
- **Waiver** = only if the **user** explicitly approved skipping this cell in chat; note code (e.g. `USER-SCOPE-HIRING-ONLY`).
- Leave **n/a** only for impossible pairs (should be rare—document why).
- Use **—** or leave empty only while the run is **in progress**; before claiming **complete**, every cell must be **Attempted** or **Waiver** (verifier).

## Batch coverage (which logs prove which cells)

Map each **batch id** to the account rows it covers **for that signal**. Update as batch files land.

| Batch id | Signal # | Batch log file (path) | Account rows in batch |
| -------- | -------- | --------------------- | --------------------- |
| S1-B01 | 1 | `runs/2026-04/master-digest-log-2026-04-s1-b01.md` | ACI Worldwide through DOVISTA (first 15 rows) |
| S1-B02 | 1 | `runs/2026-04/master-digest-log-2026-04-s1-b02.md` | Emirates group through Orange SA |
| S1-B03 | 1 | `runs/2026-04/master-digest-log-2026-04-s1-b03.md` | Orange Business through Woolworths |
| S2-B01 | 2 | `runs/2026-04/master-digest-log-2026-04-s2-b01.md` | ACI Worldwide through DOVISTA |
| S2-B02 | 2 | `runs/2026-04/master-digest-log-2026-04-s2-b02.md` | Emirates group through Orange SA |
| S2-B03 | 2 | `runs/2026-04/master-digest-log-2026-04-s2-b03.md` | Orange Business through Woolworths |
| S3-B01 | 3 | `runs/2026-04/master-digest-log-2026-04-s3-b01.md` | ACI Worldwide through DOVISTA |
| S3-B02 | 3 | `runs/2026-04/master-digest-log-2026-04-s3-b02.md` | Emirates group through Orange SA |
| S3-B03 | 3 | `runs/2026-04/master-digest-log-2026-04-s3-b03.md` | Orange Business through Woolworths |
| S4-B01 | 4 | `runs/2026-04/master-digest-log-2026-04-s4-b01.md` | ACI Worldwide through DOVISTA |
| S4-B02 | 4 | `runs/2026-04/master-digest-log-2026-04-s4-b02.md` | Emirates group through Orange SA |
| S4-B03 | 4 | `runs/2026-04/master-digest-log-2026-04-s4-b03.md` | Orange Business through Woolworths |
| S5-B01 | 5 | `runs/2026-04/master-digest-log-2026-04-s5-b01.md` | ACI Worldwide through DOVISTA |
| S5-B02 | 5 | `runs/2026-04/master-digest-log-2026-04-s5-b02.md` | Emirates group through Orange SA |
| S5-B03 | 5 | `runs/2026-04/master-digest-log-2026-04-s5-b03.md` | Orange Business through Woolworths |
| S6-B01 | 6 | `runs/2026-04/master-digest-log-2026-04-s6-b01.md` | ACI Worldwide through DOVISTA |
| S6-B02 | 6 | `runs/2026-04/master-digest-log-2026-04-s6-b02.md` | Emirates group through Orange SA |
| S6-B03 | 6 | `runs/2026-04/master-digest-log-2026-04-s6-b03.md` | Orange Business through Woolworths |

## Row × signal matrix

| Account (exact table row) | [chro-statement] | [leadership-appointment] | [transformation-initiative] | [hiring-trends] | [skills-gaps] | [hr-technology] |
| ------------------------- | ---------------- | -------------------------- | --------------------------- | --------------- | ------------- | --------------- |
| ACI Worldwide | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Admiral Group Plc | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| African Development Bank | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Almarai - المراعي | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| AssuredPartners | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Bertelsmann, Inc. | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Boston Children's Hospital | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Capitec bank | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Cleaver-Brooks | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| DHL Ecommerce | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| DHL Supply Chain | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| DHL Express | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| DHL global forwarding | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| DHL | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| DOVISTA | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Emirates group | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| ENGIE | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Entergy | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| First Quantum Minerals | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Gallagher | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Galaxy Entertainment Group | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Howmet Aerospace | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| James Avery Artisan Jewelry | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Logitech | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Logitech USA | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Mercury Insurance | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| METRO AG | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Momentum Metropolitan | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Orange Group | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Orange SA | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Orange Business | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Oscar Health | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Phoenix Contact | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Pierre Fabre Laboratories | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| RATP Dev | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Schneider Electric | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Sony Music Entertainment | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Stellenbosch University | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Toyota SA | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| TTEC | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Viasat | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Viasat Government | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| VON Canada | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Wood Mackenzie | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |
| Woolworths | Attempted | Attempted | Attempted | Attempted | Attempted | Attempted |

## Trade media sweep (`sop-master-digest` §7.2) — audit table

**Orchestrator-only** (not delegated to signal-only subagents). For **each** outlet visit, list **every** article or listing URL that **might** name an in-scope account. For each candidate row below, state verification per child SOP §8 (especially primary/filing requirement for `[skills-gaps]` and `[hr-technology]`).

| Outlet visited | Entry path or search query used | Review window filter | Candidate article URL | In-scope account row (if any) | Outcome (included in Part A / excluded / paywall) | Routed tag (if applicable) | Notes |
| -------------- | ------------------------------- | -------------------- | --------------------- | ----------------------------- | ------------------------------------------------- | -------------------------- | ----- |
| HR Dive | `site:hrdive.com April 2026 "Orange" OR "Schneider Electric" OR "TTEC" HR learning skills Workday` | Apr 2026 | https://www.hrdive.com/news/what-will-employee-learning-look-like-in-2026/808532/ and related HR Dive results | — | excluded — broad HR/L&D trend coverage, no in-scope account named | — | Outlet probe; no primary account route. |
| UNLEASH | `site:unleash.ai April 2026 "Orange" "Schneider Electric" "TTEC" "DHL" HR AI skills workforce` | Apr 2026 | https://www.unleash.ai/unleash-world/orange-group-chro-we-must-build-ai-with-the-people-not-against-the-people/ | Orange Group | excluded — fetched article is dated 2025-10-13, outside review period | `[chro-statement]` / `[skills-gaps]` if in-period | Useful for query tuning only. |
| UNLEASH | same query | Apr 2026 | https://www.unleash.ai/employee-experience-and-engagement/schneider-electric-chro-talks-sustainability-new-jobs-and-the-future-of-learning/ | Schneider Electric | excluded — fetched article is dated 2024-07-17, outside review period | `[chro-statement]` / `[skills-gaps]` if in-period | Useful for query tuning only. |
| People Matters | `site:peoplemattersglobal.com April 2026 "DHL" OR "Galaxy Entertainment" OR "Capitec" HR talent learning` | Apr 2026 | https://www.peoplemattersglobal.com/article/hr-technology/dhl-express-hr-head-the-secret-to-great-ex-innovation-and-inclusion-44738 | DHL Express | excluded — fetched article is dated 2025-03-12, outside review period | `[chro-statement]` / `[hr-technology]` if in-period | No April People Matters account candidate found. |
| HCM Technology Report | `site:hcmtechnologyreport.com April 2026 "Orange" OR "Schneider" OR "Galaxy Entertainment" HR technology Workday SuccessFactors` | Apr 2026 | https://www.hcmtechnologyreport.com/oracle-hcm-features-focuses-usability/ | — | excluded — HR technology product coverage, no in-scope account named | — | No account route. |
| Human Resource Executive | `site:hrexecutive.com April 2026 "TTEC" OR "Schneider Electric" OR "DHL" HR technology learning workforce` | Apr 2026 | https://hrexecutive.com/hrs-rising-stars-advancing-people-success-at-schneider-electric-with-a-heart-and-mind-approach/ | Schneider Electric | excluded — search result was Schneider-related but not April 2026 and not needed after primary Schneider entries | `[chro-statement]` if in-period | Broad April AI/L&D articles did not name in-scope accounts. |
| Reworked | `site:reworked.co April 2026 "Orange" OR "Schneider Electric" OR "DHL" workplace AI HR skills` | Apr 2026 | https://www.reworked.co/employee-experience/ai-interview-agents-redefine-the-job-application/ | — | excluded — broad HR/AI article, no in-scope account named | — | No account route. |
| People Management (CIPD) | `site:peoplemanagement.co.uk April 2026 "Admiral" OR "Orange" OR "Schneider Electric" HR skills learning` | Apr 2026 | https://www.peoplemanagement.co.uk/article/1923752/experience-superpower-schneider-electrics-michael-fossat-redefining-careers-senior-talent | Schneider Electric | paywall — member-only body; not used for Part A | `[chro-statement]` / `[skills-gaps]` if verifiable | Logged as access limitation. |
| HR Grapevine | `site:hrgrapevine.com April 2026 "Admiral" OR "DHL" OR "TTEC" HR skills learning appointment` | Apr 2026 | https://www.hrgrapevine.com/content/article/2026-04-30-why-cpos-at-serco-beyond-are-opening-doors-with-social-mobility-schemes | — | excluded — April HR article but no in-scope account named | — | No account route. |

**Sweep complete?** yes

## Subagent / batch invocations

| Signal # | Batch id | Rows (names or range) | Batch log file | Returned OK for §7 minimums? | Notes |
| -------- | -------- | ---------------------- | -------------- | ---------------------------- | ----- |
| 1 | S1-B01 | ACI Worldwide–DOVISTA | `master-digest-log-2026-04-s1-b01.md` | yes | Part L row-specific |
| 1 | S1-B02 | Emirates–Orange SA | `master-digest-log-2026-04-s1-b02.md` | yes | |
| 1 | S1-B03 | Orange Business–Woolworths | `master-digest-log-2026-04-s1-b03.md` | yes | |
| 2 | S2-B01 | ACI Worldwide–DOVISTA | `master-digest-log-2026-04-s2-b01.md` | yes | |
| 2 | S2-B02 | Emirates–Orange SA | `master-digest-log-2026-04-s2-b02.md` | yes | No Part A′ hits; Part L complete |
| 2 | S2-B03 | Orange Business–Woolworths | `master-digest-log-2026-04-s2-b03.md` | yes | |
| 3 | S3-B01 | ACI Worldwide–DOVISTA | `master-digest-log-2026-04-s3-b01.md` | yes | |
| 3 | S3-B02 | Emirates–Orange SA | `master-digest-log-2026-04-s3-b02.md` | yes | |
| 3 | S3-B03 | Orange Business–Woolworths | `master-digest-log-2026-04-s3-b03.md` | yes | |
| 4 | S4-B01 | ACI Worldwide–DOVISTA | `master-digest-log-2026-04-s4-b01.md` | yes | |
| 4 | S4-B02 | Emirates–Orange SA | `master-digest-log-2026-04-s4-b02.md` | yes | |
| 4 | S4-B03 | Orange Business–Woolworths | `master-digest-log-2026-04-s4-b03.md` | yes | |
| 5 | S5-B01 | ACI Worldwide–DOVISTA | `master-digest-log-2026-04-s5-b01.md` | yes | |
| 5 | S5-B02 | Emirates–Orange SA | `master-digest-log-2026-04-s5-b02.md` | yes | |
| 5 | S5-B03 | Orange Business–Woolworths | `master-digest-log-2026-04-s5-b03.md` | yes | |
| 6 | S6-B01 | ACI Worldwide–DOVISTA | `master-digest-log-2026-04-s6-b01.md` | yes | |
| 6 | S6-B02 | Emirates–Orange SA | `master-digest-log-2026-04-s6-b02.md` | yes | |
| 6 | S6-B03 | Orange Business–Woolworths | `master-digest-log-2026-04-s6-b03.md` | yes | |

---

When the matrix is full and drafts are merged, run **`/max-digest-verifier`** (or equivalent) before closing the run.

## See also

- [[sop-master-digest]] — Master SOP that fills this template
- [[accounts-in-scope]] — Account rows tracked in this manifest
- [[batch-lane-log-template]] — Per-batch log template used alongside this
