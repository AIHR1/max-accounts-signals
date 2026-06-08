Batch id: S4-B04 | Signal: 4 | Run id: 2026-W24

# Batch lane log - Signal 4 hiring trends

**Run id:** `2026-W24`  
**Signal # (1-6):** 4  
**Batch id:** `S4-B04`  
**Review period:** 2026-06-02 through 2026-06-08 inclusive  
**Date rule:** For postings, prefer first-seen-live date in-window or last-updated date if exposed; otherwise the Signal 4 volume rule allows simultaneously live professional postings on official careers properties during the verification pass. For statements, use publication date.  
**Account rows in this batch:** RATP Dev; Schneider Electric; Sony Music Entertainment; Stellenbosch University; Toyota SA; TTEC; Viasat; Viasat Government; VON Canada; Wood Mackenzie; Woolworths.

---

## Part A' - Verified entries (this signal x this batch only)

[hiring-trends] (HIRE)  
Account: Schneider Electric  
Date: 2026-06-08  
Source: Official Schneider Electric careers pages / fetch fallback from official search snippets  
Link: https://www.se.com/ww/en/about-us/careers/job-details/hr-services-senior-manager--talent-acquisition/89965/ ; https://www.se.com/ww/en/about-us/careers/job-details/hr-data-governance-manager/84020/ ; https://www.se.com/ww/en/about-us/careers/job-details/hris-data-specialist/0099RL/ ; https://careers.se.com/jobs/114866?lang=en-us  
What changed: As of the 2026-06-08 verification pass, Schneider Electric's official careers properties surfaced a cluster of professional HR digital, HR data, and talent-technology roles, including HR Services Senior Manager, Talent Acquisition; HR Data Governance Manager; HRIS Data Specialist; and a Human Resource Manager role supporting people-strategy transformations at the Motivair business. Automated fetches of individual pages returned 404, timeouts, or blocked shells, so role text was not over-quoted beyond official-search excerpts.  
Why it matters: The roles concentrate on HR data maturity, HRIS operations, Talent Acquisition technology, AI/data readiness, data governance, and HR transformation execution across Schneider's people-function operating model.  
Relevant stakeholder: Global HR Services / HR Digital Services leadership; Talent Acquisition operations; HR data governance; HRIS / people analytics leaders.  
Commercial hypothesis: AIHR has an evidence-linked conversation around HR data governance, people analytics/data readiness for AI, Talent Acquisition digital operations, and upskilling HR teams to operate global HR technology and governance processes.  
Score: 22/25 (Relevance 5, Actionability 4, Stakeholder clarity 5, Specificity 5, Timing 3)  
Signal: Count-based. Official-search evidence identified at least three professional HR/workforce capability postings on Schneider Electric careers properties during the verification pass. Fetch limitations are logged in Part L as RF-FETCH.

[hiring-trends] (HIRE)  
Account: TTEC  
Date: 2026-06-08  
Source: Official TTEC jobs portal  
Link: https://www.ttecjobs.com/en/search-jobs ; https://www.ttecjobs.com/en/job/cainta/executive-director-learning-and-development/44028/86576310208 ; https://www.ttecjobs.com/en/job/mexico-city/senior-manager-learning-and-development/44028/94993029664 ; https://www.ttecjobs.com/en/job/pampanga/instructional-designer/44028/85979467312 ; https://www.ttecjobs.com/en/job/cairo/french-learning-and-development-coach/44028/94853396864 ; https://www.ttecjobs.com/en/job/hyderabad/hrms-principal-analyst/44028/93672975232  
What changed: As of the 2026-06-08 verification pass, TTEC's official jobs portal showed live category counts of 18 Learning & Development postings and 20 Talent Acquisition postings. Representative professional postings fetched during the pass included Executive Director, Learning & Development; Senior Manager, Learning and Development; Instructional Designer; French Learning and Development Coach; Talent Acquisition Specialist I; and HRMS Principal Analyst for Taleo/recruiting systems.  
Why it matters: The live cluster points to active hiring in learning strategy, training innovation, instructional design, sales enablement, talent acquisition, and HRMS/recruiting technology for a global customer-experience workforce.  
Relevant stakeholder: VP / Head of Learning and Development; Talent Acquisition leadership; HRMS / people systems; sales enablement and operations training leaders.  
Commercial hypothesis: AIHR has a clear opening around scalable L&D operating models, learning analytics, instructional design for virtual/global delivery, TA operations capability, and HR systems skills supporting high-volume workforce needs.  
Score: 23/25 (Relevance 5, Actionability 5, Stakeholder clarity 4, Specificity 5, Timing 4)  
Signal: Count-based. Official portal facet counts supplied the volume proof; fetched role pages verified professional-track examples and no internship/graduate-only roles were counted.

