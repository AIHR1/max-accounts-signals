Batch id: S2-B01 | Signal: 2 | Run id: 2026-W37

# Batch lane log — Signal 2 (leadership appointment)

**Run id:** `2026-W37`  
**Signal # (1–6):** `2`  
**Batch id:** `S2-B01`  
**Review period:** 1 September 2026 through 7 September 2026 inclusive  
**Date rule:** Publication date of the announcement (SOP 2 §6); effective date only if that is the sole dated field in an official release and it falls in-window.  
**Account rows in this batch:** ACI Worldwide; Admiral Group Plc; African Development Bank; Almarai - المراعي; AssuredPartners; Bertelsmann, Inc.; Boston Children's Hospital; Capitec bank; Cleaver-Brooks; DHL Ecommerce; DHL Supply Chain; DHL Express; DHL global forwarding; DHL; DOVISTA  

**Note:** Master SOP §7.2 HR / HR-tech trade-media sweep is pending on the orchestrator; this lane did not substitute for it. No user-approved RF-WAIVER. DHL division rows were searched as atomic names (not treated as one parent hit).

---

## Part A′ — Verified entries (this signal × this batch only)

_No qualifying `[leadership-appointment]` entries. Every row completed families 1–4 plus an extended pass (5–7 / §7.1a as required). Candidates that were fetched failed SOP 2 §5 (wrong date, wrong function, LinkedIn-only, not an appointment, junior/local, or vacancy) and/or master §4.1. Cross-signal handoffs are in Part L._

---

## Part L — Execution log

Channels: WebSearch; WebFetch; curl + browser UA; `https://r.jina.ai/http(s)://…` fallback. LinkedIn snippets used only as discovery pointers; no LinkedIn-only appointment was included.

### ACI Worldwide | aciworldwide.com

**Families:** 1, 2, 3, 4, 5, 7 (extended pass)

**Queries (full strings):**
1. `"ACI Worldwide" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:aciworldwide.com (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:aciworldwide.com (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `"ACI Worldwide" appointed OR names OR joins CHRO OR "Chief People" OR "Head of Talent" OR "Chief Learning" OR "CHRO" September 2026`
5. `site:hrtoday.in OR site:hrgrapevine.com OR site:peoplematters.in OR site:humanresourcesonline.net "ACI Worldwide" appointed September 2026`
6. `"ACI Worldwide" "Cranium Ventures" announced September 2026 Nathawat OR talent`
7. `site:aciworldwide.com Cranium Ventures appointment OR leadership OR CHRO OR talent September 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://finance.yahoo.com/technology/articles/aci-worldwide-add-microservices-card-100000651.html (Business Wire 1 Sep 2026; WebFetch) | Excluded: in-window M&A. Co-founders Ashraf Dimitri and Tony Horrell will join ACI as technology leaders, not L&D / talent / OD / HR-transformation / CHRO. | Excluded: strategy/M&A, no people-function appointment. |  |
| https://www.businesswire.com/news/home/20260901440353/en/ | Excluded: HTTP 500 on direct fetch; Yahoo reprint of same wire used for verification. | Same fact as Yahoo. | RF-FETCH |
| https://www.linkedin.com/posts/praveena-nathawat-a385265_aci-worldwide-to-add-microservices-card-switching-activity-7500559220015149058-udsg (2026-09-01) | Excluded for S2: not an appointment. CHRO Praveena Nathawat attributes the acquisition’s value to “the talent joining ACI.” | Not scored as S2. **Cross-signal: S1** (CHRO-tier in-window people commentary — 7.1b). |  |
| https://investor.aciworldwide.com/news-releases/news-release-details/aci-worldwide-appoints-praveena-nathawat-chief-human-resources | Excluded: CHRO appointment dated 28 May 2024. Direct WebFetch timed out; date/title confirmed from search-index body. | Excluded before scoring: wrong date. | RF-FETCH |
| https://investor.aciworldwide.com/management/praveena-nathawat | Excluded: static bio, CHRO since 2024. WebFetch timed out; search snippet confirms incumbent. | Excluded: no in-window appointment. | RF-FETCH |
| https://investor.aciworldwide.com/corporate-governance/executive-leadership-team | Excluded: directory listing Nathawat as CHRO; JP Krishnamoorthy CITO appointment is 13–14 Jan 2026 technology, not this signal. | Excluded: static org chart / wrong function. |  |

**Row conclusion:** families 1–4 + extended 5/7; no S2 hit.

---

### Admiral Group Plc | admiralgroup.co.uk

**Families:** 1, 2, 3, 4, 5, 7 (extended pass)

