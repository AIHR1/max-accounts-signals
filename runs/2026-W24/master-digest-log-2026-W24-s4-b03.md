Batch id: S4-B03 | Signal: 4 | Run id: 2026-W24

# Batch lane log — Signal 4 hiring trends

**Run id:** `2026-W24`  
**Signal # (1–6):** 4  
**Batch id:** `S4-B03`  
**Review period:** 2026-06-02 through 2026-06-08 inclusive  
**Date rule:** For postings, prefer first-seen-live date in-window or last-updated date if exposed; otherwise verification date for simultaneously live official careers postings. For statements, use publication date.  
**Account rows in this batch:** Logitech; Logitech USA; Mercury Insurance; METRO AG; Momentum Metropolitan; Orange Group; Orange SA; Orange Business; Oscar Health; Phoenix Contact; Pierre Fabre Laboratories.

---

## Part A′ — Verified entries (this signal × this batch only)

[hiring-trends] (HIRE)
Account: Logitech  
Date: 2026-06-08  
Source: Official careers portal / Workday public jobs API  
Link: https://logitech.wd5.myworkdayjobs.com/en-US/Logitech  
What changed: As of verification on 2026-06-08, Logitech's official Workday jobs API showed a live cluster of professional People & Culture / HR operations roles, including Talent Acquisition Partner (posted 5 days ago), Sr. Total Rewards Analyst, two People Services Administrator postings, and Benefits Operations Specialist.  
Why it matters: The cluster points to active investment in People Services, talent acquisition, total rewards, HRIS/Workday operations, and HR process improvement across regions.  
Relevant stakeholder: Global People & Culture leadership; People Experience & Services; Talent Acquisition; Total Rewards / HRIS leaders.  
Commercial hypothesis: AIHR-relevant conversation around scaling HR operations, Workday-enabled people services, talent acquisition capability, and rewards/people-data skills for a distributed global workforce.  
Score: 22/25 (Relevance 5, Actionability 4, Stakeholder clarity 5, Specificity 4, Timing 4)  
Signal: Count-based. Official Workday CXS query returned professional postings after excluding the People & Culture intern and generic non-HR roles; counted postings included job reqs 146487, 146704, 146271, 146272, and 146221.

[hiring-trends] (HIRE)
Account: Mercury Insurance  
Date: 2026-06-08  
Source: Official careers portal / iCIMS postings plus CPO-attributed LinkedIn statement  
Link: https://careers-mercuryinsurance.icims.com/jobs/search?ss=1&searchKeyword=Human%20Resources  
What changed: As of verification on 2026-06-08, Mercury's official iCIMS careers site listed multiple Human Resources openings, including Talent Acquisition Coordinator, Senior Manager Talent Acquisition - Technology, and Sr Manager Compensation; a Chief People Officer LinkedIn post also stated Mercury is building a "next-generation People Team" with people operations, analytics, work design, and people business partner leadership roles.  
Why it matters: The postings and executive statement show hiring concentration around AI-enabled recruiting, compensation analytics, People Business Partnering, and People Operations/Analytics as part of a broader people-function redesign.  
Relevant stakeholder: Chief People Officer; Talent Acquisition leadership; Compensation / Total Rewards; People Analytics / People Operations leaders.  
Commercial hypothesis: AIHR-relevant conversation around talent acquisition transformation, AI-enabled recruiting, compensation analytics, people analytics, and operating-model skills for a next-generation People Team.  
Score: 23/25 (Relevance 5, Actionability 4, Stakeholder clarity 5, Specificity 5, Timing 4)  
Signal: Count/statement-based. Official iCIMS pages verified current roles 2026-6471, 2026-6403, and 2026-6256; LinkedIn statement was from Jenny Chan, Chief People Officer, but dated "2mo" so it supports context rather than the in-period posting date.

