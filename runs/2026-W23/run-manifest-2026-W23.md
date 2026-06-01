# Run manifest — master digest (copy per run)

**Review period:** 2026-05-26–2026-06-01 inclusive (publication / disclosure date rule per child SOP §6)  
**Run id:** `2026-W23`  
**User-approved waivers (quote or link to message):** _none_

## Instructions

- **Location:** this file lives in **`runs/{run-id}/run-manifest-{run-id}.md`** (not the vault root).  
- **Fill this file last** in the orchestrator workflow: after all batch lane logs for the run exist and Part A / Part B are merged. See [[sop-master-digest]] Section 7.3.
- **Attempted** = child SOP §7 minimum discovery executed for that row + signal **and** a **batch lane log** (`master-digest-log-{run}-s{N}-b{MM}.md` or path under `runs/`) contains that row with the required families and query strings for that signal. Do not mark **Attempted** from memory or from unsubmerged subagent chat alone.
- **Waiver** = only if the **user** explicitly approved skipping this cell in chat; note code (e.g. `USER-SCOPE-HIRING-ONLY`).
- Leave **n/a** only for impossible pairs (should be rare—document why).
- Use **—** or leave empty only while the run is **in progress**; before claiming **complete**, every cell must be **Attempted** or **Waiver** (verifier).

## Batch coverage (which logs prove which cells)