[hiring-trends] (HIRE)  
Account: Wood Mackenzie  
Date: 2026-06-08  
Source: Official Workday careers API / job detail endpoints  
Link: https://woodmac.wd3.myworkdayjobs.com/woodmaccareers ; https://woodmac.wd3.myworkdayjobs.com/wday/cxs/woodmac/woodmaccareers/jobs  
What changed: As of the 2026-06-08 verification pass, Wood Mackenzie's official Workday API returned three full-time regular HR postings: Strategic HR Business Partner (startDate 2026-05-18), Specialist - Human Resources (HR Operations) (startDate 2026-06-04, posted 3 days before verification), and HR Digital Senior Manager (startDate 2026-04-24).  
Why it matters: The postings form a live people-function capability cluster around strategic business partnering, workforce planning, organisational design/change, HR operations/service delivery, employee data, ServiceNow, Workday ownership, and HR digital roadmap execution.  
Relevant stakeholder: Chief People Officer / HR leadership; HR digital; HR operations; people business partnering; workforce planning and organisational design leaders.  
Commercial hypothesis: AIHR has a timely reason to engage on HR digital capability, Workday-enabled HR operating models, people analytics/data skills, strategic HRBP capability, and change/organisation-design skills for HR teams.  
Score: 22/25 (Relevance 5, Actionability 4, Stakeholder clarity 4, Specificity 5, Timing 4)  
Signal: Count-based. Workday CXS search for `HR` returned three full-time regular postings; the HR Operations role was posted within the active review window and all three detail endpoints returned official JSON during verification.

---

## Part L - Execution log

**§7.1a local-language attempts logged:** RATP Dev: `fr`; Schneider Electric: `fr`; Sony Music Entertainment: `ja`; Stellenbosch University: `af`; Toyota SA: `af`; VON Canada: `fr`; Woolworths: `af`.  
**Master §7.2 HR/trade-media sweep:** pending with the orchestrator; this lane did not substitute for the master sweep.

### RATP Dev - ratpdev.com

- **Families run:** 1, 2, 3, 5, 6 (fr); master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"RATP Dev" careers jobs hiring "people analytics" OR "talent management" OR "learning and development" OR HRIS`
  - `site:ratpdev.com OR site:careers.ratpdev.com "RATP Dev" (RH OR HR OR talent OR formation OR SIRH) jobs`
  - `"RATP Dev" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `"RATP Dev USA" "Human Resources Manager" "Permanent contract"`
  - `fr "RATP Dev" recrutement emplois RH talents formation SIRH` (ISO 639-1: fr)
- **URLs fetched / opened:**
  - https://careers.ratpdevusa.com/
  - https://careers.ratpdevusa.com/en/annonce/4248413-human-resources-manager-27704-durham
  - https://careers.ratpdev.com/en/annonce/3751739-people-and-culture-pc-graduate-sydney
  - https://ratpgroup.com/api/media/english-version---20260219---cp---le-groupe-ratp-recrute-pres-de-6-600-personnes-en-2026-dont-3-500-en-ile-de-france.pdf
  - https://careers.ratpdev.com/fr/annonces
  - https://www.jobintree.com/emplois/67376295.html
  - https://bebee.com/fr/jobs/alternant-charge-de-mission-sirh-ratp-dev-paris-ile-de--theirstack-667356407