[hiring-trends] (HIRE)
Account: Momentum Metropolitan  
Date: 2026-06-08  
Source: Official eRecruit careers portal  
Link: https://momentumgroupltd.erecruit.co/candidateapp/Jobs/Categories/Human_Capital  
What changed: As of verification on 2026-06-08, Momentum Group's official eRecruit Human Capital category exposed four live Human Capital postings: Talent Acquisition Specialist, Senior Reward Analyst Design, Advisory & Governance, Organisational Development Consultant, and Talent Pool: Workforce Planner, with closing dates from 2026-06-09 to 2026-06-30.  
Why it matters: The cluster indicates current hiring in talent acquisition, rewards strategy, organizational development, and workforce planning/analytics capabilities.  
Relevant stakeholder: Group Human Capital; Talent Acquisition; Reward / Compensation; Organizational Development; Workforce Planning leaders.  
Commercial hypothesis: AIHR-relevant conversation around building Human Capital capability in workforce planning, organizational development, rewards analytics, and talent acquisition across a financial-services group.  
Score: 22/25 (Relevance 5, Actionability 4, Stakeholder clarity 4, Specificity 5, Timing 4)  
Signal: Count-based. Official eRecruit postings verified as professional roles; no internships, graduate intakes, or early-career-only roles were counted.

[hiring-trends] (HIRE)
Account: Oscar Health  
Date: 2026-06-08  
Source: Official Greenhouse careers board API / hioscar careers URLs  
Link: https://boards-api.greenhouse.io/v1/boards/oscar/jobs?content=true  
What changed: As of verification on 2026-06-08, Oscar's official Greenhouse board listed a live People/Talent/Learning cluster including Director, Talent Management; two People Services Coordinator postings; four Senior Learning Specialist postings; and Senior People Strategy Partner.  
Why it matters: The postings show hiring concentration around enterprise talent management, people services, decentralized learning, and people strategy support for a technology-enabled health insurer.  
Relevant stakeholder: Chief People Officer / VP Talent; People Strategy; Talent Management; Learning; People Services leaders.  
Commercial hypothesis: AIHR-relevant conversation around talent management strategy, learning operations, people services scaling, and people-data-enabled HR partnering.  
Score: 23/25 (Relevance 5, Actionability 4, Stakeholder clarity 5, Specificity 5, Timing 4)  
Signal: Count-based. Official Greenhouse board returned 241 total jobs and at least eight live People/Learning/Talent postings; counted postings included hioscar career IDs 7750797, 7964056, 7975478, 7927693, 7961317, 7961316, 7961312, and 7939940.

---

## Part L — Execution log

### Logitech

- **Families run:** 1, 2, 3, 5, 6.
- **Queries (full strings):**
  - `"Logitech" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:jobs.lever.co/logitech OR site:careers.logitech.com Logitech "People" "Talent" "HR" jobs`
  - `"Logitech" hiring talent workforce skills analytics interview blog investor June 2026`
  - `"People Services Administrator" "Logitech" "Apply" "Workday"`
  - `"Benefits Operations Specialist" "Logitech" "Apply" "Workday"`
  - `de "Logitech" Karriere Stellenangebote "People" "Talent" "HRIS" "Learning"` (ISO 639-1: de)
  - `fr "Logitech" carrières offres emploi "People" "talent" "SIRH" "formation"` (ISO 639-1: fr)
- **URLs fetched / opened:**
  - https://www.logitech.com/en-us/careers
  - https://www.logitech.com/en-eu/careers
  - https://jobs.jobvite.com/logitech/jobs/brand?s=Logitech
  - https://logitech.wd5.myworkdayjobs.com/en-US/Logitech/job/Benefits-Operations-Specialist_146221
  - Workday CXS endpoint queried by script: `https://logitech.wd5.myworkdayjobs.com/wday/cxs/logitech/Logitech/jobs`
  - Workday CXS detail paths queried by script: `/job/Hsinchu-Taiwan/Talent-Acquisition-Partner--Fixed-term-contractor-_146487`, `/job/Hsinchu-Taiwan/Sr-Total-Rewards-Analyst_146704`, `/job/Hsinchu-Taiwan/People-Services-Administrator--1-year-contract--_146271`, `/job/Hsinchu-Taiwan/People-Services-Administrator--1-year-contract--_146272`, `/job/Offsite---USA---TX/Benefits-Operations-Specialist_146221`
  - https://builtin.com/job/people-services-program-lead/6691023
  - https://www.cake.me/companies/logitech/jobs/22ca04fa79a71000d9837733ea340000-people-services-administrator-1-yea-566ea2f1aba24a05bb4aacd2801b97
  - https://www.cake.me/companies/logitech/jobs/637667e5332d1000bc4a36080c430000-benefits-operations-specialist-6999477366beff31ab714b7b9a0f5c
