Batch id: S6-B04 | Signal: 6 | Run id: 2026-W24

# Batch lane log - S6-B04

**Run id:** `2026-W24`  
**Signal # (1-6):** 6  
**Batch id:** `S6-B04`  
**Review period:** 2026-06-02 through 2026-06-08 inclusive  
**Date rule:** Use announcement publication date or stated go-live date if the release is the first public disclosure of that milestone in-window.  
**Account rows in this batch:** RATP Dev; Schneider Electric; Sony Music Entertainment; Stellenbosch University; Toyota SA; TTEC; Viasat; Viasat Government; VON Canada; Wood Mackenzie; Woolworths.

---

## Part A′ - Verified entries (this signal x this batch only)

No qualifying `[hr-technology]` entries passed S6 Section 8 verification and the master Section 4.1 commercial signal gate for this batch.

## Part L - Execution log

Note: master SOP Section 7.2 HR/HR-tech trade-media sweep is pending with the orchestrator; no waiver is claimed or used in this lane.

### RATP Dev

**Families run:** 1, 2, 3, 5, 6 (extended pass; local language `fr`).

**Queries (full strings):**
- F1: `"RATP Dev" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:ratpdev.com (HRIS OR SIRH OR "learning platform" OR "talent platform" OR Workday OR SuccessFactors) (rollout OR "go-live" OR deployment OR launch OR déploiement) 2026`
- F3: `"RATP Dev" ("case study" OR "customer story" OR "press release") (Workday OR SuccessFactors OR "Oracle HCM" OR LMS OR LXP OR HRIS)`
- F5: `"RATP Dev" ("people systems" OR "digital HR" OR "learning ecosystem" OR "HR transformation") (rollout OR launch OR implementation)`
- F6 local-language attempt: ISO `fr` - `"RATP Dev" (SIRH OR "plateforme de formation" OR "plateforme talents" OR Workday OR SuccessFactors) (déploiement OR lancement OR "mise en œuvre" OR migration)`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://www.beedeez.com/en/case-studies/ratp-dev | Excluded: English Beedeez case-study fetch timed out; French mirror was fetched and assessed. | Not scored for inclusion: fetch failed and mirror did not establish in-window publication/go-live. |  | RF-FETCH |
| https://www.beedeez.com/fr/cas-clients/ratp-dev | Excluded: customer-named LMS deployment for 20,000 employees in 13 countries, but page shows no in-window publication date or stated June 2-8 go-live. | Excluded before scoring: fails S6 date rule despite clear HR/L&D relevance. |  |  |
| https://www.cegid.com/global/case-studies/ratp-dev/ | Excluded: Cegid Talentsoft talent-management case references pre-2020 growth context and no in-window disclosure. | Excluded before scoring: fails date rule. |  |  |
| https://www.joinblink.com/events/on-demand-webinar-building-culture-through-connection | Excluded: RATP Dev USA/Blink employee super-app webinar dated July 31, 2024, not active review period. | Excluded before scoring: fails date rule. |  |  |
| https://www.yomly.com/project/ratp-group/ | Excluded: Yomly HR-process case says client since 2019 and Dubai-only launch, not in-window. | Excluded before scoring: fails date rule. |  |  |

### Schneider Electric

**Families run:** 1, 2, 3, 5, 6 (extended pass; local language `fr`).