- **Outcome:** Excluded. The official RATP Group PDF states RATP Dev plans to hire over 3,200 permanent employees in 2026, but the stated needs are broad transit operations/maintenance growth, not a professional HR/workforce capability hiring cluster. The RATP Dev USA Human Resources Manager and RATP Dev People & Culture Graduate pages both returned "job offer unavailable." The French SIRH alternance hit is apprenticeship/alternance and excluded; the French development-of-skills coordinator was third-party and not enough for a three-role official cluster.
- **Commercial gate score / reason:** Excluded before scoring for S4: broad operational hiring and training-system context do not meet the HR/workforce capability hiring trend rule; graduate/alternance items are hard-excluded.
- **Cross-signal hint:** RATP Group PDF may be relevant to S3/S5? for operational ramp-up and training/career-development context, but not S4 hiring trend.
- **Flags:** RF-FETCH (official job detail pages returned unavailable; no live official RATP Dev HR cluster verified).

### Schneider Electric - se.com

- **Families run:** 1, 2, 3, 5, 6 (fr); master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"Schneider Electric" careers jobs hiring "HR data governance" OR HRIS OR "talent acquisition technology" OR "people analytics"`
  - `site:se.com/ww/en/about-us/careers/job-details "Schneider Electric" ("HR Data Governance" OR HRIS OR "Talent Acquisition")`
  - `"Schneider Electric" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `site:careers.se.com/jobs "Schneider Electric" "HRIS" OR "HR Data Governance" OR "HR Services Senior Manager"`
  - `fr "Schneider Electric" recrutement emplois RH talents formation SIRH "HR Data Governance"` (ISO 639-1: fr)
- **URLs fetched / opened:**
  - https://www.se.com/ww/en/about-us/careers/job-details/hr-services-senior-manager--talent-acquisition/89965/
  - https://www.se.com/ww/en/about-us/careers/job-details/hr-data-governance-manager/84020/
  - https://www.se.com/ww/en/about-us/careers/job-details/hris-data-specialist/0099RL/
  - https://careers.se.com/jobs/114866?lang=en-us
  - https://careers.se.com/jobs/0099RL?lang=en-us
  - https://careers.se.com/jobs/89965?lang=en-us
  - https://careers.se.com/jobs/84020?lang=en-us
  - https://www.se.com/ww/en/assets/564/document/466152/2023-human-resources-report.pdf?p_enDocType=EDMS&p_File_Name=2023+People+Report
- **Outcome:** Included. Official-search snippets and official page metadata surfaced at least three professional HR digital/data roles (HR Services Senior Manager, Talent Acquisition; HR Data Governance Manager; HRIS Data Specialist), plus one HR Manager role supporting people-strategy transformation. Automated WebFetch/Shell attempts against the direct URLs returned 404, timeouts, or access-denied behavior, so the entry relies on official-careers search excerpts and logs retrieval limitations rather than inventing dates or role text.
- **Commercial gate score / reason:** Included: 22/25 (Relevance 5, Actionability 4, Stakeholder clarity 5, Specificity 5, Timing 3). Why AIHR: HR data governance, HRIS, TA digital operations, and AI-readiness for HR data. Capability gap/need: HR digital/data operating capability and governance. Stakeholder: HR Services, TA technology, HRIS, HR data governance.
- **Cross-signal hint:** 2023 People Report is historical S6/S5 background for HR tech and talent systems, not an in-period S4 source; Cross-signal: S6?, S5?
- **Flags:** RF-FETCH (Schneider careers pages blocked/timed out/404 in automated fetch, but official search excerpts recovered enough title/domain evidence for S4 inclusion).

### Sony Music Entertainment - sonymusic.com

- **Families run:** 1, 2, 3, 5, 6 (ja); master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"Sony Music Entertainment" careers jobs hiring "People Experience" OR "talent acquisition" OR learning OR HRIS`
  - `site:job-boards.greenhouse.io/sonymusicentertainment "People Experience" OR "Talent Acquisition" OR "Learning"`
  - `"Sony Music Entertainment" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `boards-api.greenhouse.io sonymusicentertainment jobs People Experience Talent Acquisition`
  - `ja "Sony Music Entertainment" 採用 人事 人材育成 研修 HR` (ISO 639-1: ja)