- **Outcome:** Included. Official Workday CXS API verified at least five professional HR / People & Culture postings live or posted recently; third-party mirrors were used only as discovery aids. BuiltIn People Services Program Lead was excluded from the count because the fetched page says the job was removed on 2025-09-29.
- **Commercial gate score / reason:** Included at 22/25; clear AIHR relevance to HR operations, People Services, Talent Acquisition, Total Rewards, Workday/HRIS, and process transformation.
- **Cross-signal hint:** None.
- **Flags:** RF-FETCH (Logitech Workday UI page fetched as empty/script-heavy; Workday CXS endpoint recovered enough official data).

### Logitech USA

- **Families run:** 1, 2, 3, 5, 6.
- **Queries (full strings):**
  - `"Logitech USA" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:jobs.lever.co/logitech "United States" Logitech "People" "Talent" "HR"`
  - `"Logitech USA" hiring talent workforce skills analytics interview blog investor June 2026`
  - `"Logitech USA" "Benefits Operations Specialist" "Talent Acquisition" "People Services" "Workday"`
  - `de "Logitech USA" Karriere Stellenangebote "People" "Talent" "HRIS" "Learning"` (ISO 639-1: de)
  - `fr "Logitech USA" carrières offres emploi "People" "talent" "SIRH" "formation"` (ISO 639-1: fr)
- **URLs fetched / opened:**
  - https://www.logitech.com/en-us/careers
  - Workday CXS endpoint queried by script: `https://logitech.wd5.myworkdayjobs.com/wday/cxs/logitech/Logitech/jobs`
  - Workday CXS detail path queried by script: `/job/Offsite---USA---TX/Benefits-Operations-Specialist_146221`
  - https://www.cake.me/companies/logitech/jobs/637667e5332d1000bc4a36080c430000-benefits-operations-specialist-6999477366beff31ab714b7b9a0f5c
- **Outcome:** Excluded. The USA-specific verification found one U.S. benefits/People Operations posting; global Logitech roles were not counted for the USA row because rows are atomic and no three-posting U.S.-specific HR/workforce-capability cluster was verified.
- **Commercial gate score / reason:** Excluded: single qualifying U.S. posting, below Signal 4 volume threshold; otherwise relevant but insufficient trend proof.
- **Cross-signal hint:** None.
- **Flags:** RF-FETCH (Workday UI script-heavy; API recovered the single U.S. role).

### Mercury Insurance

- **Families run:** 1, 2, 3, 5.
- **Queries (full strings):**
  - `"Mercury Insurance" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:mercuryinsurance.com careers jobs Mercury Insurance HRIS "Talent" "Learning"`
  - `"Mercury Insurance" hiring talent workforce skills analytics interview blog investor June 2026`
  - `"Director of People Operations & Analytics" "Mercury Insurance" "careers-mercuryinsurance.icims.com"`
  - `"Head of People Business Partners" "Mercury Insurance" "careers-mercuryinsurance.icims.com"`
  - `"Director of Work Design & Innovation" "Mercury Insurance" "careers-mercuryinsurance.icims.com"`
  - `"Mercury Insurance" "next-generation People Team" "Director of People Operations"`
- **URLs fetched / opened:**
  - https://www.mercuryinsurance.com/about/careers-jobs/careers-in-human-capital.html
  - https://remotive.com/remote/jobs/hr/director-of-people-operations-analytics-4000123
  - https://careers-mercuryinsurance.icims.com/jobs/intro?mobile=true&needsRedirect=false
  - https://careers-mercuryinsurance.icims.com/jobs/search?ss=1&searchKeyword=People
  - https://careers-mercuryinsurance.icims.com/jobs/search?ss=1&searchKeyword=Human%20Resources
  - https://www.linkedin.com/posts/jennydchan_we-are-building-a-next-generation-people-activity-7439398497835020288-abSA
  - https://careers-mercuryinsurance.icims.com/jobs/6471/talent-acquisition-coordinator/job
  - https://careers-mercuryinsurance.icims.com/jobs/6403/senior-manager-talent-acquisition---technology/job
  - https://careers-mercuryinsurance.icims.com/jobs/6256/sr-manager-compensation/job