| Batch id | Signal # | Batch log file (path) | Account rows in batch |
| -------- | -------- | --------------------- | --------------------- |
| S1-B01 | 1 | `runs/2026-W23/master-digest-log-2026-W23-s1-b01.md` | ACI Worldwide, Admiral Group Plc, African Development Bank, Almarai - المراعي, AssuredPartners, Bertelsmann, Inc., Boston Children's Hospital, Capitec bank, Cleaver-Brooks, DHL Ecommerce, DHL Supply Chain, DHL Express, DHL global forwarding, DHL, DOVISTA |
| S1-B02 | 1 | `runs/2026-W23/master-digest-log-2026-W23-s1-b02.md` | Emirates group, ENGIE, Entergy, First Quantum Minerals, Gallagher, Galaxy Entertainment Group, Howmet Aerospace, James Avery Artisan Jewelry, Logitech, Logitech USA, Mercury Insurance, METRO AG, Momentum Metropolitan, Orange Group, Orange SA |
| S1-B03 | 1 | `runs/2026-W23/master-digest-log-2026-W23-s1-b03.md` | Orange Business, Oscar Health, Phoenix Contact, Pierre Fabre Laboratories, RATP Dev, Schneider Electric, Sony Music Entertainment, Stellenbosch University, Toyota SA, TTEC, Viasat, Viasat Government, VON Canada, Wood Mackenzie, Woolworths |
| S2-B01 | 2 | `runs/2026-W23/master-digest-log-2026-W23-s2-b01.md` | ACI Worldwide, Admiral Group Plc, African Development Bank, Almarai - المراعي, AssuredPartners, Bertelsmann, Inc., Boston Children's Hospital, Capitec bank, Cleaver-Brooks, DHL Ecommerce, DHL Supply Chain, DHL Express, DHL global forwarding, DHL, DOVISTA |
| S2-B02 | 2 | `runs/2026-W23/master-digest-log-2026-W23-s2-b02.md` | Emirates group, ENGIE, Entergy, First Quantum Minerals, Gallagher, Galaxy Entertainment Group, Howmet Aerospace, James Avery Artisan Jewelry, Logitech, Logitech USA, Mercury Insurance, METRO AG, Momentum Metropolitan, Orange Group, Orange SA |
| S2-B03 | 2 | `runs/2026-W23/master-digest-log-2026-W23-s2-b03.md` | Orange Business, Oscar Health, Phoenix Contact, Pierre Fabre Laboratories, RATP Dev, Schneider Electric, Sony Music Entertainment, Stellenbosch University, Toyota SA, TTEC, Viasat, Viasat Government, VON Canada, Wood Mackenzie, Woolworths |
| S3-B01 | 3 | `runs/2026-W23/master-digest-log-2026-W23-s3-b01.md` | ACI Worldwide, Admiral Group Plc, African Development Bank, Almarai - المراعي, AssuredPartners, Bertelsmann, Inc., Boston Children's Hospital, Capitec bank, Cleaver-Brooks, DHL Ecommerce, DHL Supply Chain, DHL Express, DHL global forwarding, DHL, DOVISTA |
| S3-B02 | 3 | `runs/2026-W23/master-digest-log-2026-W23-s3-b02.md` | Emirates group, ENGIE, Entergy, First Quantum Minerals, Gallagher, Galaxy Entertainment Group, Howmet Aerospace, James Avery Artisan Jewelry, Logitech, Logitech USA, Mercury Insurance, METRO AG, Momentum Metropolitan, Orange Group, Orange SA |
| S3-B03 | 3 | `runs/2026-W23/master-digest-log-2026-W23-s3-b03.md` | Orange Business, Oscar Health, Phoenix Contact, Pierre Fabre Laboratories, RATP Dev, Schneider Electric, Sony Music Entertainment, Stellenbosch University, Toyota SA, TTEC, Viasat, Viasat Government, VON Canada, Wood Mackenzie, Woolworths |
| S4-B01 | 4 | `runs/2026-W23/master-digest-log-2026-W23-s4-b01.md` | ACI Worldwide, Admiral Group Plc, African Development Bank, Almarai - المراعي, AssuredPartners, Bertelsmann, Inc., Boston Children's Hospital, Capitec bank, Cleaver-Brooks, DHL Ecommerce, DHL Supply Chain, DHL Express, DHL global forwarding, DHL, DOVISTA |
| S4-B02 | 4 | `runs/2026-W23/master-digest-log-2026-W23-s4-b02.md` | Emirates group, ENGIE, Entergy, First Quantum Minerals, Gallagher, Galaxy Entertainment Group, Howmet Aerospace, James Avery Artisan Jewelry, Logitech, Logitech USA, Mercury Insurance, METRO AG, Momentum Metropolitan, Orange Group, Orange SA |
| S4-B03 | 4 | `runs/2026-W23/master-digest-log-2026-W23-s4-b03.md` | Orange Business, Oscar Health, Phoenix Contact, Pierre Fabre Laboratories, RATP Dev, Schneider Electric, Sony Music Entertainment, Stellenbosch University, Toyota SA, TTEC, Viasat, Viasat Government, VON Canada, Wood Mackenzie, Woolworths |
| S5-B01 | 5 | `runs/2026-W23/master-digest-log-2026-W23-s5-b01.md` | ACI Worldwide, Admiral Group Plc, African Development Bank, Almarai - المراعي, AssuredPartners, Bertelsmann, Inc., Boston Children's Hospital, Capitec bank, Cleaver-Brooks, DHL Ecommerce, DHL Supply Chain, DHL Express, DHL global forwarding, DHL, DOVISTA |
| S5-B02 | 5 | `runs/2026-W23/master-digest-log-2026-W23-s5-b02.md` | Emirates group, ENGIE, Entergy, First Quantum Minerals, Gallagher, Galaxy Entertainment Group, Howmet Aerospace, James Avery Artisan Jewelry, Logitech, Logitech USA, Mercury Insurance, METRO AG, Momentum Metropolitan, Orange Group, Orange SA |
| S5-B03 | 5 | `runs/2026-W23/master-digest-log-2026-W23-s5-b03.md` | Orange Business, Oscar Health, Phoenix Contact, Pierre Fabre Laboratories, RATP Dev, Schneider Electric, Sony Music Entertainment, Stellenbosch University, Toyota SA, TTEC, Viasat, Viasat Government, VON Canada, Wood Mackenzie, Woolworths |
| S6-B01 | 6 | `runs/2026-W23/master-digest-log-2026-W23-s6-b01.md` | ACI Worldwide, Admiral Group Plc, African Development Bank, Almarai - المراعي, AssuredPartners, Bertelsmann, Inc., Boston Children's Hospital, Capitec bank, Cleaver-Brooks, DHL Ecommerce, DHL Supply Chain, DHL Express, DHL global forwarding, DHL, DOVISTA |
| S6-B02 | 6 | `runs/2026-W23/master-digest-log-2026-W23-s6-b02.md` | Emirates group, ENGIE, Entergy, First Quantum Minerals, Gallagher, Galaxy Entertainment Group, Howmet Aerospace, James Avery Artisan Jewelry, Logitech, Logitech USA, Mercury Insurance, METRO AG, Momentum Metropolitan, Orange Group, Orange SA |
| S6-B03 | 6 | `runs/2026-W23/master-digest-log-2026-W23-s6-b03.md` | Orange Business, Oscar Health, Phoenix Contact, Pierre Fabre Laboratories, RATP Dev, Schneider Electric, Sony Music Entertainment, Stellenbosch University, Toyota SA, TTEC, Viasat, Viasat Government, VON Canada, Wood Mackenzie, Woolworths |

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
| HR Dive | `site:hrdive.com May 26 2026 June 1 2026 "Orange" OR "Schneider Electric" OR "TTEC" HR learning skills Workday` | 2026-05-26--2026-06-01 | no in-scope candidate URL surfaced | — | excluded — no account-specific candidate in active window | — | Broad HR/L&D trend coverage only. |
| UNLEASH | `site:unleash.ai May 2026 "Orange" "Schneider Electric" "TTEC" "DHL" HR AI skills workforce` | 2026-05-26--2026-06-01 | https://www.unleash.ai/unleash-world/interview/orange-group-chro-we-must-build-ai-with-the-people-not-against-the-people | Orange Group | excluded — relevant HR-leader item surfaced, but search snippet indicates UNLEASH World 2025 context / not first-published in active weekly window | `[chro-statement]` / `[skills-gaps]` if in-window | Useful watchlist item, not included. |
| People Matters | `site:peoplemattersglobal.com May 2026 DHL Orange TTEC HR talent learning` | 2026-05-26--2026-06-01 | no in-scope candidate URL surfaced | — | excluded — no account-specific candidate in active window | — | No route. |
| Human Resource Executive | `site:hrexecutive.com May 2026 Schneider Electric DHL HR technology learning workforce` | 2026-05-26--2026-06-01 | no in-scope candidate URL surfaced | — | excluded — no account-specific candidate in active window | — | No route. |
| HR Grapevine | `site:hrgrapevine.com May 2026 Admiral DHL TTEC appointment skills learning` | 2026-05-26--2026-06-01 | no in-scope candidate URL surfaced | — | excluded — no account-specific candidate in active window | — | No route. |
| HCM Technology Report | `site:hcmtechnologyreport.com May 2026 Orange Schneider Galaxy HR technology Workday SuccessFactors` | 2026-05-26--2026-06-01 | no in-scope candidate URL surfaced | — | excluded — product/vendor coverage did not name an in-scope account as customer-primary implementation | — | No route. |
| Techrseries / HRTech | `site:techrseries.com May 2026 TTEC Titan workforce AI hiring coaching` | 2026-05-26--2026-06-01 | https://techrseries.com/hrtechnology/ttec-launches-ttec-titan-an-ai-powered-security-platform-for-remote-customer-experience-operations/ | TTEC | included in Part A via TTEC primary release, not trade article | `[hr-technology]` | Trade article corroborated the primary TTEC source. |
| UC Today | `site:uctoday.com May 2026 Workday Google HR workflows agents account list` | 2026-05-26--2026-06-01 | https://www.uctoday.com/talent-hcm-platforms/workday-google-cloud-ai-agents-hr-workflows/ | — | excluded — HR technology market news, no in-scope account customer implementation | — | Watchlist for future Workday customer references. |
| Benefits Canada | `site:benefitscanada.com May 2026 Gallagher HR benefits appointment` | 2026-05-26--2026-06-01 | https://www.benefitscanada.com/notice/appointment-notice/gallagher-appointing-daniel-sullivan-senior-vice-president-of-benefits-hr/ | Gallagher | excluded — client-facing benefits/HR consulting appointment, not an internal learning/talent/HR transformation leadership appointment for the account row | `[leadership-appointment]?` | Classification reviewed and excluded. |
| Mining Weekly / Engineering News | `site:miningweekly.com "Toyota" "training facility" "29th May 2026" hydrogen skills` | 2026-05-26--2026-06-01 | https://www.miningweekly.com/article/toyota-government-hand-over-locally-developed-hydrogen-refuelling-station-2026-05-29 | Toyota SA | included in Part A after verification against government/DSTI primary source | `[skills-gaps]` | Routed to Signal 5 with DSTI / gov.za primary URLs. |
| SatNews | `site:satnews.com Viasat Atos digital workplace May 28 2026 workforce` | 2026-05-26--2026-06-01 | https://satnews.com/2026/05/28/viasat-selects-atos-to-modernize-its-global-digital-workplace-operations/ | Viasat | excluded — SatNews republication was in-window but Atos primary release was May 19, outside active period | `[transformation-initiative]` if first-published in-window | Logged date-rule exclusion. |
| Consultor / CFE-CGC Orange | `site:consultor.fr OR site:cfecgc-orange.org Orange Business Oliver Wyman compétences 27 28 mai 2026` | 2026-05-26--2026-06-01 | https://www.consultor.fr/articles/oliver-wyman-evalue-les-competences-des-salaries-dorange-business-france; https://www.cfecgc-orange.org/2026052816346/revue-de-presse/oliver-wyman-au-coeur-des-sujets-rh-d-orange-business-france-consultor-fr.html | Orange Business | excluded — no company-primary Orange Business disclosure for skills assessment/training pathway item | `[skills-gaps]` / `[transformation-initiative]` if primary source appears | Strong lead for next run. |
| Barchart / GlobeNewswire mirror | `TTEC Titan May 28 2026 GlobeNewswire remote workforce SmartHire Perform` | 2026-05-26--2026-06-01 | https://www.barchart.com/story/news/2187883/ttec-launches-ttec-titan-an-ai-powered-security-platform-for-remote-customer-experience-operations | TTEC | included in Part A via TTEC primary release | `[hr-technology]` | Wire mirror used only for corroboration. |