- **URLs fetched / opened:**
  - https://job-boards.greenhouse.io/sonymusicentertainment
  - https://boards-api.greenhouse.io/v1/boards/sonymusicentertainment/jobs?content=true
  - https://job-boards.greenhouse.io/sonymusicentertainment/jobs/8498878002
  - https://job-boards.greenhouse.io/sonymusicentertainment/jobs/8551319002
  - https://job-boards.greenhouse.io/sonymusicentertainment/jobs/8537826002
  - https://job-boards.greenhouse.io/sonymusicentertainment/jobs/8536242002
  - https://www.sonymusic.com/inside-sony-music/introducing-sony-music-careers/
  - https://cocotame.jp/series/105390/
- **Outcome:** Excluded. Official Greenhouse board/API returned 168 jobs, but the relevant HR/People results were only isolated professional postings such as Manager, Benefits; People Experience (HR) Coordinator; Talent Partner; and Technical Talent Acquisition Partner across different units/themes. The board did not show three postings in the same qualifying HR/workforce capability theme. Japanese local-language sources were static career/HR-function descriptions or early-career/new-graduate context, not in-period S4 hiring volume.
- **Commercial gate score / reason:** Excluded before scoring: relevant roles exist, but no verified three-posting same-theme Signal 4 cluster and no in-period company statement about professional HR/workforce capability hiring expansion.
- **Cross-signal hint:** Sony Music Careers launch (2025-09-30) and Cocotame HR article are employer-branding/career-process background; no current cross-signal route.
- **Flags:** None.

### Stellenbosch University - sun.ac.za