- **Outcome:** Included. Official iCIMS verified three current HR roles and the CPO-attributed LinkedIn post provided supporting context for a next-generation People Team. Remotive candidate URL returned 404 and was not used as primary proof.
- **Commercial gate score / reason:** Included at 23/25; role cluster clearly maps to TA technology, compensation analytics, people operations, and AI-enabled recruiting.
- **Cross-signal hint:** LinkedIn CPO statement may fit S1 if in-scope dates are separately accepted by the orchestrator, but it is dated "2mo" and outside this review-period lane's inclusion basis; Cross-signal: S1?
- **Flags:** RF-FETCH for Remotive 404 (not used); no ATS block on iCIMS.

### METRO AG

- **Families run:** 1, 2, 3, 5, 6.
- **Queries (full strings):**
  - `"METRO AG" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:metroag.de careers jobs "METRO AG" HRIS Talent Learning People Analytics`
  - `"METRO AG" hiring talent workforce skills analytics interview blog investor June 2026`
  - `"METRO AG" "Traineeprogramm People & Culture" "careers.metroag.de"`
  - `site:careers.metroag.de/jobs "Human Resources" "METRO AG" "People" "Culture" "Düsseldorf"`
  - `de "METRO AG" Karriere Stellenangebote "People & Culture" "Learning" "Talent"` (ISO 639-1: de)
  - `de "METRO AG" Karriere Stellenangebote "People & Culture" "Learning" "Talent" "HR Analytics"` (ISO 639-1: de)
- **URLs fetched / opened:**
  - https://careers.metroag.de/working-at-metro/our-departments
  - https://careers.metroag.de/working-at-metro/development
  - https://careers.metroag.de/jobs/working-student-m-f-d-employer-branding?jid=6fc170c3-f7d2-40ed-9307-bdd55132a66c
  - https://careers.metroag.de/jobs
  - https://karriere.metroag.de/arbeiten-bei-metro/weiterentwicklung
- **Outcome:** Excluded. Official sources surfaced static People & Culture / P&C Academy material and a working-student employer-branding role; the People & Culture trainee listing found via iAgora is a graduate/trainee program and not counted under Signal 4 hard exclusions. No three-posting professional HR/workforce-capability cluster verified in the active review period.
- **Commercial gate score / reason:** Excluded: no verified professional hiring trend; trainee/working-student roles excluded; static P&C Academy material lacks in-period hiring evidence.
- **Cross-signal hint:** Static P&C Academy page may be relevant to S5/S6 background but lacks active-period publication in this lane; Cross-signal: S5?
- **Flags:** RF-FETCH (one METRO careers departments page timed out; development page recovered).

### Momentum Metropolitan

- **Families run:** 1, 2, 3, 5.
- **Queries (full strings):**
  - `"Momentum Metropolitan" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:momentummetropolitan.co.za careers jobs "Momentum Metropolitan" HRIS Talent Learning People Analytics`
  - `"Momentum Metropolitan" hiring talent workforce skills analytics interview blog investor June 2026`
  - `site:momentumgroupltd.erecruit.co "Learning Experience Facilitator" "Momentum"`
  - `site:momentumgroupltd.erecruit.co "Training Solutions Specialist" "Momentum"`
  - `site:momentumgroupltd.erecruit.co/candidateapp/Jobs/View "Role Family | Human Capital" "Closing Date | 2026/06" Momentum`
- **URLs fetched / opened:**
  - https://www.momentumgroupltd.co.za/about-us/careers
  - https://www.momentum.co.za/momentum/about-us/careers
  - https://www.myjobmag.co.za/job/learning-experience-facilitator-momentum-metropolitan-holdings-limited
  - https://www.myjobmag.co.za/job/training-solutions-specialist-momentum-metropolitan-holdings-limited
  - https://momentumgroupltd.erecruit.co/candidateapp/Jobs/Categories/Human_Capital
  - https://momentumgroupltd.erecruit.co/candidateapp/Jobs/View/MMH260604-4
  - https://momentumgroupltd.erecruit.co/candidateapp/Jobs/View/MMH260127-69
  - https://momentumgroupltd.erecruit.co/candidateapp/Jobs/View/MMH260127-36
  - https://momentumgroupltd.erecruit.co/candidateapp/Jobs/View/MMH251128-21
- **Outcome:** Included. Official eRecruit category raw HTML and individual pages verified four current professional Human Capital postings. MyJobMag pages were used only as discovery aids; one MyJobMag Training Solutions Specialist was expired and excluded from count.
- **Commercial gate score / reason:** Included at 22/25; roles cover workforce planning, organizational development, rewards strategy, and talent acquisition.
- **Cross-signal hint:** None.
- **Flags:** RF-FETCH (Momentum Group corporate careers page timed out, but eRecruit official pages recovered evidence).