**Queries (full strings):**
- F1: `"Schneider Electric" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:se.com (HRIS OR SIRH OR "learning platform" OR "talent platform" OR Workday OR SuccessFactors OR "Oracle HCM") (rollout OR "go-live" OR deployment OR launch OR déploiement) 2026`
- F3: `"Schneider Electric" ("case study" OR "customer story" OR "press release") (Workday OR SuccessFactors OR "Oracle HCM" OR LMS OR LXP OR HRIS OR "talent marketplace")`
- F5: `"Schneider Electric" ("people systems" OR "digital HR" OR "learning ecosystem" OR "HR transformation" OR "skills platform") (rollout OR launch OR implementation)`
- F6 local-language attempt: ISO `fr` - `"Schneider Electric" (SIRH OR "plateforme de formation" OR "plateforme talents" OR Workday OR SuccessFactors OR "Oracle HCM") (déploiement OR lancement OR "mise en œuvre" OR migration) 2026`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://oracle.com/customers/schneider-electric/ | Excluded: Oracle customer page fetch timed out; search snippet indicated existing Oracle Fusion Cloud HCM/analytics case with no in-window go-live. | Not scored for inclusion: fetch failed and no in-window milestone confirmed. |  | RF-FETCH |
| https://www.itpro.com/business/digital-transformation/how-schneider-electric-is-streamlining-onboarding-with-walkme | Excluded: fetched page only returned title; search result dated article April 2, 2026 about WalkMe/SAP Enable Now and Learning Arc pilot, outside active review period. | Excluded before scoring: fails date rule; partial fetch. |  | RF-FETCH |
| https://www.fromdayone.com/stories/2026/3/12/how-schneider-electric-is-powering-a-skillsfirst-future | Excluded: March 12, 2026 VP Learning Excellence article describes Career Hub, skills architecture, and AI coaching pilot, but not a June 2-8 implementation disclosure. | Excluded before scoring: fails date rule. | S1?, S5? |  |
| https://resources.gloat.com/resources/schneider-electric-customer-success-story/ | Excluded: Gloat fetch timed out; search snippets describe 2020-era Open Talent Market rollout, outside review period. | Not scored for inclusion: fetch failed and visible source timing is old. |  | RF-FETCH |

### Sony Music Entertainment

**Families run:** 1, 2, 3, 5, 6 (extended pass; local language `ja` where relevant).

**Queries (full strings):**
- F1: `"Sony Music Entertainment" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:sonymusic.com (HRIS OR "learning platform" OR "talent platform" OR Workday OR SuccessFactors OR "Oracle HCM" OR LMS) (rollout OR "go-live" OR implementation OR launch OR deploy) 2026`
- F3: `"Sony Music Entertainment" ("case study" OR "customer story" OR "press release") (Workday OR SuccessFactors OR "Oracle HCM" OR LMS OR LXP OR HRIS OR "talent platform")`
- F5: `"Sony Music Entertainment" ("people systems" OR "digital HR" OR "learning ecosystem" OR "HR transformation" OR "skills platform") (rollout OR launch OR implementation)`
- F6 local-language attempt: ISO `ja` - `"Sony Music Entertainment" (人事システム OR 学習プラットフォーム OR タレントプラットフォーム OR Workday OR SuccessFactors) (導入 OR 展開 OR ロールアウト OR 移行) 2026`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://www.sonymusic.com/inside-sony-music/introducing-sony-music-careers/ | Excluded: Sony Music Careers hub announced September 30, 2025, not active review period. | Excluded before scoring: fails date rule. |  |  |
| https://hrmasia.com/reimagining-performance-management-sony-musics-approach-to-foster-collaborative-growth/ | Excluded: People Performance Tool article dated September 3, 2024. | Excluded before scoring: fails date rule. | S5? |  |
| https://www.sonymusic.com/inside-sony-music/hr-is-now-px-heres-why/ | Excluded: PX rename and engagement-survey reference dated June 22, 2022; not a current S6 rollout. | Excluded before scoring: fails date rule and lacks S6 deployment milestone. | S1? |  |
| https://www.snaplogic.com/resources/webcasts/sonys-modern-hr-infrastructure | Excluded: vendor webinar says Sony integrates Workday globally across 90 business units, but page is undated and no June 2-8 milestone is stated. | Excluded before scoring: fails date rule; vendor page has customer speaker but no active-period disclosure. |  |  |

### Stellenbosch University

**Families run:** 1, 2, 3, 5, 6 (extended pass; local language `af` where relevant).