- **Families run:** 1, 2, 3, 5, 6 (af); master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"Stellenbosch University" careers jobs hiring "talent management" OR "organizational development" OR "HR governance" OR "learning and development"`
  - `site:sun.ac.za careers "Stellenbosch University" "Human Resources" "Talent Management" jobs`
  - `"Stellenbosch University" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) 2026`
  - `site:sun-e-hr.sun.ac.za "Human Resources" "Talent Management" "Stellenbosch"`
  - `af "Stellenbosch University" loopbane poste menslike hulpbronne talent opleiding ontwikkeling` (ISO 639-1: af)
- **URLs fetched / opened:**
  - https://sun-e-hr.sun.ac.za/OA_HTML/IrcVisitor.jsp
  - https://www.su.ac.za/en/careers-su
  - https://salarymagazine.co.za/public/imisebenzi/imisebenzi/umsebenzi/stellenbosch-university-talent-management-coordinator-stellenbosch-western-cape
  - https://www.myjobmag.co.za/job/human-resources-client-partner-mhb-055-0326-stellenbosch-university
  - https://za.talent.com/view?id=617811165402503931
  - https://www.su.ac.za/af/personeel/menslike-hulpbronne
  - https://staff-development.sun.ac.za/
  - https://staff-development.sun.ac.za/event/su-senior-leadership-management-programme/
- **Outcome:** Excluded. Official SU careers/iRecruitment pages confirmed the Oracle iRecruitment channel but did not expose a current three-role HR/workforce capability cluster during automated verification. Third-party HR/talent roles had closing dates in March/April 2026 or were non-official. Afrikaans local-language results surfaced HR strategy/staff-development pages and a 2026-06-11 leadership programme, which are training/development context rather than current hiring concentration.
- **Commercial gate score / reason:** Excluded before scoring: no verified official S4 hiring volume; static HR/staff development pages do not meet posting or in-period hiring statement rules.
- **Cross-signal hint:** Afrikaans HR and staff-development pages may fit S5? if the orchestrator wants skills/capability-development context; current lane lacks publication/hiring evidence.
- **Flags:** RF-FETCH (iRecruitment page timed out in one WebFetch attempt and is Oracle/script-heavy).

### Toyota SA - toyota.co.za

- **Families run:** 1, 2, 3, 5, 6 (af); master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"Toyota SA" careers jobs hiring "human resources" OR "organizational development" OR "learning and development" OR HRIS`
  - `site:jobs.toyota.co.za "Toyota South Africa Motors" ("Human Resources" OR "Toyota Academy" OR "Organisational Development")`
  - `"Toyota South Africa Motors" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `"Toyota SA" "Learnership Development Administrator" "Toyota Academy" "Human Resources"`
  - `af "Toyota SA" loopbane poste menslike hulpbronne talent opleiding ontwikkeling` (ISO 639-1: af)
- **URLs fetched / opened:**
  - https://jobs.toyota.co.za/
  - https://jobs.toyota.co.za/go/Development-Programmes/5314901/
  - https://jobs.toyota.co.za/go/GRADUATE-TRAINEEPROGRAMME/4077601/
  - https://www.myjobmag.co.za/job/manager-sales-technical-training-toyota
  - https://youthspace.co.za/learnership-development-administrator-lda-at-toyota-south-africa-sandton/
  - https://jobdirecta.co.za/jobs/specialist-hr-organisational-development-at-toyota-sa/
  - https://jobdirecta.co.za/jobs/assistant-manager-hr-12-months-ftc-at-toyota-sa/
  - https://www.bellurbanpace.co.za/learnership-development-administrator-lda-at-toyota-south-africa-motors/
- **Outcome:** Excluded. Official Toyota SA careers pages verified general careers and development/graduate programme pages, but no current professional HR/workforce capability cluster. Third-party Learnership Development Administrator material appears relevant to Toyota Academy/L&D but was not verified on an official current posting; Jobdirecta HR OD and Assistant Manager HR roles had 2025 closing dates. Development and graduate programme pages are early-career/learnership-oriented and hard-excluded for S4 count.
- **Commercial gate score / reason:** Excluded before scoring: no official live three-posting professional cluster; early-career/learnership/graduate programme content is hard-excluded.
- **Cross-signal hint:** Toyota Academy/development programme pages may fit S5? as workforce skills context if publication/timing is separately verified by the orchestrator.
- **Flags:** RF-FETCH (official Toyota careers home timed out once via WebFetch; WebSearch recovered the static official page text).

### TTEC - ttec.com

- **Families run:** 1, 2, 3, 5; master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"TTEC" careers jobs hiring "Learning & Development" OR "Talent Acquisition" OR HRMS OR "people analytics"`
  - `site:ttecjobs.com/en/search-jobs "Learning & Development" "Talent Acquisition" "TTEC"`
  - `"TTEC" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `site:ttecjobs.com/en/job "Learning and Development" "TTEC" "Job Requisition"`
  - `site:ttecjobs.com/en/job "Talent Acquisition" "TTEC" "Job Requisition"`
  - `site:ttecjobs.com/en/job "HRMS Principal Analyst" "Taleo" "TTEC"`
- **URLs fetched / opened:**
  - https://www.ttecjobs.com/en/search-jobs
  - https://www.ttecjobs.com/en/job/mexico-city/senior-manager-learning-and-development/44028/94993029664
  - https://www.ttecjobs.com/en/job/cainta/executive-director-learning-and-development/44028/86576310208
  - https://www.ttecjobs.com/en/job/pampanga/instructional-designer/44028/85979467312
  - https://www.ttecjobs.com/en/job/cairo/french-learning-and-development-coach/44028/94853396864
  - https://www.ttecjobs.com/en/job/austin/seasonal-healthcare-trainer/44028/94827385072
  - https://www.ttecjobs.com/en/job/tempe/talent-acquisition-specialist-i-onsite-tempe/44028/94241011152
  - https://www.ttecjobs.com/en/job/quezon-city/associate-recruiter-novaliches/44028/90578119024
  - https://www.ttecjobs.com/en/job/hyderabad/hrms-principal-analyst/44028/93672975232
  - Radancy endpoint queried by script: `https://www.ttecjobs.com/en/search-jobs/results`