**Queries (full strings):**
1. `"Admiral Group Plc" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:admiralgroup.co.uk (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:admiralgroup.co.uk (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `"Admiral Group" appointed OR names OR joins CHRO OR "Chief People Officer" OR "Head of Talent" OR "HR transformation" September 2026`
5. `site:hrtoday.in OR site:hrgrapevine.com OR site:peoplematters.in OR site:humanresourcesonline.net "Admiral Group" appointed September 2026`
6. `"Admiral Group" OR "Admiral Group Plc" people talent learning appointment 2026 "Zareena Brown"`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://www.admiralgroup.co.uk/management/zareena-brown (WebFetch) | Excluded: page states Zareena Brown “was appointed Group Chief People Officer in September 2025.” | Excluded: wrong year. |  |
| https://admiralgroup.co.uk/news-releases/news-release-details/geraint-jones-retire-group-cfo-rachel-lewis-assuming-role-july | Excluded: Group CFO succession (Rachel Lewis from 1 Jul 2026), not people/L&D. | Excluded: wrong function. |  |
| https://www.linkedin.com/posts/jo-franco-wheeler-4ba1b1b_insurance-lifeatadmiral-futureofwork-activity-7491058889237549056-bwsk (2026-08-06) | Excluded: LinkedIn-only first-week post as Head of Organisational Effectiveness; publication 6 Aug 2026, outside window; no company/press corroboration. | Excluded: LinkedIn-only + wrong date. OD remit would otherwise be §5-adjacent. |  |

**Row conclusion:** families 1–4 + extended 5/7; no S2 hit.

---

### African Development Bank | afdb.org

**Families:** 1, 2, 3, 4, 5, 6, 7 (extended pass; §7.1a `fr`)

**Queries (full strings):**
1. `"African Development Bank" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:afdb.org (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:afdb.org (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `"African Development Bank" appointed OR names OR joins CHRO OR "Chief People" OR "Director Human Resources" September 2026`
5. `fr: "Banque africaine de développement" (nomination OR nommé OR nommée OR rejoint OR "prend la fonction") (talent OR "ressources humaines" OR apprentissage OR DRH OR "transformation RH") septembre 2026`
6. `"African Development Bank Group" "People and Talent Management" appointment 2026 September Jacques Edjangue`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://www.afdb.org/en/news-and-events/african-development-bank-appoints-jessica-kitakule-mukungu-acting-director-talent-performance-management-and-staff-development-department-52943 | Excluded: Cloudflare challenge on WebFetch; search body is a historic acting-director talent appointment (undated in fetch; previously known as 2020s, not this week). | Excluded: not verified in-window. | RF-FETCH |
| https://www.afdb.org/sites/default/files/2025/09/23/approved_new_bank_structure_as_of_01_september_2025.3.pdf | Excluded: org chart “Updated: 01 September **2025**”; VP People & Talent still J. EDJANGUE; PTCE J. KITAKULE-MUKUNGU; PTCE.2 R. A. VENEAU. | Excluded: wrong year / static structure. |  |
| https://www.afdb.org/en/corporate-procurement/provision-human-resources-services-recruitment-short-term-staff-regional-directorate-general-south-rdgs-91464 | Excluded: 6 Mar 2026 procurement for short-term staff agency, not a senior L&D/talent appointment. | Excluded: vendor RFP. |  |

**§7.1a:** `fr` — `"Banque africaine de développement" (nomination OR nommé OR nommée OR rejoint OR "prend la fonction") (talent OR "ressources humaines" OR apprentissage OR DRH OR "transformation RH") septembre 2026` — French hits were LinkedIn staff-profile noise and Africa Re board bios, not AfDB people-leadership nominations.

**Row conclusion:** families 1–4 + extended 5–7; no S2 hit.

---

### Almarai - المراعي | almarai.com

**Families:** 1, 2, 3, 4, 5, 6, 7 (extended pass; §7.1a `ar`)

**Queries (full strings):**
1. `"Almarai - المراعي" OR "Almarai" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:almarai.com (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:almarai.com (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `Almarai OR المراعي appointed OR names CHRO OR "Chief People" OR "Head of Talent" OR "HR" September 2026`
5. `ar: "المراعي" (تعيين OR عُين OR ينضم OR "منصب جديد") ("الموارد البشرية" OR المواهب OR التعلم OR "التطوير التنظيمي") سبتمبر 2026`
6. `"Almarai Company" OR "Almarai" "Head of Talent" OR "Chief Human Resources Officer" appointment 2026 Ayman Algeer`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://annualreport.almarai.com/governance/executive-management/ (WebFetch) | Excluded: Ayman Algeer listed as CHRO; joined 2021 as Head of HR CoE, CHRO in 2024. No 1–7 Sep 2026 appointment. | Excluded: static 2025 annual-report bios. |  |
| https://www.almarai.com/en/corporate/investor-relations/corporate-governance | Excluded: WebFetch returned JS shell (“null 2026”); search snippet still lists Algeer as current CHRO (appointed 2024). | Excluded: no in-window appointment. | RF-FETCH |
| https://www.almarai.com/en/corporate/media-center/almarai-news/almarai-55-graduates-leadership | Excluded: CHRO present at leadership-program graduation; Marketscreener/WN date **8 May 2026**, outside window; not an appointment. | Excluded: wrong date. If later verified in another period, **Cross-signal: S1 / S5?** for CHRO/CEO talent-development quotes. |  |
| https://jobzsa.net/8999 | Excluded: 7 Sep 2026 aggregator of 35 generic Almarai vacancies (admin/engineering/sales), not a senior people-leader appointment. | Excluded: generic hiring; not a 3+ HR/L&D cluster. |  |

**§7.1a:** `ar` — `"المراعي" (تعيين OR عُين OR ينضم OR "منصب جديد") ("الموارد البشرية" OR المواهب OR التعلم OR "التطوير التنظيمي") سبتمبر 2026` — returned job ads and older training-award coverage, not a dated CHRO/talent-head nomination.

**Row conclusion:** families 1–4 + extended 5–7; no S2 hit.

---

### AssuredPartners | assuredpartners.com

**Families:** 1, 2, 3, 4, 5 (extended pass)

**Queries (full strings):**
1. `"AssuredPartners" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:assuredpartners.com (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:assuredpartners.com (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `AssuredPartners appointed OR names OR joins CHRO OR "Chief People" OR "Head of Talent" OR "HR transformation" September 2026`
5. `"AssuredPartners" "Chief Human Resources Officer" "Head of Talent" appointment 2026 Andrea Brogger`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://www.prweb.com/releases/assuredpartners-announces-chief-human-resources-officer-816975420.html | Excluded: Andrea Brogger CHRO effective 26 Jun 2023. | Excluded: wrong date. |  |
| https://assuredpartners.co.uk/news/ | Excluded: Gallagher close 18 Aug 2025 and other M&A; no people-function appointment in window. | Excluded: strategy/M&A. |  |
| https://www.assuredpartners.com/blogs/ap-in-the-news/2023/assuredpartners-announces-milestone-200th-acquisition/ | Excluded: domain now serves Gallagher insight feed; no Sept 2026 CHRO/talent appointment. | Excluded: no candidate. |  |

**Row conclusion:** families 1–4 + extended 5; no S2 hit.

---

### Bertelsmann, Inc. | bertelsmann.com

**Families:** 1, 2, 3, 4, 5, 6, 7 (extended pass; §7.1a `de`)

**Queries (full strings):**
1. `"Bertelsmann, Inc." OR "Bertelsmann" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:bertelsmann.com (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:bertelsmann.com (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `Bertelsmann appointed OR ernannt CHRO OR "Chief People" OR "Head of Talent" OR Personalvorstand OR "HR transformation" September 2026`
5. `de: Bertelsmann (ernannt OR übernimmt OR Leitung OR Berufung) (Personalvorstand OR Talent OR Personalentwicklung OR HR-Transformation) September 2026`
6. `"Steven Moran" Bertelsmann "Chief Learning Officer" appointed OR named 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://www.bertelsmann.com/en/media/news/clement-schwebig-new-ceo-of-rtl-group-alexander-von-torklus-to-become-cfo.html (WebFetch; dated 13 May 2026) | Excluded: RTL CEO/CFO succession; von Torklus “by the end of September 2026” is **CFO**, not people/L&D. Publication May 2026. | Excluded: wrong function + publication outside window. |  |
| https://www.bertelsmann.com/en/news-and-media/news/bertelsmann-appoints-steven-moran-to-group-management-committee.jsp | Excluded: CLO Moran additionally named Chief Partnership Officer / GMC **effective 1 Jan 2025**. | Excluded: wrong date. |  |
| https://www.bertelsmann.com/en/company/management/steven-moran.html | Excluded: static CLO + CPO bio; not a new in-window appointment. | Excluded: directory page. |  |
| https://gb2025.bertelsmann.de/unternehmen/management | Excluded: Hermreck still Personalvorstand; Moran still CLO. | Excluded: static management page. |  |
| https://www.nw.de/nachrichten/wirtschaft/24405642_Guetersloher-Unternehmen-Bertelsmann-steigert-Gewinn-aktuell-mehr-als-200-offene-Stellen.html (WebFetch; **30 Aug 2026**) | Excluded for S2: not an appointment. CHRO Immanuel Hermreck quoted on stable headcount (~10,000 regionally), 225 open roles, more apprentices. Publication 30 Aug 2026, **outside** 1–7 Sep window. | Excluded: wrong date for this run. CHRO workforce comments would be **Cross-signal: S1** if an orchestrator later opens an Aug window. |  |
| https://www.visier.com/blog/bertelsmann-group-hr-transformation-people-analytics/ | Excluded: vendor case study; Kai Wehmeyer SVP Corporate HR Strategy & Systems; no dated Sept 2026 appointment. | Excluded: undated/vendor. **Cross-signal: S6?** if customer-corroborated HR-tech go-live can be dated. |  |

**§7.1a:** `de` — `Bertelsmann (ernannt OR übernimmt OR Leitung OR Berufung) (Personalvorstand OR Talent OR Personalentwicklung OR HR-Transformation) September 2026` — surfaced Hermreck H1 comments (Aug) and CEO succession to Jan 2027, not an HR appointment this week.

**Row conclusion:** families 1–4 + extended 5–7; no S2 hit.

---

### Boston Children's Hospital | childrenshospital.org

**Families:** 1, 2, 3, 4, 5 (extended pass)

**Queries (full strings):**
1. `"Boston Children's Hospital" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:childrenshospital.org (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:childrenshospital.org (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `"Boston Children's Hospital" appointed CHRO OR "Chief People" OR "Head of Talent" OR "Chief Learning" OR "HR transformation" September 2026`
5. `"Boston Children's Hospital" "Chief Human Resources Officer" "Head of Talent" appointment 2026 "Lisa Abbott"`
6. `"140 hospital and health system CHROs" Becker's 2026 published date September`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| http://childrenshospital.org/about-us/our-leadership/lisa-abbott | Excluded: Incapsula block on WebFetch. Search body: Lisa Abbott EVP/CHRO since **2023**. | Excluded: incumbent bio. | RF-FETCH |
| https://www.beckershospitalreview.com/hospital-management-administration/140-hospital-and-health-system-chros-and-chief-people-officers-to-know-2026/ (fetched; LinkedIn corroboration Mar 2026) | Excluded for S2: recognition list, not an appointment. Abbott text discusses a leadership capability model and technology-transformation workforce alignment. Scott Doak LinkedIn dates the list **Mar 2026**; St. Tammany post 11 Aug 2026 — neither is 1–7 Sep. | Excluded: wrong date / not appointment. **Cross-signal: S1?** only if orchestrator independently dates a VP+/CHRO quote inside this week (not established here). |  |
| https://www.linkedin.com/posts/maryanneamato_im-excited-to-be-starting-my-next-adventure-activity-7488177751670071296-0XOb (2026-07-29) | Excluded: LinkedIn-only Sr. Director Leadership & Talent Development start; July 2026; director-level. | Excluded: LinkedIn-only, wrong date, below typical §5 senior bar without company announcement. |  |
| https://bcrp.childrenshospital.org/people/program-directors/ | Excluded: pediatric residency program-director transition in Sep 2026 (clinical education), not enterprise people/L&D. | Excluded: wrong function. |  |

**Row conclusion:** families 1–4 + extended 5; no S2 hit.

---

### Capitec bank | capitecbank.co.za

**Families:** 1, 2, 3, 4, 5, 6, 7 (extended pass; §7.1a `af`)

**Queries (full strings):**
1. `"Capitec bank" OR "Capitec Bank" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:capitecbank.co.za (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:capitecbank.co.za (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `"Capitec" appointed OR names CHRO OR "Chief People" OR "Head of Talent" OR "Head of Learning" September 2026`
5. `af: "Capitec" (aangestel OR benoem OR "nuwe rol") ("menslike hulpbronne" OR talentbestuur OR "Hoof van Leer" OR CHRO) September 2026`
6. `"Capitec" OR "Capitec Bank Ltd" "Head of Learning" "appointed" OR "new role" 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://www.capitecbank.co.za/globalassets/pages/investor-relations/financial-results/2026/annual-report/integrated_annual_report_2026.pdf | Excluded: FY26 IAR notes Deepesh Desai Executive: Insurance (9 Apr 2026), Andy Baker Executive: Technology and Data / Wim de Bruyn Executive: Transact (1 Mar 2026); no new Group Executive: HR. Rizwana Butler remains HR officer (MarketScreener: 28 Feb 2021). | Excluded: other-function exec moves, wrong dates. |  |
| https://www.linkedin.com/posts/capitec-bank_for-womens-month-were-sitting-down-with-activity-7495068016808914944-blZN (2026-08-17) | Excluded for S2: interview, not appointment. Butler + Suzanne Liebenberg on capability, learning, internal mobility. Dated 17 Aug 2026. | Excluded: wrong date. Would be **Cross-signal: S1** in an August window. |  |
| https://chro.co.za/articles/capitec-group-hr-executive-rizwana-butler-champions-people-through-technology/ | Excluded: 28 Jul **2025** interview on AI-enabled org / SuccessFactors. | Excluded: wrong date. |  |
| https://careers.capitecbank.co.za/job/Strategic-People-Partner-Stellenbosch/1383194933/ (WebFetch) | Excluded: vacancy dated **7 Aug 2026**, page now “Sorry, this position has been filled.” Not a public senior appointment. | Excluded: single job posting (master §4.1). ATS HTML returned the filled-state message (not a live script-only board). |  |
| https://okjobs.co.za/people-partner_stellenbosch-c452920/2026-09-capitec-bank-ltd_i4194196792 | Excluded: aggregator reprint of Strategic People Partner role, published 4 Sep 2026 as a **vacancy**. | Excluded: single posting, not appointment. |  |

**§7.1a:** `af` — `"Capitec" (aangestel OR benoem OR "nuwe rol") ("menslike hulpbronne" OR talentbestuur OR "Hoof van Leer" OR CHRO) September 2026` — no Afrikaans nomination wire; English job-board and incumbent-profile noise only.

**Row conclusion:** families 1–4 + extended 5–7; no S2 hit.

---

### Cleaver-Brooks | cleaverbrooks.com

**Families:** 1, 2, 3, 4, 5 (extended pass)

**Queries (full strings):**
1. `"Cleaver-Brooks" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:cleaverbrooks.com (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:cleaverbrooks.com (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `"Cleaver-Brooks" appointed OR names CHRO OR "Vice President Human Resources" OR "Head of Talent" September 2026`
5. `"Cleaver-Brooks" "Vice President Human Resources" "Corporate Talent Team Lead" appointment 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://cleaverbrooks.com/about-us/get-to-know-us/executive-leadership-team/vpofhumanresources (WebFetch) | Excluded: Dennis Hettinger VP HR since 2020 (joined 2006; Corporate Director 2009). Undated page, no “new”/effective 1–7 Sep 2026 language. | Excluded: static leadership page. |  |
| https://cleaverbrooks.com/about-us/get-to-know-us/executive-leadership-team | Excluded: same ELT roster. | Excluded: directory. |  |

**Row conclusion:** families 1–4 + extended 5; no S2 hit.

---

### DHL Ecommerce | dhlecommerce.com

**Families:** 1, 2, 3, 4, 5, 6, 7 (extended pass; §7.1a `de`; atomic row)

**Queries (full strings):**
1. `"DHL Ecommerce" OR "DHL eCommerce" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:dhlecommerce.com OR site:dhl.com/ecommerce (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:dhlecommerce.com OR site:dhl.com/ecommerce (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `"DHL Ecommerce" OR "DHL eCommerce" appointed OR names CHRO OR "Head of Talent" OR "Chief People" OR "HR transformation" September 2026`
5. `de: "DHL eCommerce" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) September 2026`
6. `"DHL Express" OR "DHL eCommerce" (ernannt OR übernimmt OR "neue Leitung") Personal OR Talent OR Weiterbildung September 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://group.dhl.com/en/media-relations/press-releases/2026/dhl-ecommerce-trends-report-2026-old-rules-do-not-apply-in-the-age-of-ai.html | Excluded: 2 Jun 2026 trends report; CEO Pablo Ciano quote; not an HR appointment. | Excluded: wrong date / wrong function. |  |
| https://www.northdata.com/DHL%20eCommerce%20Holding%20GmbH,%20Bonn/HRB%2028541 | Excluded: 14 Jul 2026 German register: Fiona Dalley managing director; Florian Bumberger no longer MD. Not an HR/talent appointment in this window. | Excluded: wrong date / corporate-register MD change. |  |

Search also showed Florian Bumberger still described as divisional CHRO on LinkedIn (not a new Sept appointment) and Juliana S. VP Global Talent Management & People Experience since Jan 2022.

**§7.1a:** `de` — `"DHL eCommerce" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) September 2026`

**Row conclusion:** families 1–4 + extended 5–7; no S2 hit.

---

### DHL Supply Chain | dhl.com

**Families:** 1, 2, 3, 4, 5, 6, 7 (extended pass; §7.1a `de`; atomic row)

**Queries (full strings):**
1. `"DHL Supply Chain" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:dhl.com "DHL Supply Chain" (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:dhl.com "DHL Supply Chain" (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `"DHL Supply Chain" appointed OR names CHRO OR "Head of Talent" OR "Chief People" OR "Head of Learning" OR "HR transformation" September 2026`
5. `de: "DHL Supply Chain" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) September 2026`
6. `"DHL Supply Chain" OR "DHL Global Forwarding" OR "Deutsche Post DHL" (ernannt OR übernimmt OR Berufung) (Personalvorstand OR Talentmanagement OR Weiterbildung OR CHRO) September 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://www.dhl.com/pl-en/home/press/press-archive/2026/dhl-supply-chain-appoints-bernard-wierzbik-as-managing-director-for-poland-reinforcing-strategic-growth-in-the-cee-region.html | Excluded: WebFetch timed out. Search/mirrors: Warsaw **25 Mar 2026**, Bernard Wierzbik **Managing Director Poland** (operations), not HR/talent. | Excluded: wrong date + wrong function. | RF-FETCH |
| https://europaproperty.com/hr-marketplace/dhl-supply-chain-appoints-managing-director-for-poland/ | Excluded: 25 Mar 2026 reprint of same MD appointment. | Same. |  |
| https://www.dhl.com/us-en/home/press/press-archive/2026/dhl-supply-chain-announces-leadership-appointments-to-advance-strategy-2x30.html | Excluded: **21 May 2026** commercial/ops appointments (Monkmeyer, Ruff, Moss), not people function. | Excluded: wrong date + wrong function. Mentions “bench of talent” as rhetoric only. |  |
| https://group.dhl.com/en/media-relations/press-releases/2025/dhl-supply-chain-announces-key-executive-appointments-and-strengthening-of-customer-focused-strategy.html | Excluded: **1 Sep 2025** customer/commercial C-suite, not this week. | Excluded: wrong year. |  |

LinkedIn-only (not fetched as primary, logged as discovery): Daniela Kerkhoff-Guenther SVP HR DSC Europe from **Jun 2026**; Michele Toscano Head of TA/L&D Feb 2026; Kate F. Head of Talent and Development May 2026 — all outside window and/or uncorroborated.

**§7.1a:** `de` — `"DHL Supply Chain" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) September 2026`

**Row conclusion:** families 1–4 + extended 5–7; no S2 hit.

---

### DHL Express | express-resource.dhl.com

**Families:** 1, 2, 3, 4, 5, 6 (extended pass; §7.1a `de`; atomic row)

**Queries (full strings):**
1. `"DHL Express" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "SVP HR" OR "HR transformation") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:express-resource.dhl.com OR site:dhl.com "DHL Express" (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "SVP Human Resources") September 2026`
3. `site:dhl.com "DHL Express" (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "SVP Human Resources") 2026`
4. `"DHL Express" appointed OR names CHRO OR "Head of Talent" OR "SVP Human Resources" OR "Chief People" September 2026`
5. `de: "DHL Express" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR Personalvorstand) September 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://www.dhl.com/in-en/home/press/press-archive/2025/dhl-express-enhances-asia-pacific-leadership-team-with-strategic-appointments-in-hr-and-taiwan.html | Excluded: WebFetch timeout. Search body: Singapore **18 Dec 2025**; Chee Choong Ng SVP HR APAC **effective 1 Jan 2026**. | Excluded: wrong date. | RF-FETCH |
| https://www.humanresourcesonline.net/up-the-ranks-dhl-express-appoints-new-svp-hr-for-apac-and-managing-director-for-taiwan | Excluded: published **6 Jan 2026**; same Ng appointment. | Excluded: wrong date. |  |
| https://www.peoplematters.in/news/appointments/dhl-express-appoints-saurabh-dalvi-as-head-of-hr-for-it-services-india-48579 | Excluded: **26 Feb 2026** (company confirmed Jan 2026); Head of HR, IT Services **India** — local/functional, outside window. | Excluded: wrong date / not enterprise §5. |  |
| https://www.linkedin.com/posts/dhlexpressindia_dhl-express-hr-global-metrics-engagement-activity-7447240811207036928-wHTO | Excluded for S2: EVP Global HR Fadzlun Sapandi Economic Times interview on HR metrics/engagement — **not an appointment**; LinkedIn activity id consistent with ~Mar/Apr 2026, not 1–7 Sep. | Excluded: not appointment + wrong date. **Cross-signal: S1** if S1 lane independently dates the ET piece in-window (not established here). |  |

**§7.1a:** `de` — `"DHL Express" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR Personalvorstand) September 2026`

**Row conclusion:** families 1–4 + extended 5–6; no S2 hit.

---

### DHL global forwarding | dhl.com

**Families:** 1, 2, 3, 4, 5, 6, 7 (extended pass; §7.1a `de`; atomic row)

**Queries (full strings):**
1. `"DHL global forwarding" OR "DHL Global Forwarding" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "Head Talent" OR "HR transformation") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:dhl.com "DHL Global Forwarding" (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "Head Talent" OR "HR transformation") September 2026`
3. `de: "DHL Global Forwarding" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) September 2026`
4. `"DHL Global Forwarding" appointed OR names "Head of Talent" OR CHRO OR "Chief People" OR "HR transformation" September 2026`
5. `site:hrtoday.in "DHL Global Forwarding" appointed September 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://hrtoday.in/mohit-rai-takes-on-global-head-of-global-service-centers-role-at-dhl-global-forwarding/ (WebFetch) | Excluded: schema `datePublished` **2026-08-15**; Global Head of **GSC** (operations/shared services), not L&D/talent/HR transformation. | Excluded: wrong date + wrong function. |  |
| https://hrtoday.in/lindsy-foran-appointed-as-head-of-human-resources-canada-at-dhl-global-forwarding/ | Excluded: **January 2026**, country Head of HR Canada. | Excluded: wrong date / local HR. |  |
| https://hrtoday.in/daniela-kerkhoff-guenther-joins-as-vice-president-certified-talent-management-talent-acquisition-at-dhl-global-forwarding-dhl-freight/ | Excluded: **September 2025** (prior year). | Excluded: wrong year. |  |
| https://hrtoday.in/suparna-chatterjee-appointed-as-head-hr-gsc-bom-at-dhl-global-forwarding/ | Excluded: **May 2026**, Head HR GSC Mumbai — site HR, outside window. | Excluded: wrong date / local. |  |