**Queries (full strings):**
- F1: `"Stellenbosch University" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:sun.ac.za (HRIS OR "learning platform" OR "talent platform" OR LMS OR "Oracle HCM" OR Workday OR SuccessFactors) (rollout OR "go-live" OR implementation OR migration OR launch OR deploy) 2026`
- F3: `"Stellenbosch University" ("case study" OR "customer story" OR "press release") (LMS OR "learning management system" OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS)`
- F5: `"Stellenbosch University" ("digital HR" OR "people systems" OR "learning ecosystem" OR "HR transformation" OR "talent platform") (rollout OR launch OR implementation)`
- F6 local-language attempt: ISO `af` - `"Stellenbosch Universiteit" (menslikehulpbronstelsel OR "leerplatform" OR "talent platform" OR Workday OR SuccessFactors OR HRIS) (implementering OR bekendstelling OR uitrol OR migrasie) 2026`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://www.su.ac.za/en/staff/human-resources | Excluded: official HR page describes HR service model and HRIS/admin function but no in-window implementation, go-live, migration, or rollout. | Excluded before scoring: no S6 milestone. |  |  |
| http://stbweb01.stb.sun.ac.za/ekampus/sun-e-HR/index.htm | Excluded: legacy Sun-e-HR page returned 404 on fetch; search snippet indicated copyright 2005/legacy Oracle HR platform, not active review period. | Not scored for inclusion: fetch failed and visible evidence is legacy. |  | RF-FETCH |
| https://www.smfnews.org/learning-technology-issues-continue-to-frustrate-stellenbosch-university-students/ | Excluded: SUNStudent/SUNLearn issues concern student academic/learning systems and registration period, not employee HR or workforce learning technology; no June 2-8 go-live stated. | Excluded before scoring: out of S6 scope for people/employee tech and no in-window milestone. |  |  |
| https://www.su.ac.za/en/node/5851 | Excluded: SUNFin finance-system page timed out; search snippets show old finance go-live planning, not HR/learning tech. | Not scored for inclusion: fetch failed and source is outside S6 scope. |  | RF-FETCH |

### Toyota SA

**Families run:** 1, 2, 3, 5, 6 (extended pass; local language `af` where relevant).

**Queries (full strings):**
- F1: `"Toyota SA" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:toyota.co.za (HRIS OR "learning platform" OR "talent platform" OR LMS OR Workday OR SuccessFactors OR "Oracle HCM") (rollout OR "go-live" OR implementation OR migration OR launch OR deploy) 2026`
- F3: `"Toyota South Africa" ("case study" OR "customer story" OR "press release") (LMS OR "learning management system" OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "talent platform")`
- F5: `"Toyota South Africa" ("digital HR" OR "people systems" OR "learning ecosystem" OR "HR transformation" OR "skills platform") (rollout OR launch OR implementation)`
- F6 local-language attempt: ISO `af` - `"Toyota Suid-Afrika" (menslikehulpbronstelsel OR leerplatform OR talentplatform OR Workday OR SuccessFactors OR HRIS) (implementering OR bekendstelling OR uitrol OR migrasie) 2026`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://news.sap.com/africa/2025/11/ibm-accelerates-digital-transformation-for-toyota-south-africa-motors-with-sap-s-4hana-upgrades/ | Excluded: SAP/IBM announcement dated November 26, 2025 says HR systems/payroll/personnel administration were modernized on SAP S/4HANA, but outside review period and no Toyota customer quote. | Excluded before scoring: fails date rule; vendor/partner-only corroboration would be insufficient for inclusion. | S3? |  |
| https://www.itweb.co.za/article/toyota-sa-invests-in-sap-upgrades-to-accelerate-digital-transformation/4r1lyMR9VrX7pmda | Excluded: ITWeb article dated November 27, 2025 mirrors IBM/SAP statement; no active-period disclosure. | Excluded before scoring: fails date rule. | S3? |  |
| https://www.k5business.com/2017/02/22/toyota-selects-k5-business-nga-implement-sap-successfactors/ | Excluded: 2017 selection/implementation plan for SAP SuccessFactors; not a 2026 in-window go-live. | Excluded before scoring: fails date rule. |  |  |

### TTEC

**Families run:** 1, 2, 3, 5, extended English retry (no local-language ISO assigned for this row).