- **Outcome:** Included. Official TTEC jobs search page showed 18 Learning & Development postings and 20 Talent Acquisition postings during the verification pass. Fetched professional examples included L&D executive/senior manager/instructional design/sales enablement roles, plus TA and HRMS/Taleo roles. Seasonal Healthcare Trainer was fetched but not needed for the core count; the inclusion basis is the official L&D category count and representative professional L&D/HRMS/TA role pages.
- **Commercial gate score / reason:** Included: 23/25 (Relevance 5, Actionability 5, Stakeholder clarity 4, Specificity 5, Timing 4). Why AIHR: L&D, sales enablement, TA, and HRMS capability cluster. Capability gap/need: scaled global training, learning analytics, recruiting systems, and TA process skills. Stakeholder: L&D, TA, HRMS, enablement leaders.
- **Cross-signal hint:** None.
- **Flags:** None.

### Viasat - viasat.com

- **Families run:** 1, 2, 3, 5; master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"Viasat" careers jobs hiring "People and Culture" OR "talent acquisition" OR "learning and development" OR HRIS`
  - `site:careers.viasat.com/jobs Viasat (People OR Talent OR Learning OR Recruiter OR HR)`
  - `"Viasat" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `"Viasat" "Recruiter, Temporary" "People, Brand, & Culture"`
  - `"Viasat" "People & Culture" "organizational design" careers`
- **URLs fetched / opened:**
  - https://careers.viasat.com/jobs
  - https://careers.viasat.com/howwehire
  - https://www.viasat.com/perspectives/corporate/2021/paz-patel-working-to-merge-talent-acquisition-with-talent-development-at-viasat/
  - https://media.localjobnetwork.com/job/detail/86039452/Recruiter-Temporary
  - Viasat Jibe pages queried by script: `https://careers.viasat.com/jobs?keyword=people`, `?keyword=talent`, `?keyword=learning`, `?keyword=HR`
- **Outcome:** Excluded. Official Viasat careers pages were Angular/Jibe shells and did not expose a verified current HR/workforce capability count. Third-party temporary recruiter hit is a single role and not sufficient for S4. Viasat's 2021 talent acquisition/development article is outside the active period; careers/how-we-hire pages describe learning culture but not current hiring concentration.
- **Commercial gate score / reason:** Excluded before scoring: no verified three-posting official cluster and no in-period company statement about professional HR/workforce capability hiring expansion.
- **Cross-signal hint:** 2021 talent-acquisition/development article is historical S1/S5 background only, not current.
- **Flags:** RF-BLOCKED-ATS (Viasat Jibe/Angular careers pages did not expose parsable job results through automated fetch/API attempts).

### Viasat Government - viasat.com

- **Families run:** 1, 2, 3, 5; master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"Viasat Government" careers jobs hiring "People and Culture" OR "talent acquisition" OR "learning and development" OR HRIS`
  - `site:careers.viasat.com/jobs "Viasat Government" (People OR Talent OR Learning OR HR)`
  - `"Viasat Government" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `"Viasat Government" "Embedded Software Engineer" careers "learning"`
  - `"Viasat Government" "People Strategy" HR leadership`
- **URLs fetched / opened:**
  - https://careers.viasat.com/jobs/5915?lang=en-us
  - https://careers.viasat.com/jobs
  - https://hrtoday.in/harsha-raghavan-appointed-as-sr-director-people-strategy-at-viasat/
  - https://powertofly.com/up/life-at-viasat-2645017127
- **Outcome:** Excluded. The official Viasat Government job page fetched was an Embedded Software Engineer role and is generic engineering hiring, not HR/workforce capability. Careers search remained script-heavy. HRToday People Strategy appointment content is outside the review period and is not a Signal 4 hiring cluster; PowerToFly is employer/culture content, not current official hiring volume.
- **Commercial gate score / reason:** Excluded before scoring: no Viasat Government-specific HR/workforce capability hiring trend; generic engineering hiring is hard-excluded unless explicitly tied to HR/workforce capability.
- **Cross-signal hint:** HRToday appointment may be S2? if orchestrator separately accepts source quality/timing; PowerToFly culture/learning interview may be historical S1/S5? only.
- **Flags:** RF-BLOCKED-ATS (same Viasat careers/Jibe access limitation as parent row).