### Orange Group

- **Families run:** 1, 2, 3, 5, 6.
- **Queries (full strings):**
  - `"Orange Group" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:orange.jobs "Orange" "People Analytics" OR "Talent" OR "Learning" OR "HRIS"`
  - `"Orange Group" hiring talent workforce skills analytics interview blog investor June 2026`
  - `fr "Orange Group" recrutement emplois "people analytics" "talent" "formation" "SIRH"` (ISO 639-1: fr)
  - Orange Jobs Phenom search pages queried by script for keywords `Human Resources`, `talent`, `learning`, `SIRH`, `formation`, and `recrutement`.
- **URLs fetched / opened:**
  - https://www.orange.com/en/careers
  - https://orange.jobs/gb/en
  - https://orange.jobs/gb/en/search-results?keywords=Human%20Resources
  - https://orange.jobs/gb/en/search-results?keywords=learning
  - https://orange.jobs/gb/en/job/ICM-588024/HR-Business-Partner-OINIS
  - https://orange.jobs/gb/en/job/ICM-588192/Learning-Development-L-D-Tools-Technology-Specialist
  - https://orange.jobs/gb/en/job/ICM-585971/Learning-Development-Mgr-Sr
  - https://orange.jobs/gb/en/job/CTS-2026-52456/CDD-Gestionnaire-expert-paie-Groupe-Orange-F-H
  - https://orange.jobs/gb/en/job/ERC-545216-20136094/Strategic-HR-Business-Partner
  - https://newsroom.orange.com/orange-unanimously-signs-an-agreement-on-employment-and-career-path-planning-250463/
- **Outcome:** Excluded. Orange Jobs search HTML showed structured HR/L&D postings with in-window postedDate metadata, but opened individual job pages returned "the job you are trying to apply for has been filled"; therefore live status could not be verified. The GEPP press release is relevant workforce planning context but was published 2025-02-10, outside the review period.
- **Commercial gate score / reason:** Excluded: unable to confirm current live hiring cluster; press release outside period.
- **Cross-signal hint:** GEPP release may fit S3/S5 in a broader historical/context run, but not this period; Cross-signal: S3?, S5?
- **Flags:** RF-FETCH (Orange search-result metadata conflicted with individual filled pages).

### Orange SA