**Queries (full strings):**
- F1: `"TTEC" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:ttec.com (HRIS OR "learning platform" OR "talent platform" OR LMS OR Workday OR SuccessFactors OR "Oracle HCM") (rollout OR "go-live" OR implementation OR migration OR launch OR deploy) 2026`
- F3: `"TTEC" ("case study" OR "customer story" OR "press release") (LMS OR "learning management system" OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "talent platform")`
- F5: `"TTEC" ("digital HR" OR "people systems" OR "learning ecosystem" OR "HR transformation" OR "skills platform" OR "employee experience platform") (rollout OR launch OR implementation)`
- Extended retry: `"TTEC" "HR technology" Workday SuccessFactors "2026" "rollout" OR "go-live"`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://investors.ttec.com/news-releases/news-release-details/ttec-sets-new-standard-ai-driven-frontline-performance-ttec | Excluded: official/investor page fetch timed out; search/Nasdaq snippets date the RealSkill/Perform expansion to February 16, 2026 and describe TTEC offerings/client adoption rather than an internal June S6 go-live. | Not scored for inclusion: fetch failed; visible evidence fails date rule and customer corroboration for a named client. |  | RF-FETCH |
| https://investors.ttec.com/news-releases/news-release-details/ttec-wins-gold-ai-powered-learning-innovation-brandon-hall-group | Excluded: official/investor page fetch timed out; search snippets date Learning Wizards award to January 15, 2026, outside active period. | Not scored for inclusion: fetch failed and timing outside review period. |  | RF-FETCH |
| https://www.nasdaq.com/press-release/ttec-sets-new-standard-ai-driven-frontline-performance-ttec-performtm-and-ttec | Excluded: Nasdaq mirror fetch timed out; search snippet dated February 16, 2026 and lacked in-window deployment. | Not scored for inclusion: fetch failed and timing outside review period. |  | RF-FETCH |
| https://www.ttec.com/newsroom/press-release/ttec-and-bright-software-unveil-ai-enhanced-learning-solution-elevate | Excluded: official TTEC/Bright strategic alliance dated April 23, 2024; not active review period. | Excluded before scoring: fails date rule. |  |  |

### Viasat

**Families run:** 1, 2, 3, 5, extended English retry (no local-language ISO assigned for this row).

**Queries (full strings):**
- F1: `"Viasat" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:viasat.com (HRIS OR "learning platform" OR "talent platform" OR LMS OR Workday OR SuccessFactors OR "Oracle HCM") (rollout OR "go-live" OR implementation OR migration OR launch OR deploy) 2026`
- F3: `"Viasat" ("case study" OR "customer story" OR "press release") (LMS OR "learning management system" OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "talent platform")`
- F5: `"Viasat" ("digital HR" OR "people systems" OR "learning ecosystem" OR "HR transformation" OR "skills platform") (rollout OR launch OR implementation)`
- Extended retry: `"Viasat" "HR technology" Workday SuccessFactors "2026" "rollout" OR "go-live"`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://www.kainos.com/insights/success-stories/viasat-streamlines-ma-workday-effort-and-mitigates-risk-with-smart-test | Excluded: Kainos case dated June 30, 2023 describes Viasat Workday Smart Test and M&A data testing, not in-window. | Excluded before scoring: fails date rule. |  |  |
| https://live.euronext.com/en/products/equities/company-news/2026-05-19-atos-selected-viasat-modernize-global-digital-workplace | Excluded: Atos digital workplace modernization announcement dated May 19, 2026; employee experience/service-desk/collaboration focus, not an HR/learning system go-live, and outside active period. | Excluded before scoring: fails date rule and S6 scope. | S3? |  |
| https://www.avature.net/case-study/optimizing-campus-recruiting-how-viasat-captivates-tomorrows-talent/ | Excluded: Avature campus recruiting case has customer quote and ATS/CRM relevance but no in-window publication/go-live date. | Excluded before scoring: fails date rule. |  |  |

### Viasat Government

**Families run:** 1, 2, 3, 5, extended English retry (no local-language ISO assigned for this row).