### VON Canada - von.ca

- **Families run:** 1, 2, 3, 5, 6 (fr); master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"VON Canada" careers jobs hiring "Human Resources" OR "organizational development" OR "learning and development" OR "talent acquisition"`
  - `site:jobs.jobvite.com/von "VON Canada" ("Human Resource" OR "Labour Relations" OR "Organizational Development")`
  - `"VON Canada" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `"VON Canada" "Human Resource Business Partner" "jobs.jobvite.com/von"`
  - `fr "VON Canada" emplois ressources humaines talents formation développement organisationnel` (ISO 639-1: fr)
- **URLs fetched / opened:**
  - https://von.ca/en/careers
  - https://www.von.ca/fr/emplois
  - https://jobs.jobvite.com/von
  - https://jobs.jobvite.com/von/job/o06svfwN
  - https://remoteotter.com/company/von-canada/jobs/remote-labour-and-employee-relations-officer_c6460c6d-f117-4937-b5ac-d088c7d2cbe9
  - https://remoteotter.com/company/von-canada/jobs/remote-labour-and-employee-relations-coordinator_d72dc4d0-4c59-48b7-8ae4-d8f83e6a8b1a
  - https://jobcanadian.com/fr/von-canada-recruit-com1395
- **Outcome:** Excluded. Official VON careers/Jobvite pages were accessible and, during verification, the "Other Professions (HR, IT, Finance, etc.)" section showed only Fund Development Officer; earlier HR Business Partner URL stated the job listing no longer exists. RemoteOtter/JobCanadian third-party HR/labour-relations items were not verified as current official openings and did not establish a three-posting official cluster. VON's English/French careers pages describe Organizational Development, learning culture, leadership, and retention programmes, but not current S4 hiring volume.
- **Commercial gate score / reason:** Excluded before scoring: no verified official current HR/workforce capability hiring cluster.
- **Cross-signal hint:** VON careers pages may fit S5? as organizational development/leadership-development context, but no active-period publication or hiring signal.
- **Flags:** None.

### Wood Mackenzie - woodmac.com

- **Families run:** 1, 2, 3, 5; master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"Wood Mackenzie" careers jobs hiring HR OR "talent management" OR "learning and development" OR Workday`
  - `site:woodmac.wd3.myworkdayjobs.com/woodmaccareers "Wood Mackenzie" "HR Digital" OR "Strategic HR Business Partner"`
  - `"Wood Mackenzie" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `Wood Mackenzie Workday CXS searchText HR`
  - `Wood Mackenzie Workday CXS searchText Human Resources`
- **URLs fetched / opened:**
  - https://www.woodmac.com/careers/overview/
  - https://www.woodmac.com/careers/your-career/
  - https://woodmac.wd3.myworkdayjobs.com/woodmaccareers
  - Workday CXS endpoint queried by script: `https://woodmac.wd3.myworkdayjobs.com/wday/cxs/woodmac/woodmaccareers/jobs` with searchText `HR` and `Human Resources`
  - Workday CXS detail paths queried by script: `/job/Edinburgh-GB/Strategic-HR-Business-Partner_JR2969`, `/job/Mexico-City-MX/HR-Associate_JR2887`, `/job/Edinburgh-GB/HR-Digital-Senior-Manager-_JR2897`
  - https://www.woodmac.com/siteassets/terms/wm-esg-report-2025.pdf
