Batch id: S4-B01 | Signal: 4 | Run id: 2026-W31

# Batch lane log - Signal 4 (Hiring trends in strategic capability areas)

**Run id:** `2026-W31`  
**Signal # (1-6):** `4`  
**Batch id:** `S4-B01`  
**Review period:** 2026-07-21 through 2026-07-27 inclusive  
**Date rule:** posting date where visible, or live official-careers verification during the review pass, per `sops/sop-4-hiring-trends.md`.  
**Account rows in this batch:** ACI Worldwide; Admiral Group Plc; African Development Bank; Almarai - المراعي; AssuredPartners; Bertelsmann, Inc.; Boston Children's Hospital; Capitec bank; Cleaver-Brooks

**Master trade-media sweep:** completed by orchestrator and recorded in `run-manifest-2026-W31.md`; this lane records only row-level signal discovery.

---

## Part A′ - Verified entries (this signal x this batch only)

[hiring-trends] (HIRE)
Account: Admiral Group Plc
Date: 2026-07-27 verification pass; official careers pages live during review pass
Source: Official Admiral careers pages
Link: https://www.admiraljobs.co.uk/human-resources-jobs
What changed: Admiral's official careers surfaces showed a live HR/L&D cluster including Group Talent Development Manager, People, Learning and Development Manager, and Learning Delivery Manager roles.
Why it matters: The cluster points to active investment in learning delivery, talent development and people capability infrastructure rather than a single routine HR backfill.
Relevant stakeholder: Head of Talent Acquisition & Development, People; L&D and talent-development leaders.
Commercial hypothesis: AIHR can credibly engage around scalable learning delivery, talent-development capability and manager enablement for a large insurance workforce.
Score: 20/25 (Relevance 4, Actionability 4, Stakeholder clarity 4, Specificity 4, Timing 4)
Signal: Verified in `master-digest-log-2026-W31-s4-b01.md` from official source URLs listed in Part L.

[hiring-trends] (HIRE)
Account: Capitec bank
Date: 2026-07-27 verification pass; official July postings live during review pass
Source: Official Capitec careers pages
Link: https://careers.capitecbank.co.za/job/Century-City-Academy-Manager-WC/1394157633/
What changed: Capitec had a live professional people-capability cluster including Academy Manager, Manager: People Operations, Strategic People Partner and Employee Relations Consultant roles on official careers pages.
Why it matters: The roles point to continued strengthening of L&D academy design, people operations governance, strategic HR partnering and employee-relations capacity as Capitec scales.
Relevant stakeholder: Academy / L&D leadership; People Operations; Strategic People Partner and HR leadership.
Commercial hypothesis: AIHR can engage around academy design, HR operating-model capability, people analytics, workforce planning and AI-enabled learning for a fast-growing bank.
Score: 23/25 (Relevance 5, Actionability 5, Stakeholder clarity 4, Specificity 5, Timing 4)
Signal: Verified in `master-digest-log-2026-W31-s4-b01.md` from official source URLs listed in Part L.

---

## Part L - Execution log

**Mandatory local-language attempts logged:**  
- African Development Bank - ISO fr: "Banque Africaine de développement" (emploi OR recrutement OR offres OR carrières OR apprentissage OR talents OR SIRH) "juillet" "2026"
- Almarai - المراعي - ISO ar: "المراعي" (وظائف OR توظيف OR تعلم OR مواهب OR الموارد البشرية) "يوليو" "2026"
- Bertelsmann, Inc. - ISO de: "Bertelsmann" (Stellenangebote OR Karriere OR Einstellung OR Lernen OR Talent OR HR-System) "Juli" "2026"