- **Families run:** 1, 2, 3, 5, 6.
- **Queries (full strings):**
  - `"Orange SA" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `fr "Orange SA" recrutement offres "talent management" "formation" "SIRH"` (ISO 639-1: fr)
  - `"Orange SA" "CDD - Gestionnaire expert paie" "Médecin du Travail" "Human Resources" "Orange Jobs"`
  - Orange Jobs Phenom search pages queried by script for keywords `Human Resources`, `formation`, and `recrutement`.
- **URLs fetched / opened:**
  - https://orange.jobs/gb/en/search-results?keywords=Human%20Resources
  - https://orange.jobs/gb/en/job/CTS-2026-52456/CDD-Gestionnaire-expert-paie-Groupe-Orange-F-H
  - https://www.hellowork.com/fr-fr/emplois/79233584.html
- **Outcome:** Excluded. Orange SA-specific hits included payroll expert and occupational health roles, plus alternance/stage items; individual Orange Jobs page for the payroll role returned "filled," and no three-posting professional HR/workforce-capability cluster was verified.
- **Commercial gate score / reason:** Excluded: fewer than three verified professional postings; alternance/stage items excluded.
- **Cross-signal hint:** None.
- **Flags:** RF-FETCH (Orange Jobs page conflict/filled).

### Orange Business

- **Families run:** 1, 2, 3, 5, 6.
- **Queries (full strings):**
  - `"Orange Business" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:orange.jobs "Orange Business" "Human Resources" "Learning" "HR Business Partner" "SIRH"`
  - `"Orange Business" hiring talent workforce skills analytics interview blog investor June 2026`
  - `fr "Orange Business" recrutement offres "formation" "SIRH" "développement RH" "talent"` (ISO 639-1: fr)
  - Orange Jobs Phenom search pages queried by script for keywords `Human Resources`, `learning`, `SIRH`, `formation`, and `recrutement`.
- **URLs fetched / opened:**
  - https://orange.jobs/fr/fr/nos-activites/orange-business
  - https://orange.jobs/gb/en/orange-business/france
  - https://orange.jobs/gb/en/job/ICM-588024/HR-Business-Partner-OINIS
  - https://orange.jobs/gb/en/job/ICM-588192/Learning-Development-L-D-Tools-Technology-Specialist
  - https://orange.jobs/gb/en/job/ICM-585971/Learning-Development-Mgr-Sr
  - https://orange.jobs/gb/en/job/IOS-2026-2453/Charge-e-de-Formation-F-H
  - https://jobs.digital.orange-business.com/
- **Outcome:** Excluded. Search results and Orange Business pages pointed to HR/L&D/SIRH themes, but individual Orange Jobs pages for representative roles returned "filled." Other French-language hits were alternance/stage items, which are excluded under Signal 4.
- **Commercial gate score / reason:** Excluded: no verified live professional cluster after individual-page verification; alternance/stage roles excluded.
- **Cross-signal hint:** Orange Business CPO/upskilling articles from search may fit S1/S5/S3, but not fetched for this lane and not used for Signal 4 inclusion.
- **Flags:** RF-FETCH (Orange Jobs page conflict/filled).

### Oscar Health

- **Families run:** 1, 2, 3, 5.
- **Queries (full strings):**
  - `"Oscar Health" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:hioscar.com careers jobs "Oscar Health" HRIS Talent Learning People Analytics`
  - `"Oscar Health" hiring talent workforce skills analytics interview blog investor June 2026`
  - `"Director, Talent Management" "Oscar" "job-boards.greenhouse.io"`
  - `"Manager, People Strategy Operations" "Oscar" "greenhouse"`
  - `"Program Lead, Talent Management" "Oscar Health" "greenhouse"`
  - `"Oscar Health" "job-boards.greenhouse.io" "People Strategy"`
- **URLs fetched / opened:**
  - https://www.hioscar.com/careers/department/people
  - https://www.hioscar.com/careers/ai-guidelines
  - Greenhouse board API queried by script: `https://boards-api.greenhouse.io/v1/boards/oscar/jobs?content=true`
  - Representative official hioscar/Greenhouse absolute URLs extracted from API: http://www.hioscar.com/careers/7750797?gh_jid=7750797, http://www.hioscar.com/careers/7964056?gh_jid=7964056, http://www.hioscar.com/careers/7975478?gh_jid=7975478, http://www.hioscar.com/careers/7927693?gh_jid=7927693, http://www.hioscar.com/careers/7961317?gh_jid=7961317, http://www.hioscar.com/careers/7961316?gh_jid=7961316, http://www.hioscar.com/careers/7961312?gh_jid=7961312, http://www.hioscar.com/careers/7939940?gh_jid=7939940
- **Outcome:** Included. Official Greenhouse board API verified at least eight live People/Talent/Learning postings; hioscar department page itself fetched with minimal visible content but the official Greenhouse board API exposed job titles, content, and hioscar absolute URLs.
- **Commercial gate score / reason:** Included at 23/25; strong specificity around enterprise talent management, people services, learning, and people strategy.
- **Cross-signal hint:** The AI interview guidelines page may fit S6/HR technology if orchestrator wants candidate-screening AI coverage; Cross-signal: S6?
- **Flags:** RF-FETCH (hioscar department page minimal/script-heavy; Greenhouse API recovered official job data).

### Phoenix Contact

- **Families run:** 1, 2, 3, 5, 6.
- **Queries (full strings):**
  - `"Phoenix Contact" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:phoenixcontact.com careers jobs "Phoenix Contact" HRIS Talent Learning People Analytics`
  - `"Phoenix Contact" hiring talent workforce skills analytics interview blog investor June 2026`
  - `de "Phoenix Contact" Karriere Stellenangebote "People Analytics" "Talent" "Learning" "HRIS"` (ISO 639-1: de)
  - `"Phoenix Contact" "Team Lead HR Data & Analytics" "Compensation Analyst" "Continuous Improvement & Training Specialist"`
  - `site:jobboerse.phoenixcontact.com "Team Lead HR Data" "Phoenix Contact"`
  - `site:jobboerse.phoenixcontact.com "HR Data" "Analytics" "Phoenix Contact"`
  - `site:jobboerse.phoenixcontact.com "Talent" "Learning" "Phoenix Contact" "m/w/d"`