**Sweep complete?** yes

## Subagent / batch invocations

| Signal # | Batch id | Rows (names or range) | Batch log file | Returned OK for §7 minimums? | Notes |
| -------- | -------- | ---------------------- | -------------- | ---------------------------- | ----- |
| 1 | S1-B01 | ACI Worldwide through DOVISTA | `master-digest-log-2026-W23-s1-b01.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 1 | S1-B02 | Emirates group through Orange SA | `master-digest-log-2026-W23-s1-b02.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 1 | S1-B03 | Orange Business through Woolworths | `master-digest-log-2026-W23-s1-b03.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 2 | S2-B01 | ACI Worldwide through DOVISTA | `master-digest-log-2026-W23-s2-b01.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 2 | S2-B02 | Emirates group through Orange SA | `master-digest-log-2026-W23-s2-b02.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 2 | S2-B03 | Orange Business through Woolworths | `master-digest-log-2026-W23-s2-b03.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 3 | S3-B01 | ACI Worldwide through DOVISTA | `master-digest-log-2026-W23-s3-b01.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 3 | S3-B02 | Emirates group through Orange SA | `master-digest-log-2026-W23-s3-b02.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 3 | S3-B03 | Orange Business through Woolworths | `master-digest-log-2026-W23-s3-b03.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 4 | S4-B01 | ACI Worldwide through DOVISTA | `master-digest-log-2026-W23-s4-b01.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 4 | S4-B02 | Emirates group through Orange SA | `master-digest-log-2026-W23-s4-b02.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 4 | S4-B03 | Orange Business through Woolworths | `master-digest-log-2026-W23-s4-b03.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 5 | S5-B01 | ACI Worldwide through DOVISTA | `master-digest-log-2026-W23-s5-b01.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 5 | S5-B02 | Emirates group through Orange SA | `master-digest-log-2026-W23-s5-b02.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 5 | S5-B03 | Orange Business through Woolworths | `master-digest-log-2026-W23-s5-b03.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 6 | S6-B01 | ACI Worldwide through DOVISTA | `master-digest-log-2026-W23-s6-b01.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 6 | S6-B02 | Emirates group through Orange SA | `master-digest-log-2026-W23-s6-b02.md` | yes | Part L row-specific; anti-placeholder check passed. |
| 6 | S6-B03 | Orange Business through Woolworths | `master-digest-log-2026-W23-s6-b03.md` | yes | Part L row-specific; anti-placeholder check passed. |

---

When the matrix is full and drafts are merged, run **`/max-digest-verifier`** (or equivalent) before closing the run.

## See also

- [[sop-master-digest]] — Master SOP that fills this template
- [[accounts-in-scope]] — Account rows tracked in this manifest
- [[batch-lane-log-template]] — Per-batch log template used alongside this