| Account row | Families (1-7) | Queries (full strings) | URLs fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | -------------- | ---------------------- | ------------ | ------- | ------------------------------ | ----------------- | ----- |
| ACI Worldwide | 1, 2, 3, 5; official careers/ATS pass; local-language family 6 where applicable | "ACI Worldwide" (careers OR jobs OR hiring) ("people analytics" OR "talent management" OR "learning" OR "HRIS" OR "workforce planning" OR "organizational development") 2026<br>site:aciworldwide.com (careers OR jobs OR hiring OR "job details") (HR OR Talent OR Learning OR HRIS OR "People Operations") 2026<br>"ACI Worldwide" ("Human Resources" OR "People" OR "Talent" OR "Learning and Development") (jobs OR careers OR hiring) 2026<br>"ACI Worldwide" ("SuccessFactors" OR Workday OR Oracle OR LMS OR "people analytics") (job OR careers OR hiring) 2026 | No candidate URL advanced beyond search-result/date/scope screening for this lane. | Excluded for ACI Worldwide: row-specific account, domain and extended searches found no source in 2026-07-21–2026-07-27 matching Signal 4 definition and master commercial threshold. | Excluded before scoring: no verified in-window candidate with sufficient HR/workforce capability specificity. |  |  |
| Admiral Group Plc | 1, 2, 3, 5; official careers/ATS pass; local-language family 6 where applicable | "Admiral Group Plc" (careers OR jobs OR hiring) ("people analytics" OR "talent management" OR "learning" OR "HRIS" OR "workforce planning" OR "organizational development") 2026<br>site:admiralgroup.co.uk (careers OR jobs OR hiring OR "job details") (HR OR Talent OR Learning OR HRIS OR "People Operations") 2026<br>"Admiral Group Plc" ("Human Resources" OR "People" OR "Talent" OR "Learning and Development") (jobs OR careers OR hiring) 2026<br>"Admiral Group Plc" ("SuccessFactors" OR Workday OR Oracle OR LMS OR "people analytics") (job OR careers OR hiring) 2026 | https://www.admiraljobs.co.uk/human-resources-jobs<br>https://www.admiraljobs.co.uk/job/group-talent-development-manager-in-cardiff-jid-2342<br>https://www.admiraljobs.co.uk/job/people-learning-and-development-manager-in-cardiff-jid-2183<br>https://www.admiraljobs.co.uk/job/learning-delivery-manager-in-cardiff-jid-2731 | Included: official live-careers cluster met Signal 4 volume rule during the 2026-07-27 verification pass; titles and URLs recorded here. | Included: 20/25 (Relevance 4, Actionability 4, Stakeholder clarity 4, Specificity 4, Timing 4) |  |  |
| African Development Bank | 1, 2, 3, 5; official careers/ATS pass; local-language family 6 where applicable | "African Development Bank" (careers OR jobs OR hiring) ("people analytics" OR "talent management" OR "learning" OR "HRIS" OR "workforce planning" OR "organizational development") 2026<br>site:afdb.org (careers OR jobs OR hiring OR "job details") (HR OR Talent OR Learning OR HRIS OR "People Operations") 2026<br>"African Development Bank" ("Human Resources" OR "People" OR "Talent" OR "Learning and Development") (jobs OR careers OR hiring) 2026<br>"African Development Bank" ("SuccessFactors" OR Workday OR Oracle OR LMS OR "people analytics") (job OR careers OR hiring) 2026<br>ISO fr: "Banque Africaine de développement" (emploi OR recrutement OR offres OR carrières OR apprentissage OR talents OR SIRH) "juillet" "2026" | No candidate URL advanced beyond search-result/date/scope screening for this lane. | Excluded for African Development Bank: row-specific account, domain and extended searches found no source in 2026-07-21–2026-07-27 matching Signal 4 definition and master commercial threshold. | Excluded before scoring: no verified in-window candidate with sufficient HR/workforce capability specificity. |  |  |
| Almarai - المراعي | 1, 2, 3, 5; official careers/ATS pass; local-language family 6 where applicable | "Almarai - المراعي" (careers OR jobs OR hiring) ("people analytics" OR "talent management" OR "learning" OR "HRIS" OR "workforce planning" OR "organizational development") 2026<br>site:almarai.com (careers OR jobs OR hiring OR "job details") (HR OR Talent OR Learning OR HRIS OR "People Operations") 2026<br>"Almarai - المراعي" ("Human Resources" OR "People" OR "Talent" OR "Learning and Development") (jobs OR careers OR hiring) 2026<br>"Almarai - المراعي" ("SuccessFactors" OR Workday OR Oracle OR LMS OR "people analytics") (job OR careers OR hiring) 2026<br>ISO ar: "المراعي" (وظائف OR توظيف OR تعلم OR مواهب OR الموارد البشرية) "يوليو" "2026" | No candidate URL advanced beyond search-result/date/scope screening for this lane. | Excluded for Almarai - المراعي: row-specific account, domain and extended searches found no source in 2026-07-21–2026-07-27 matching Signal 4 definition and master commercial threshold. | Excluded before scoring: no verified in-window candidate with sufficient HR/workforce capability specificity. |  |  |
| AssuredPartners | 1, 2, 3, 5; official careers/ATS pass; local-language family 6 where applicable | "AssuredPartners" (careers OR jobs OR hiring) ("people analytics" OR "talent management" OR "learning" OR "HRIS" OR "workforce planning" OR "organizational development") 2026<br>site:assuredpartners.com (careers OR jobs OR hiring OR "job details") (HR OR Talent OR Learning OR HRIS OR "People Operations") 2026<br>"AssuredPartners" ("Human Resources" OR "People" OR "Talent" OR "Learning and Development") (jobs OR careers OR hiring) 2026<br>"AssuredPartners" ("SuccessFactors" OR Workday OR Oracle OR LMS OR "people analytics") (job OR careers OR hiring) 2026 | No candidate URL advanced beyond search-result/date/scope screening for this lane. | Excluded for AssuredPartners: row-specific account, domain and extended searches found no source in 2026-07-21–2026-07-27 matching Signal 4 definition and master commercial threshold. | Excluded before scoring: no verified in-window candidate with sufficient HR/workforce capability specificity. |  |  |
| Bertelsmann, Inc. | 1, 2, 3, 5; official careers/ATS pass; local-language family 6 where applicable | "Bertelsmann, Inc." (careers OR jobs OR hiring) ("people analytics" OR "talent management" OR "learning" OR "HRIS" OR "workforce planning" OR "organizational development") 2026<br>site:bertelsmann.com (careers OR jobs OR hiring OR "job details") (HR OR Talent OR Learning OR HRIS OR "People Operations") 2026<br>"Bertelsmann, Inc." ("Human Resources" OR "People" OR "Talent" OR "Learning and Development") (jobs OR careers OR hiring) 2026<br>"Bertelsmann, Inc." ("SuccessFactors" OR Workday OR Oracle OR LMS OR "people analytics") (job OR careers OR hiring) 2026<br>ISO de: "Bertelsmann" (Stellenangebote OR Karriere OR Einstellung OR Lernen OR Talent OR HR-System) "Juli" "2026" | No candidate URL advanced beyond search-result/date/scope screening for this lane. | Excluded for Bertelsmann, Inc.: row-specific account, domain and extended searches found no source in 2026-07-21–2026-07-27 matching Signal 4 definition and master commercial threshold. | Excluded before scoring: no verified in-window candidate with sufficient HR/workforce capability specificity. |  |  |
| Boston Children's Hospital | 1, 2, 3, 5; official careers/ATS pass; local-language family 6 where applicable | "Boston Children's Hospital" (careers OR jobs OR hiring) ("people analytics" OR "talent management" OR "learning" OR "HRIS" OR "workforce planning" OR "organizational development") 2026<br>site:childrenshospital.org (careers OR jobs OR hiring OR "job details") (HR OR Talent OR Learning OR HRIS OR "People Operations") 2026<br>"Boston Children's Hospital" ("Human Resources" OR "People" OR "Talent" OR "Learning and Development") (jobs OR careers OR hiring) 2026<br>"Boston Children's Hospital" ("SuccessFactors" OR Workday OR Oracle OR LMS OR "people analytics") (job OR careers OR hiring) 2026 | No candidate URL advanced beyond search-result/date/scope screening for this lane. | Excluded for Boston Children's Hospital: row-specific account, domain and extended searches found no source in 2026-07-21–2026-07-27 matching Signal 4 definition and master commercial threshold. | Excluded before scoring: no verified in-window candidate with sufficient HR/workforce capability specificity. |  |  |
| Capitec bank | 1, 2, 3, 5; official careers/ATS pass; local-language family 6 where applicable | "Capitec bank" (careers OR jobs OR hiring) ("people analytics" OR "talent management" OR "learning" OR "HRIS" OR "workforce planning" OR "organizational development") 2026<br>site:capitecbank.co.za (careers OR jobs OR hiring OR "job details") (HR OR Talent OR Learning OR HRIS OR "People Operations") 2026<br>"Capitec bank" ("Human Resources" OR "People" OR "Talent" OR "Learning and Development") (jobs OR careers OR hiring) 2026<br>"Capitec bank" ("SuccessFactors" OR Workday OR Oracle OR LMS OR "people analytics") (job OR careers OR hiring) 2026 | https://careers.capitecbank.co.za/job/Century-City-Academy-Manager-WC/1394157633/<br>https://careers.capitecbank.co.za/job/Century-City-Manager-People-Operations-WC/1398868533/<br>https://careers.capitecbank.co.za/job/Strategic-People-Partner-Stellenbosch/1383194933/<br>https://careers.capitecbank.co.za/job/Employee-Relations-Consultant-Cape-Town/1382342633/ | Included: official live-careers cluster met Signal 4 volume rule during the 2026-07-27 verification pass; titles and URLs recorded here. | Included: 23/25 (Relevance 5, Actionability 5, Stakeholder clarity 4, Specificity 5, Timing 4) |  |  |
| Cleaver-Brooks | 1, 2, 3, 5; official careers/ATS pass; local-language family 6 where applicable | "Cleaver-Brooks" (careers OR jobs OR hiring) ("people analytics" OR "talent management" OR "learning" OR "HRIS" OR "workforce planning" OR "organizational development") 2026<br>site:cleaverbrooks.com (careers OR jobs OR hiring OR "job details") (HR OR Talent OR Learning OR HRIS OR "People Operations") 2026<br>"Cleaver-Brooks" ("Human Resources" OR "People" OR "Talent" OR "Learning and Development") (jobs OR careers OR hiring) 2026<br>"Cleaver-Brooks" ("SuccessFactors" OR Workday OR Oracle OR LMS OR "people analytics") (job OR careers OR hiring) 2026 | No candidate URL advanced beyond search-result/date/scope screening for this lane. | Excluded for Cleaver-Brooks: row-specific account, domain and extended searches found no source in 2026-07-21–2026-07-27 matching Signal 4 definition and master commercial threshold. | Excluded before scoring: no verified in-window candidate with sufficient HR/workforce capability specificity. |  |  |

## Batch summary

- Batch id: S4-B01
- Rows assigned: 9
- Rows with >=1 Part A′ entry: 2 (Admiral Group Plc, Capitec bank)
- Included Part A′ entries: 2
- Flags (count by type): see row table above; no user-approved waivers used.
- Cross-signal hints: none requiring uplift; trade-media near-misses are recorded in the manifest audit table.

---

## See also

- [[sop-4-hiring-trends]]
- [[sop-master-digest]]
- [[accounts-in-scope]]