**Queries (full strings):**
- F1: `"Viasat Government" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:viasat.com/government (HRIS OR "learning platform" OR "talent platform" OR LMS OR Workday OR SuccessFactors OR "Oracle HCM") (rollout OR "go-live" OR implementation OR migration OR launch OR deploy) 2026`
- F3: `"Viasat Government" ("case study" OR "customer story" OR "press release") (LMS OR "learning management system" OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "talent platform")`
- F5: `"Viasat Government" ("digital HR" OR "people systems" OR "learning ecosystem" OR "HR transformation" OR "skills platform") (rollout OR launch OR implementation)`
- Extended retry: `"Viasat Government" "HR technology" Workday SuccessFactors "2026" "rollout" OR "go-live"`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://www.kainos.com/insights/success-stories/viasat-streamlines-ma-workday-effort-and-mitigates-risk-with-smart-test | Excluded: enterprise Viasat Workday/Kainos case dated June 30, 2023; no Viasat Government-specific June 2026 HR-tech go-live. | Excluded before scoring: fails date rule and lacks row-specific Government milestone. |  |  |
| https://live.euronext.com/en/products/equities/company-news/2026-05-19-atos-selected-viasat-modernize-global-digital-workplace | Excluded: enterprise digital workplace modernization dated May 19, 2026, outside active period and not S6 HR/learning platform. | Excluded before scoring: fails date rule and S6 scope. | S3? |  |

### VON Canada

**Families run:** 1, 2, 3, 5, 6 (extended pass; local language `fr`).

**Queries (full strings):**
- F1: `"VON Canada" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:von.ca (HRIS OR "learning platform" OR "talent platform" OR LMS OR Workday OR SuccessFactors OR "Oracle HCM") (rollout OR "go-live" OR implementation OR migration OR launch OR deploy) 2026`
- F3: `"VON Canada" ("case study" OR "customer story" OR "press release") (LMS OR "learning management system" OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "talent platform")`
- F5: `"VON Canada" ("digital HR" OR "people systems" OR "learning ecosystem" OR "HR transformation" OR "skills platform") (rollout OR launch OR implementation)`
- F6 local-language attempt: ISO `fr` - `"VON Canada" (SIRH OR "plateforme de formation" OR "plateforme talents" OR Workday OR SuccessFactors OR "Oracle HCM") (déploiement OR lancement OR "mise en œuvre" OR migration) 2026`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://von.ca/en/news/year-transformation-von-connect | Excluded: VON Connect/AlayaCare page dated December 1, 2025; mentions Oxford and Perth Huron go-live scheduled January 26, 2026 and remaining Ontario sites targeted by mid-2026, but no June 2-8 stated go-live or first disclosure. | Excluded before scoring: fails date rule; also primarily digital health/EHR transformation rather than HR/learning tech. | S3? | RF-CLASSIFICATION |
| https://von.ca/en/news/von-connect-welcome-ontario | Excluded: VON Connect Ontario launch page dated August 1, 2025 with July 28 go-live, outside review period. | Excluded before scoring: fails date rule. | S3? | RF-CLASSIFICATION |
| https://von.ca/en/news/why-von-connect | Excluded: VON Connect overview dated August 15, 2023; beta launch April 3, 2023, not active review period. | Excluded before scoring: fails date rule. | S3? | RF-CLASSIFICATION |
| https://von.ca/en/news/von-proud-recipient-alayacares-early-adopter-award | Excluded: AlayaCare award dated October 10, 2025, not an in-window implementation disclosure. | Excluded before scoring: fails date rule. | S3? | RF-CLASSIFICATION |

### Wood Mackenzie

**Families run:** 1, 2, 3, 5, extended English retry (no local-language ISO assigned for this row).