- **Outcome:** Included. Official Workday API returned three full-time regular HR postings: Strategic HR Business Partner; Specialist - Human Resources (HR Operations); HR Digital Senior Manager. Detail JSON verified start dates and role descriptions. ESG report was used only as background for WoodMac U/Workday/talent marketplace context, not as active-period S4 proof.
- **Commercial gate score / reason:** Included: 22/25 (Relevance 5, Actionability 4, Stakeholder clarity 4, Specificity 5, Timing 4). Why AIHR: HR digital, Workday, HR operations, people solutions, workforce planning, and OD/change. Capability gap/need: HR operating-model and people-data capability. Stakeholder: HR digital/operations and HRBP leaders.
- **Cross-signal hint:** ESG report may fit S5/S6? as historical learning-platform/talent-marketplace context; not the S4 inclusion basis.
- **Flags:** None.

### Woolworths - woolworths.co.za

- **Families run:** 1, 2, 3, 5, 6 (af); master §7.2 trade-media sweep pending with orchestrator.
- **Queries (full strings):**
  - `"Woolworths" "South Africa" careers jobs hiring "Human Resources" OR "talent acquisition" OR "learning and development" OR HRIS`
  - `site:careers.woolworths.co.za "Woolworths" "Talent Acquisition" OR "Regional HR Business Partner" OR "Academy Trainer"`
  - `"Woolworths South Africa" (hiring OR talent OR workforce) (AI OR data OR analytics OR skills) (interview OR blog OR investor) June 2026`
  - `"Woolworths Financial Services" "Talent Acquisition Specialist" "Closing Date"`
  - `af "Woolworths" "Suid-Afrika" loopbane poste menslike hulpbronne talent opleiding ontwikkeling` (ISO 639-1: af)
- **URLs fetched / opened:**
  - https://careers.woolworths.co.za/index.php
  - https://careers.woolworths.co.za/applicant/index.php?controller=Page&name=jobsearch
  - https://careers.woolworths.co.za/applicant/index.php?controller=Page&name=earlycareers
  - https://careers.woolworths.co.za/applicant/index.php?controller=Listings&listingid=1e3c975d-3562-409e-ba10-a27f2c98047f&method=view
  - https://careers.woolworths.co.za/applicant/index.php?controller=Listings&listingid=8cbea010-f4d1-4776-b69d-b96b6d93d88b&method=view
  - https://bebee.com/za/jobs/talent-acquisition-specialist-12-month-contract-woolworths-financial-services-city-of-cape-town-west--theirstack-678297868
  - https://careers.woolworths.co.za/applicant/index.php?advertid=7f0a59d7-23dd-4e84-bfc7-2dd059dab9b1&controller=Adverts&method=view
  - https://careers.woolworths.co.za/applicant/index.php?controller=Listings&listingid=35143a2d-140b-48ff-bc8d-f24e92ce3804&method=view
- **Outcome:** Excluded. Official Woolworths careers home was accessible, but the job-search page returned a script/offline shell in WebFetch and did not expose current role counts. Official Regional HR Business Partner and Academy Trainer pages were under review with 2025/2024 apply-by dates; BeBee Talent Acquisition Specialist showed a 2026-05-13 closing date and was third-party. Official early-careers/trainee programme pages are graduate/trainee/early-career oriented and hard-excluded for S4 count.
- **Commercial gate score / reason:** Excluded before scoring: no verified current official three-posting professional HR/workforce capability cluster; early-careers and trainee programme content is hard-excluded.
- **Cross-signal hint:** Static early-careers/trainee and training content may fit S5? only as background if timing is separately established.
- **Flags:** RF-FETCH (official Woolworths job-search page returned a browser/offline/script shell and did not expose current listings to automated fetch).

## Batch summary

- Batch id: S4-B04
- Rows assigned: 11
- Rows with >=1 Part A' entry: 3 (Schneider Electric; TTEC; Wood Mackenzie)
- Flags (count by type): RF-FETCH: 5 row-level occurrences (RATP Dev, Schneider Electric, Stellenbosch University, Toyota SA, Woolworths); RF-BLOCKED-ATS: 2 row-level occurrences (Viasat, Viasat Government); RF-PAYWALL: 0
- Included entries by account: Schneider Electric (1), TTEC (1), Wood Mackenzie (1)