- **URLs fetched / opened:**
  - https://www.phoenixcontact.com/en-us/company/careers
  - https://www.phoenixcontact.com/de-de/karriere
  - Greenhouse board API queried by script: `https://boards-api.greenhouse.io/v1/boards/phoenixcontact/jobs?content=true`
  - https://job-boards.greenhouse.io/phoenixcontact/jobs/7751089003
  - https://builtin.com/job/compensation-analyst/3663083
  - https://talents.vaia.com/companies/phoenix-contact-deutschland-gmbh/team-lead-hr-data-analytics-m-f-d-43776667/
- **Outcome:** Excluded. Official Greenhouse board verified one current workforce-capability-adjacent training role (Continuous Improvement & Training Specialist - OPEX), but it sits in manufacturing OPEX rather than HR/L&D. BuiltIn Compensation Analyst was removed in January 2025; the Team Lead HR Data & Analytics page was third-party and could not be verified on the official Phoenix job board. No three-posting official HR/workforce cluster verified.
- **Commercial gate score / reason:** Excluded: insufficient official volume; third-party HR analytics role not cross-checked against official careers.
- **Cross-signal hint:** None.
- **Flags:** None beyond candidate source limitation.

### Pierre Fabre Laboratories

- **Families run:** 1, 2, 3, 5, 6.
- **Queries (full strings):**
  - `"Pierre Fabre Laboratories" careers jobs hiring "people analytics" OR "talent management" OR "learning" OR "HRIS"`
  - `site:pierre-fabre.com "Responsable SIRH" "Data RH" "Pierre Fabre"`
  - `site:careers.pierre-fabre.com "Responsable SIRH" "Data RH"`
  - `"Pierre Fabre" "Responsable SIRH et Data RH" "Workday" "careers"`
  - `fr "Pierre Fabre Laboratories" recrutement offres "talent" "formation" "SIRH"` (ISO 639-1: fr)
  - `"Pierre Fabre" "HR Business Partner" "Responsable CSP Opérationnel RH" "Responsable SIRH"`
- **URLs fetched / opened:**
  - https://www.pierre-fabre.com/fr/talents/faire-grandir-votre-carriere
  - https://www.pierre-fabre.com/en-us/talents/job-opportunities
  - https://pierrefabre.wd3.myworkdayjobs.com/fr-FR/External_Career_Site/job/Responsable-SIRH-et-Data-RH---CDI---H-F_JR111492
  - Workday CXS endpoint queried by script: `https://pierrefabre.wd3.myworkdayjobs.com/wday/cxs/pierrefabre/External_Career_Site/jobs`
  - Workday CXS detail paths queried by script: `/job/Tarn-81/Responsable-CSP-Oprationnel-RH---CDI---H-F_JR112981-1`, `/job/Australia---North-Sydney/HR-Business-Partner_JR113088`, and `/job/Responsable-SIRH-et-Data-RH---CDI---H-F_JR111492`
- **Outcome:** Excluded. Workday CXS verified two professional HR roles in-window (Responsable CSP Opérationnel RH posted 5 days ago; HR Business Partner posted 3 days ago). The HRIS/Data RH role surfaced in search but returned 403 from CXS detail and was not in the API search result set, so it was not counted. Alternance/stage HR/data hits were excluded.
- **Commercial gate score / reason:** Excluded: only two verified professional HR/workforce postings; below Signal 4 volume threshold.
- **Cross-signal hint:** Official career-development page describes Talent mobility, Myelin e-learning, and Skill Week, but it is static/no active-period publication; Cross-signal: S5?
- **Flags:** RF-FETCH (Workday browser fetch timed out/empty; CXS API partially recovered official postings; HRIS/Data RH detail returned 403).

## Batch summary

- Batch id: S4-B03
- Rows assigned: 11
- Rows with ≥1 Part A′ entry: 4 (Logitech; Mercury Insurance; Momentum Metropolitan; Oscar Health)
- Flags (count by type): RF-FETCH: 9; RF-BLOCKED-ATS: 0; RF-PAYWALL: 0; RF-IDENTITY: 0
- Master §7.2 trade-media sweep: pending on orchestrator; not performed in this signal batch.