**Queries (full strings):**
- F1: `"Wood Mackenzie" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:woodmac.com (HRIS OR "learning platform" OR "talent platform" OR LMS OR Workday OR SuccessFactors OR "Oracle HCM") (rollout OR "go-live" OR implementation OR migration OR launch OR deploy) 2026`
- F3: `"Wood Mackenzie" ("case study" OR "customer story" OR "press release") (LMS OR "learning management system" OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "talent platform")`
- F5: `"Wood Mackenzie" ("digital HR" OR "people systems" OR "learning ecosystem" OR "HR transformation" OR "skills platform") (rollout OR launch OR implementation)`
- Extended retry: `"Wood Mackenzie" "HR technology" Workday SuccessFactors "2026" "rollout" OR "go-live"`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://www.perkbox.com/resources/stories/wood-mackenzie | Excluded: Perkbox case has customer quotes on global recognition/wellness platform launch and 90-day activation results, but no publication date or stated June 2-8 go-live. | Excluded before scoring: fails date rule. |  |  |
| https://www.pareto.vip/testimonials/case-studies/wood-mackenzie.html | Excluded: Pareto apprenticeship/training case is not a technology implementation or rollout and has no in-window date. | Excluded before scoring: outside S6 scope and date rule. | S5? |  |
| https://bebee.com/gb/jobs/hr-digital-senior-manager-wood-mackenzie-edinburgh--theirstack-670677452 | Excluded: single job posting for HR Digital Senior Manager, active until June 24, 2026, evidences ongoing Workday ownership but not a company announcement of a new implementation/go-live. | Excluded by master Section 4.1: single job posting; no S6 rollout milestone. |  |  |

### Woolworths

**Families run:** 1, 2, 3, 5, 6 (extended pass; local language `af` where relevant).

**Queries (full strings):**
- F1: `"Woolworths South Africa" (LMS OR LXP OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "learning platform" OR "talent platform") (go-live OR rollout OR implementation OR migration OR launch OR deploy) "June" "2026"`
- F2: `site:woolworths.co.za (HRIS OR "learning platform" OR "talent platform" OR LMS OR Workday OR SuccessFactors OR "Oracle HCM") (rollout OR "go-live" OR implementation OR migration OR launch OR deploy) 2026`
- F3: `"Woolworths South Africa" ("case study" OR "customer story" OR "press release") (LMS OR "learning management system" OR Workday OR SuccessFactors OR "Oracle HCM" OR HRIS OR "talent platform")`
- F5: `"Woolworths South Africa" ("digital HR" OR "people systems" OR "learning ecosystem" OR "HR transformation" OR "skills platform") (rollout OR launch OR implementation)`
- F6 local-language attempt: ISO `af` - `"Woolworths Suid-Afrika" (menslikehulpbronstelsel OR leerplatform OR talentplatform OR Workday OR SuccessFactors OR HRIS) (implementering OR bekendstelling OR uitrol OR migrasie) 2026`

**Fetched candidate outcomes:**

| URL fetched | Outcome | Commercial gate score / reason | Cross-signal hint | Flags |
| ----------- | ------- | ------------------------------ | ----------------- | ----- |
| https://www.woolworthsholdings.co.za/people/ | Excluded: official People page describes future-fit HR systems/data and digitising operations, but no in-window implementation or go-live. | Excluded before scoring: no S6 milestone. |  |  |
| https://insidesap.com/woolworths-deploys-successfactors-to-activate-high-performance-people-strategy/ | Excluded: historical SuccessFactors case appears to concern Woolworths Australia scale (198,000 employees/2,700 locations and Australian data-centre references), not the Woolworths South Africa row; no in-window date. | Excluded before scoring: identity mismatch and date rule fail. |  | RF-IDENTITY |
| https://www.woolworthsholdings.co.za/woolworths-accelerates-its-investment-into-omni-channel-capabilities/ | Excluded: official omnichannel/digital capabilities announcement dated October 7, 2021; customer/digital-commerce focus, not HR/learning tech. | Excluded before scoring: outside S6 scope and date rule. | S3? |  |
| https://careers.woolworths.co.za/applicant/index.php?controller=Listings&listingid=3013bfa7-7737-4fa7-9b6d-6abe49d2b05f&method=view | Excluded: careers page fetch returned Chromium/network error content; search snippet showed single Workforce Management Specialist posting with implementation/support duties, not an enterprise announcement. | Excluded by master Section 4.1: single job posting; fetch degraded. |  | RF-FETCH |

## Batch summary

- Batch id: S6-B04
- Rows assigned: 11
- Rows with >=1 Part A′ entry: 0
- Flags (count by type): RF-FETCH: 10; RF-IDENTITY: 1; RF-CLASSIFICATION: 4; RF-BLOCKED-ATS: 0; RF-PAYWALL: 0.
- No CHECKPOINT: Section 7 minimums and extended passes were completed for every assigned row.

---