Isabel Rudolph remains Head of Global Talent Management & Talent Acquisition (LinkedIn since May 2022) — no in-window company announcement.

**§7.1a:** `de` — `"DHL Global Forwarding" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) September 2026`

**Row conclusion:** families 1–4 + extended 5–7; no S2 hit.

---

### DHL | dhl.com

**Families:** 1, 2, 3, 4, 5, 6, 7 (extended pass; §7.1a `de`; atomic parent row)

**Queries (full strings):**
1. `"DHL" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "Head Talent" OR "HR transformation") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:dhl.com (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "Head Talent" OR "HR transformation") September 2026`
3. `site:dhl.com (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "SVP Human Resources") 2026`
4. `"DHL" OR "Deutsche Post" appointed CHRO OR "Chief People Officer" OR "Head of Talent" OR Personalvorstand September 2026`
5. `de: "DHL" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR Personalvorstand) September 2026`
6. `"How DHL Group is raising an AI-powered workforce" Ogilvie People Matters published date 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://group.dhl.com/en/about-us/corporate-governance/board-of-management.html | Direct WebFetch timed out; **jina.ai fallback succeeded**. Dr. Thomas Ogilvie still listed **Human Resources**, appointed until Aug 2030. No new board HR appointment this week. | Excluded: static board page. | RF-FETCH (direct); fallback OK |
| https://sea.peoplemattersglobal.com/article/strategic-hr/how-dhl-is-raising-an-ai-powered-workforce-an-exclusive-interview-with-global-chro-dr-thomas-ogilvie-39603 | Excluded: interview dated **30 November 2023**. | Excluded: wrong date. Not an appointment. |  |
| https://www.dhl.com/au-en/home/press/press-archive/2025/dhl-group-recognised-as-a-great-place-to-work-in-australia.html | Excluded: **4 Sep 2025** GPTW; Ogilvie employer-brand quote. | Excluded: wrong year; employer branding. |  |
| https://www.personalwirtschaft.de/news/allgemein/thomas-ogilvie-wird-neuer-personalvorstand-104191/ | Excluded: original Personalvorstand appointment (effective 1 Sep **2017**). | Excluded: historic. |  |
| https://fortune.com/2024/10/30/dhl-chro-upskilling-internal-mobility-retention/ | Excluded: 30 Oct 2024 Career Marketplace / CHRO quotes. | Excluded: wrong date. **Cross-signal: S1 / S6?** historically, not this window. |  |

Anne Walther LinkedIn “EVP HR Group Functions” from Apr 2026 is LinkedIn-only and outside this week — logged as discovery only (SOP: no LinkedIn-only moves).

**§7.1a:** `de` — `"DHL" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR Personalvorstand) September 2026`

**Row conclusion:** families 1–4 + extended 5–7; no separate parent-row S2 hit (division hits above also failed date/scope).

---

### DOVISTA | dovista.com

**Families:** 1, 2, 3, 4, 5, 6, 7 (extended pass; §7.1a `da`)

**Queries (full strings):**
1. `"DOVISTA" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "organizational development") (appointed OR joins OR hire OR named OR "new role") September 2026`
2. `site:dovista.com (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") September 2026`
3. `site:dovista.com (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`
4. `DOVISTA appointed OR names CHRO OR "Chief People" OR "Head of Talent" OR "Head of HR" September 2026`
5. `da: "DOVISTA" (udnævnt OR tiltræder OR ansat OR "ny rolle" OR leder) (talent OR læring OR HR-transformation OR organisationsudvikling OR CHRO OR "People & Culture") september 2026`
6. `"DOVISTA" "Head of HR" OR "Chief People" OR talent appointment 2026`

| URLs fetched | Outcome | Commercial gate / Cross-signal | Flags |
| ------------ | ------- | ------------------------------ | ----- |
| https://dovista.com/management/ (WebFetch) | Excluded: Annette Palmelund-Jahn listed as CHRO among current Group Management; no dated “appointed/new” language for 1–7 Sep 2026. | Excluded: static management page (LinkedIn shows CHRO since May 2023). |  |
| https://dovista.com/press/ | Excluded: press kit / circular-product collaboration; no people appointment. | Excluded: not §5. |  |
| https://dovista.com/wp-content/uploads/2025/02/Pressemeddelelse-27.02.25.pdf | Excluded: 27 Feb 2025 4B acquisition, not HR. | Excluded: wrong date / M&A. |  |

**§7.1a:** `da` — `"DOVISTA" (udnævnt OR tiltræder OR ansat OR "ny rolle" OR leder) (talent OR læring OR HR-transformation OR organisationsudvikling OR CHRO OR "People & Culture") september 2026`

**Row conclusion:** families 1–4 + extended 5–7; no S2 hit.

---

**§7.1a local-language log (ISO 639-1 + full query string):**

| ISO | Account row | Full query string |
| --- | ----------- | ----------------- |
| `fr` | African Development Bank | `"Banque africaine de développement" (nomination OR nommé OR nommée OR rejoint OR "prend la fonction") (talent OR "ressources humaines" OR apprentissage OR DRH OR "transformation RH") septembre 2026` |
| `ar` | Almarai - المراعي | `"المراعي" (تعيين OR عُين OR ينضم OR "منصب جديد") ("الموارد البشرية" OR المواهب OR التعلم OR "التطوير التنظيمي") سبتمبر 2026` |
| `de` | Bertelsmann, Inc. | `Bertelsmann (ernannt OR übernimmt OR Leitung OR Berufung) (Personalvorstand OR Talent OR Personalentwicklung OR HR-Transformation) September 2026` |
| `de` | DHL Ecommerce | `"DHL eCommerce" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) September 2026` |
| `de` | DHL Supply Chain | `"DHL Supply Chain" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) September 2026` |
| `de` | DHL Express | `"DHL Express" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR Personalvorstand) September 2026` |
| `de` | DHL global forwarding | `"DHL Global Forwarding" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) September 2026` |
| `de` | DHL | `"DHL" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR Personalvorstand) September 2026` |
| `da` | DOVISTA | `"DOVISTA" (udnævnt OR tiltræder OR ansat OR "ny rolle" OR leder) (talent OR læring OR HR-transformation OR organisationsudvikling OR CHRO OR "People & Culture") september 2026` |
| `af` | Capitec bank | `"Capitec" (aangestel OR benoem OR "nuwe rol") ("menslike hulpbronne" OR talentbestuur OR "Hoof van Leer" OR CHRO) September 2026` |

---

## Batch summary

- **Batch id:** S2-B01
- **Rows assigned:** 15
- **Rows with ≥1 Part A′ entry:** 0
- **CHECKPOINT:** none — all 15 rows completed families 1–4 plus extended 5–7 / §7.1a as required
- **Flags (count by type):**
  - RF-FETCH: 8 URL/channel failures (ACI 2024 CHRO PR timeout; ACI Nathawat bio timeout; ACI BusinessWire 500; Almarai IR JS-empty; BCH Lisa Abbott Incapsula; AfDB Cloudflare; DHL Express India PR timeout; DHL SC Poland PR timeout; DHL Board direct timeout with jina success)
  - RF-PAYWALL: 0 (nw.de Hermreck piece returned full text)
  - RF-BLOCKED-ATS: 0 (Capitec careers returned a filled-state HTML page)
  - RF-IDENTITY: 0
  - RF-WAIVER: 0
- **Cross-signal hints harvested:**
  - **S1 (mandatory pattern):** ACI Worldwide — https://www.linkedin.com/posts/praveena-nathawat-a385265_aci-worldwide-to-add-microservices-card-switching-activity-7500559220015149058-udsg — CHRO Praveena Nathawat, 1 Sep 2026, talent-joining commentary on Cranium Ventures (not an appointment — 7.1b)
  - **S1 (out of this window, for orchestrator awareness only):** Capitec Women’s Month interview 17 Aug 2026; Bertelsmann Hermreck H1 workforce comments 30 Aug 2026; BCH Becker’s CHRO list (Mar 2026) with Abbott capability-model language
  - **S6?:** Visier Bertelsmann people-analytics case (undated; vendor)
- **Master §7.2** trade-media sweep: pending orchestrator
