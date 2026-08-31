Batch id: S2-B01 | Signal: 2 | Run id: 2026-W36

# Batch lane log — Signal 2 (leadership appointment)

**Run id:** `2026-W36`  
**Signal # (1–6):** `2`  
**Batch id:** `S2-B01`  
**Review period:** 25 August 2026 through 31 August 2026 inclusive  
**Date rule:** Publication date of the announcement, or the effective date if that is the only dated field in the official release and it falls in-window.  
**Account rows in this batch:** ACI Worldwide; Admiral Group Plc; African Development Bank; Almarai - المراعي; AssuredPartners; Bertelsmann, Inc.; Boston Children's Hospital; Capitec bank; Cleaver-Brooks; DHL Ecommerce; DHL Supply Chain; DHL Express; DHL global forwarding; DHL; DOVISTA  

**Note:** Master SOP §7.2 HR / HR-tech trade-media sweep is pending on the orchestrator; this lane did not substitute for it. DHL* rows were searched as **atomic** division names (no shared-query substitution). No RF-WAIVER.

---

## Part A′ — Verified entries (this signal × this batch only)

No qualifying `[leadership-appointment]` entry passed Signal 2 §8.1 verification and the master §4.1 commercial gate for this batch. Near-misses were incumbent bios, appointments first disclosed before 25 August 2026, LinkedIn-only moves without company/press corroboration, non-HR operational appointments, or CHRO-tier commentary that is not an appointment.

---

## Part L — Execution log

### ACI Worldwide

- **Families:** 1, 2, 3, 4, 5. Extended pass.
- **Queries run:** `"ACI Worldwide" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "HR transformation" OR "Chief Human Resources Officer" OR "Chief People Officer") (appointed OR joins OR named OR "new role") August 2026`; `site:aciworldwide.com (appointed OR appointment OR joins OR named) (CHRO OR "Chief People" OR talent OR learning OR "HR transformation") 2026`; `site:aciworldwide.com (news OR press OR leadership) ("Head of Talent" OR CHRO OR "Chief Learning Officer" OR "organizational development") August 2026`; `"ACI Worldwide" (appointed OR names OR joins) (CHRO OR CPO OR "Head of Talent" OR "Chief Learning" OR "People Officer") 2026 -2024`.
- **URLs fetched/opened:** `https://investor.aciworldwide.com/news-releases/news-release-details/aci-worldwide-appoints-praveena-nathawat-chief-human-resources` (search snippet: **28 May 2024** CHRO appointment of Praveena Nathawat; curl HTTP/1.1 with browser UA returned **Access Denied** / Akamai); `https://investor.aciworldwide.com/management/praveena-nathawat` (incumbent CHRO bio, with ACI since 2024); `https://investor.aciworldwide.com/corporate-governance/executive-leadership-team` (CHRO listed; WebFetch timeout); `https://events.aciworldwide.com/paymentsunleashed/speaker/1827710/praveena-nathawat` (speaker listing for “People Power: Building the Skills for Tomorrow’s Payments”; not an appointment).
- **Outcome:** Excluded. Only dated CHRO appointment recovered is May 2024. No in-window L&D / talent / OD / HR-transformation / CHRO appointment.
- **Commercial gate:** Not scored: wrong date / no current-window candidate.
- **Cross-signal hint:** `S1?` — Payments Unleashed speaker session is not an appointment; if the orchestrator finds an in-window dated quote from Nathawat on skills/workforce, route to Signal 1.
- **Flags:** `RF-FETCH` (ACI investor news-release HTML Access Denied; executive-leadership-team WebFetch timeout). Verification of the 2024 date rests on search-extracted page text plus the management bio.

### Admiral Group Plc

- **Families:** 1, 2, 3, 4, 5. Extended pass.
- **Queries run:** `"Admiral Group Plc" OR "Admiral Group" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR "Chief People Officer" OR CHRO) (appointed OR joins OR named) August 2026`; `site:admiralgroup.co.uk (appointed OR appointment OR joins OR named) (CHRO OR "Chief People" OR talent OR learning OR HR) August 2026`; `site:admiralgroup.co.uk (news OR press OR leadership OR management) ("Chief People Officer" OR "Head of Talent" OR "Chief Learning Officer") 2026`; `"Rachel Warwick" Admiral "Head of People" August 2026 appointed OR joins`; `"Rachel Warwick" "Admiral" "Head of People" (press OR newsroom OR appointed) -linkedin`.
- **URLs fetched/opened:** `https://www.admiralgroup.co.uk/management/zareena-brown` (curl HTTP/1.1; schema.org text: “appointed Group Chief People Officer in **September 2025**”); `https://www.admiralgroup.co.uk/who-we-are/our-board-and-management` (Zareena Brown still Group CPO; Rachel Lewis Group CFO); `https://admiralgroup.co.uk/news-releases/news-release-details/geraint-jones-retire-group-cfo-rachel-lewis-assuming-role-july` (CFO succession, not people leadership); `https://www.linkedin.com/posts/rachel-warwick-a2879a1b_admiralgroup-culture-peopleteam-activity-7491436789614800898-wPZp` (search-extracted: **2026-08-07** personal post “joining as Head of People for Group Functions”).
- **Outcome:** Excluded. CPO appointment is September 2025. Rachel Warwick “Head of People, Group Functions” appears **LinkedIn-only** (SOP §5: no LinkedIn-only moves without company/press corroboration) and first public post is **7 August 2026**, outside this window. No Admiral newsroom corroboration found.
- **Commercial gate:** Not scored: LinkedIn-only + first disclosure before 25 August 2026.
- **Cross-signal hint:** none (Warwick post is an arrival note, not VP+/CHRO-tier workforce commentary meeting S1).
- **Flags:** none.

### African Development Bank

- **Families:** 1, 2, 3, 5, 6 (`fr`). Extended pass.
- **Queries run:** `"African Development Bank" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR CHRO OR "People and Talent") (appointed OR joins OR named) August 2026`; `site:afdb.org (appointed OR appointment OR named OR joins) (talent OR learning OR CHRO OR "human resources" OR "people and talent") August 2026`; `site:afdb.org (news OR press) (appointment OR appointed OR named) (talent OR "human resources" OR learning) 2026`; **ISO 639-1 `fr`:** `"Banque africaine de développement" (nomination OR nommé OR nommée OR rejoint OR "prend la fonction") (talent OR "ressources humaines" OR apprentissage OR "transformation RH" OR DRH) août 2026`.
- **URLs fetched/opened:** `https://www.afdb.org/sites/default/files/2025/09/23/approved_new_bank_structure_as_of_01_september_2025.3.pdf` (J. EDJANGUE still VP People & Talent Management; J. KITAKULE-MUKUNGU Director Talent, Performance & Staff Development; R. A. VENEAU Careers, Learning & Talent Development; updated **1 September 2025**); `https://afdb.africa-newsroom.com/press/the-african-development-bank-appoints-jacques-edjangue-vice-president-for-people-and-talent-management` (effective **16 June 2023**); `https://www.afdb.org/en/news-and-events/african-development-bank-appoints-jessica-kitakule-mukungu-acting-director-talent-performance-management-and-staff-development-department-52943` (**30 June 2022**); `https://www.afdb.org/en/news-and-events/press-releases/abidjan-lagos-highway-megaproject-enters-new-phase-authority-board-meets-and-appoints-chair-94873` (WebFetch hit Cloudflare bot wall; search snippet is ALCoMA board chair / interim HR committee for a corridor authority, not AfDB People & Talent leadership).
- **Outcome:** Excluded. No in-window AfDB L&D/talent/HR-transformation appointment. French query returned third-party job ads (e.g. “Gestionnaire des ressources humaines” dated 2026-08-31 on formation.professionnallink.com), not a senior appointment announcement.
- **Commercial gate:** Not scored: no in-window §5 appointment.
- **Cross-signal hint:** none for ALCoMA (wrong entity / not AfDB people leadership).
- **Flags:** `RF-FETCH` (afdb.org press page Cloudflare interstitial).

### Almarai - المراعي

- **Families:** 1, 2, 3, 5, 6 (`ar`), 7. Extended pass.
- **Queries run:** `"Almarai" OR "المراعي" ("Chief Learning Officer" OR "Head of Talent" OR CHRO OR "Chief People Officer" OR "الموارد البشرية") (appointed OR joins OR named OR تعيين) August 2026`; `site:almarai.com (appointed OR appointment OR named OR leadership) (talent OR CHRO OR learning OR HR) 2026`; `site:almarai.com (news OR press OR leadership) (appointed OR تعيين OR CHRO OR "human resources") August 2026`; **ISO 639-1 `ar`:** `"المراعي" (تعيين OR عُين OR عُيّن OR ينضم OR منصب) (الموارد البشرية OR المواهب OR التعلم OR التطوير التنظيمي OR رئيس الموارد البشرية) أغسطس 2026`; `"نايف العمري" OR "نايف العُمري" OR "Naif Alomari" OR "Nayef Alomari" المراعي تعيين موارد بشرية`.
- **URLs fetched/opened:** `https://annualreport.almarai.com/governance/executive-management/` (Ayman Algeer listed as CHRO; joined CoE 2021, CHRO **2024**); `https://www.almarai.com/en/corporate/media-center/almarai-news/almarai-55-graduates-leadership` (**07/05/2026**; CEO Fawaz Al Jasser and CHRO Ayman Algeer attended; CHRO-attributed leadership-development quote); `https://www.almarai.com/en/corporate/media-center/almarai-news/almarai-signs-waad-program` (CHRO Ayman Al-Qeer quoted on national training; not an appointment); `https://www.almarai.com/ar/corporate/media-center/almarai-news/almarai-55-graduates-leadership` (Arabic counterpart of May graduation); `https://ae.linkedin.com/posts/%D8%AA%D9%86%D9%81%D8%B0%D9%8A%D9%88%D9%86-executives_%D8%AA%D8%B9%D9%8A%D9%8A%D9%86-%D8%A7%D9%84%D8%AF%D9%83%D8%AA%D9%88%D8%B1-%D9%86%D8%A7%D9%8A%D9%81-%D8%A7%D9%84%D8%B9%D9%85%D8%B1%D9%8A-naif-alomari-activity-7480324185278300160-zroJ` (**7 July 2026**; Dr Naif Alomari appointed academic-affairs director at **Dr. Sulaiman Al Habib Medical Group**, not Almarai).
- **Outcome:** Excluded. Arabic search synthesis that claimed a 27 August Almarai CHRO appointment of نايف العمري was **not corroborated**; the named appointment is a different person/employer. Ayman Algeer remains CHRO. May 2026 graduation and Waad items are not appointments and are outside this window.
- **Commercial gate:** Not scored: no in-window appointment.
- **Cross-signal hint:** `S1` — Almarai 55-graduates page (`https://www.almarai.com/en/corporate/media-center/almarai-news/almarai-55-graduates-leadership`) is not an appointment; CHRO-attributed talent/leadership-development commentary (`not an appointment — 7.1b`). Date **7 May 2026** is outside this window. Waad training agreement same pattern (`S1`, `S5?`).
- **Flags:** none.

### AssuredPartners

- **Families:** 1, 2, 3, 4, 5. Extended pass.
- **Queries run:** `"AssuredPartners" ("Chief Learning Officer" OR "Head of Learning" OR "Head of Talent" OR CHRO OR "Chief People Officer" OR "HR transformation") (appointed OR joins OR named) August 2026`; `site:assuredpartners.com (appointed OR appointment OR joins OR named) (CHRO OR talent OR learning OR "people officer" OR HR) August 2026`; `site:assuredpartners.com (news OR press OR leadership) ("Chief Human Resources" OR "Head of Talent" OR "Chief Learning Officer") 2026`.
- **URLs fetched/opened:** `https://www.assuredpartners.com/about-us/leadership-team/` (now **Gallagher** executive team; Susan E. Pietrucha listed as CHRO, joined Gallagher **2007** — not an AssuredPartners in-window appointment); `https://www.prweb.com/releases/assuredpartners-announces-chief-human-resources-officer-816975420.html` (**26 June 2023**, Andrea Brogger CHRO); `https://www.businessinsurance.com/gallagher-names-former-assuredpartners-execs-to-lead-practices/` (25 August 2026 adjacent industry news; manufacturing/energy/transport practice leaders, not HR/talent/L&D); `https://insurance-search.com/captivate-podcast/nurturing-and-advancing-all-talent-andrea-brogger-assuredpartners/` (podcast profile, not a dated appointment).
- **Outcome:** Excluded. AssuredPartners was acquired by Gallagher (closed August 2025). No in-window AssuredPartners L&D/talent/HR-transformation appointment. 2023 Brogger CHRO and Gallagher CHRO Pietrucha bios are incumbents / wrong date.
- **Commercial gate:** Not scored: no in-window §5 appointment.
- **Cross-signal hint:** `S1?` — Brogger talent podcast is not an appointment; orchestrator triages only if an in-window dated VP+/CHRO quote is separately verified.
- **Flags:** none.

### Bertelsmann, Inc.

- **Families:** 1, 2, 3, 5, 6 (`de`). Extended pass.
- **Queries run:** `"Bertelsmann, Inc." OR "Bertelsmann" ("Chief Learning Officer" OR "Head of Talent" OR CHRO OR "Chief People Officer" OR Personalvorstand) (appointed OR joins OR named OR ernannt) August 2026`; `site:bertelsmann.com (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") August 2026`; `site:bertelsmann.com (news OR press OR leadership) (ernannt OR appointed OR Personalvorstand OR CLO) August 2026`; **ISO 639-1 `de`:** `site:bertelsmann.com (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR "HR-Transformation" OR Personalvorstand) August 2026`.
- **URLs fetched/opened:** `https://www.bertelsmann.com/en/media/news/talent-meets-bertelsmann-international-talent-develops-ideas-for-the-future-in-berlin.html` (**Gütersloh / Berlin–07/01/2026**; CHRO Immanuel Hermreck quoted; employer-branding student event, not an appointment); `https://bcc-cdn.bertelsmann.com/asset/908027409915/document_k0rb7fm2jt673agan6e2qmio5f/Bertelsmann_At_a_Glance_2026.pdf` (Hermreck still CHRO; Steven Moran still CLO / Chief Partnership Officer); `https://www.bertelsmann.com/en/media/news/clement-schwebig-new-ceo-of-rtl-group-alexander-von-torklus-to-become-cfo.html` (RTL CEO/CFO, not people leadership); `https://www.bertelsmann.com/de/media/audio-und-video/personalvorstand-immanuel-hermreck-im-bertelsmann-business-podcast-mit-insead-professor-charles-galunic.html` (CHRO podcast; not an appointment).
- **Outcome:** Excluded. No August 2026 Bertelsmann, Inc. or Group people-leadership appointment. TMB 2026 is 1 July 2026 employer branding. Erika Kirchner remains CPO of Bertelsmann, Inc. (LinkedIn: Jan 2023–present) — LinkedIn-only tenure, not an in-window announcement.
- **Commercial gate:** Not scored: not an appointment / wrong date.
- **Cross-signal hint:** `S1` — TMB press release is not an appointment; CHRO Hermreck attributed talent/openness-to-change commentary (`not an appointment — 7.1b`). Date **1 July 2026** is outside this window.
- **Flags:** none.

### Boston Children's Hospital

- **Families:** 1, 2, 3, 4, 5. Extended pass.
- **Queries run:** `"Boston Children's Hospital" ("Chief Learning Officer" OR "Head of Talent" OR CHRO OR "Chief People Officer" OR "Chief Human Resources") (appointed OR joins OR named) August 2026`; `site:childrenshospital.org (appointed OR appointment OR named OR joins) (CHRO OR talent OR learning OR "human resources" OR "people officer") August 2026`; `site:childrenshospital.org (news OR press OR leadership) (appointed OR names) (HR OR talent OR "human resources" OR CHRO) 2026`; `"140 hospital and health system CHROs" Becker's "Lisa Abbott" 2026 date`.
- **URLs fetched/opened:** `https://childrenshospital.org/about-us/our-leadership/lisa-abbott` (Lisa M. Abbott EVP & CHRO since **2023**; no “new”/effective-date in window); `https://www.beckershospitalreview.com/hospital-management-administration/140-hospital-and-health-system-chros-and-chief-people-officers-to-know-2026/` (recognition list; Lisa Abbott profile on leadership-capability model / workforce-tech readiness; published **March 2026** per search corroboration); `https://tido.childrenshospital.org/tido-staffing-update-nadine-beauger-senior-director/` (Therapeutic Accelerator scientific-commercial hire, not HR).
- **Outcome:** Excluded. Incumbent CHRO. No in-window people-leadership appointment. Becker’s list is recognition, not an appointment, and is dated March 2026.
- **Commercial gate:** Not scored: not an appointment in-window.
- **Cross-signal hint:** `S1?` — Becker’s 2026 CHRO list describes Abbott’s leadership-capability and workforce-transformation work but is not a first-person attributed statement in this window; orchestrator triages.
- **Flags:** none.

### Capitec bank

- **Families:** 1, 2, 3, 5, 6 (`af`), 7. Extended pass.
- **Queries run:** `"Capitec bank" OR "Capitec Bank" ("Chief Learning Officer" OR "Head of Talent" OR CHRO OR "Chief People Officer" OR "Head of Learning") (appointed OR joins OR named) August 2026`; `site:capitecbank.co.za (appointed OR appointment OR named OR joins) (CHRO OR talent OR learning OR "human resources" OR people) August 2026`; `site:capitecbank.co.za (news OR press OR leadership) ("Group Executive" OR appointed) (HR OR talent OR learning OR people) 2026`; **ISO 639-1 `af`:** `"Capitec" (aangestel OR aangestelde OR "nuwe rol" OR benoem) (talent OR leer OR "menslike hulpbronne" OR "HR-transformasie" OR mense) Augustus 2026`.
- **URLs fetched/opened:** `https://www.capitecbank.co.za/globalassets/pages/investor-relations/financial-results/2026/annual-report/integrated_annual_report_2026.pdf` (Board-approved **1 April 2026**; welcomes Deepesh Desai Executive: Insurance 9 Apr 2026, Andy Baker Executive: Technology and Data 1 Mar 2026, Wim de Bruyn Executive: Transact 1 Mar 2026 — **not HR/L&D**; people/culture narrative including AI future-fit language); `https://www.capitecbank.co.za/globalassets/pages/investor-relations/financial-results/2026/annual-report/capitec_remuneration_report_2026.pdf`; `https://careers.capitecbank.co.za/go/Human-Resources/3666101/1000?q=&sortColumn=sort_title&sortDirection=desc` (HR category: “currently no open positions”; recent L&D Manager listing dated **2 May 2026**; page shows “Loading…” for live job widgets); `https://www.linkedin.com/posts/capitec-bank_for-womens-month-were-sitting-down-with-activity-7495068016808914944-blZN` (search-extracted **2026-08-17**; Rizwana Butler GE:HR and Suzanne Liebenberg Head Talent Management interview on capability/internal mobility — **not an appointment**, and **17 August** is before this window); `https://www.netwerk24.com/sake/maatskappye/gerrie-fourie-keer-vinnig-terug-na-capitec-as-direkteur-20260429-1032` (Afrikaans; Gerrie Fourie NED effective 1 August — **not people leadership**; announcement April 2026).
- **Outcome:** Excluded. Group Executive: HR remains Rizwana Butler (since March 2021). No in-window L&D/talent/CHRO appointment. Women’s Month interview is not an appointment and is dated 17 August. Afrikaans results were CEO/board, not HR appointments.
- **Commercial gate:** Not scored: no in-window §5 appointment. IAR people/AI language is investor narrative without a new people-leader appointment.
- **Cross-signal hint:** `S1` — Capitec Women’s Month LinkedIn (`…activity-7495068016808914944-blZN`) is not an appointment; GE:HR + Head of Talent attributed commentary on capability and internal mobility (`not an appointment — 7.1b`). First-seen **17 August 2026**, outside this window. `S5?` on IAR future-fit/AI people language (April 2026 report). `S4?` on May L&D Manager posting (single listing / wrong date).
- **Flags:** `RF-BLOCKED-ATS` (Capitec careers HR category HTML shows “Loading…” for live listings).

### Cleaver-Brooks

- **Families:** 1, 2, 3, 5. Extended pass.
- **Queries run:** `"Cleaver-Brooks" ("Chief Learning Officer" OR "Head of Talent" OR CHRO OR "Chief People Officer" OR "Vice President Human Resources") (appointed OR joins OR named) August 2026`; `site:cleaverbrooks.com (appointed OR appointment OR named OR joins) (CHRO OR talent OR learning OR HR OR "human resources") 2026`; `site:cleaverbrooks.com (news OR press OR leadership OR management) ("Head of Talent" OR "Chief Learning Officer" OR "HR transformation" OR "organizational development") 2026`.
- **URLs fetched/opened:** `https://cleaverbrooks.com/about-us/get-to-know-us/executive-leadership-team/vpofhumanresources` (Dennis Hettinger VP HR **since 2020**; joined 2006; no in-window update).
- **Outcome:** Excluded. Static leadership page. Scottie McDonald VP HR at **Cleaver-Brooks Sales and Service** (LinkedIn: Nov 2025) is LinkedIn-only, a different legal entity, and outside this window.
- **Commercial gate:** Not scored: no in-window appointment.
- **Cross-signal hint:** none.
- **Flags:** none.

### DHL Ecommerce

- **Families:** 1, 2, 3, 5, 6 (`de`), 7. Extended pass.
- **Queries run:** `"DHL Ecommerce" OR "DHL eCommerce" ("Chief Learning Officer" OR "Head of Talent" OR CHRO OR "Chief People Officer" OR "Head of Learning") (appointed OR joins OR named) August 2026`; `site:dhlecommerce.com OR site:dhl.com/ecommerce (appointed OR appointment OR named) (HR OR talent OR learning OR CHRO) 2026`; **ISO 639-1 `de`:** `"DHL eCommerce" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR CHRO) August 2026`.
- **URLs fetched/opened:** `https://www.linkedin.com/in/florian-bumberger` (divisional CHRO since **Jan 2019**); `https://www.linkedin.com/in/saadjuliana` (VP Global Talent Management & People Experience since **Jan 2022**; 3 Aug 2026 personal note on a talent program — not an appointment); `https://servicepoints.dhlecommerce.com/` (locator tool; no newsroom).
- **Outcome:** Excluded. No company/press appointment in-window. Incumbent CHRO/talent leaders. German query did not surface an ernannt/übernimmt people-leadership release for this division in August 2026. Seda Armağan CHRO DHL eCommerce Türkiye (May 2025) is country-level and outside window / LinkedIn-only.
- **Commercial gate:** Not scored: no in-window corroborated appointment.
- **Cross-signal hint:** none for Juliana S. 3 Aug note (personal, before window, not a strategic attributed statement of record).
- **Flags:** none. `site:dhlecommerce.com` newsroom is thin (service-point tool).

### DHL Supply Chain

- **Families:** 1, 2, 3, 4, 5, 6 (`de`). Extended pass.
- **Queries run:** `"DHL Supply Chain" ("Chief Learning Officer" OR "Head of Talent" OR CHRO OR "Chief People Officer" OR "Head of Learning" OR "HR transformation") (appointed OR joins OR named) August 2026`; `site:dhl.com OR site:group.dhl.com ("DHL Supply Chain") (appointed OR appointment OR named) (HR OR talent OR learning OR CHRO) August 2026`; **ISO 639-1 `de`:** `"DHL Supply Chain" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR Personalvorstand) August 2026`.
- **URLs fetched/opened:** `https://www.linkedin.com/in/danielakerkhoffguenther` (SVP HR DHL Supply Chain Europe **Jun 2026–present** — LinkedIn-only; June first disclosure); `https://www.linkedin.com/in/lindsay-bridges-6866464` (incumbent Global Head of HR; 14 Aug 2026 HR Evolution event promo); `https://www.linkedin.com/posts/daveames_at-dhl-supply-chain-we-have-a-very-strong-activity-7493012068141379584-hsIo` (**11 August 2026**; VP TA/TM/L&D on hiring-at-scale / AI in recruiting — not an appointment); `https://group.dhl.com/en/media-relations/press-releases/2025/personnel-changes-to-the-management-board-of-dhl-group.html` (**15 July 2025**; Oscar de Bok / Hendrik Venter **CEO** moves effective 16 Aug 2025, not HR).
- **Outcome:** Excluded. No company-primary in-window people-leadership appointment. Kerkhoff-Guenther SVP HR Europe is LinkedIn-only and June 2026. Dave Ames / Lindsay Bridges August posts are not appointments and are dated **11–14 August**, before this window.
- **Commercial gate:** Not scored: LinkedIn-only / wrong date / not an appointment.
- **Cross-signal hint:** `S1` — Dave Ames Front Line discussion (`…activity-7493012068141379584-hsIo`) is not an appointment; VP-tier talent-acquisition / AI-hiring commentary (`not an appointment — 7.1b`). Date **11 August 2026** is outside this window.
- **Flags:** none.

### DHL Express

- **Families:** 1, 2, 3, 4, 5, 6 (`de`). Extended pass.
- **Queries run:** `"DHL Express" ("Chief Learning Officer" OR "Head of Talent" OR CHRO OR "SVP Human Resources" OR "Chief People Officer") (appointed OR joins OR named) August 2026`; `site:express-resource.dhl.com OR site:dhl.com "DHL Express" (appointment OR appointed OR joins OR named OR leadership) (learning OR talent OR "HR transformation" OR "SVP Human Resources") August 2026`; **ISO 639-1 `de`:** `"DHL Express" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR Personalvorstand OR HR-Transformation) August 2026`.
- **URLs fetched/opened:** `https://www.dhl.com/in-en/home/press/press-archive/2025/dhl-express-enhances-asia-pacific-leadership-team-with-strategic-appointments-in-hr-and-taiwan.html` and `https://www.dhl.com/hk-en/home/press/press-archive/2025/dhl-express-enhances-asia-pacific-leadership-team-with-strategic-appointments-in-hr-and-taiwan.html` (search-extracted full text: Chee Choong Ng SVP HR Asia Pacific **effective 1 January 2026**; 2025 press archive. Direct curl of HK URL returned empty body; India WebFetch timed out; r.jina.ai Cloudflare interstitial); `https://hr.economictimes.indiatimes.com/news/industry/dhl-express-hr-global-metrics-engagement-diversity-wellbeing-strategies/130074384` (**published 7 April 2026**; Fadzlun Sapandi EVP Global HR exclusive on engagement, mobility, leadership programmes — **not an appointment**); `https://www.linkedin.com/in/plavsin` (VP Global Talent & Experience **Jan 2026** — LinkedIn-only, outside window); `https://group.dhl.com/en/about-us/corporate-governance/board-of-management/thomas-ogilvie.html` (search-extracted: Thomas Ogilvie Group HR Board member since Sep 2017, appointed until Aug 2030; curl empty).
- **Outcome:** Excluded. APAC HR appointment effective 1 Jan 2026 / 2025 press. ETHRWorld piece is April 2026 commentary, not an appointment. No in-window Express L&D/talent/CHRO appointment.
- **Commercial gate:** Not scored: wrong date / not an appointment.
- **Cross-signal hint:** `S1` — ETHRWorld (`https://hr.economictimes.indiatimes.com/news/industry/dhl-express-hr-global-metrics-engagement-diversity-wellbeing-strategies/130074384`) is not an appointment; EVP Global HR attributed workforce/leadership-capability commentary (`not an appointment — 7.1b`). Date **7 April 2026** is outside this window.
- **Flags:** `RF-FETCH` (dhl.com HK empty curl; India timeout; jina.ai Cloudflare; group.dhl.com Ogilvie page empty curl). Appointment facts recovered from search-extracted press text plus ETHRWorld fetch.

### DHL global forwarding

- **Families:** 1, 2, 4, 5, 6 (`de`). Extended pass.
- **Queries run:** `"DHL global forwarding" OR "DHL Global Forwarding" ("Head of Talent" OR CHRO OR "Chief People Officer" OR "Chief Learning Officer" OR "HR transformation") (appointed OR joins OR named) August 2026`; `site:dhl.com "DHL Global Forwarding" (appointment OR appointed OR named OR leadership) (learning OR talent OR "Head Talent" OR "HR transformation") August 2026`; **ISO 639-1 `de`:** `"DHL Global Forwarding" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) August 2026`.
- **URLs fetched/opened:** `https://hrtoday.in/suparna-chatterjee-appointed-as-head-hr-gsc-bom-at-dhl-global-forwarding/` (WebFetch: **May 2026**, Head HR Global Service Centre Mumbai — local GSC HR, not enterprise CLO/talent/HR-transformation; outside window); `https://www.linkedin.com/posts/hrtoday_mohitrai-dhlglobalforwarding-dhl-activity-7494297522849628160-OZgp` (search-extracted **15 August 2026**; Mohit Rai Global Head of **Global Service Centers** — operations, not HR/L&D; LinkedIn-only; **15 Aug** before this window); `https://www.linkedin.com/in/harm-otten-7bb76441` (incumbent EVP HR DGF&F); `https://www.linkedin.com/in/isabel-rudolph-a46355104` (Head of Global Talent Management & TA since **May 2022**).
- **Outcome:** Excluded. No in-window company-primary DGF talent/L&D/CHRO appointment. Chatterjee is May 2026 local GSC HR. Mohit Rai is not a people-function appointment and is LinkedIn-only dated 15–17 August.
- **Commercial gate:** Not scored: wrong date / wrong function / LinkedIn-only.
- **Cross-signal hint:** none for Mohit Rai (operations GSC head, not S1 people commentary).
- **Flags:** none on hrtoday.in (fetch succeeded).

### DHL

- **Families:** 1, 2, 3, 5, 6 (`de`), 7. Extended pass.
- **Queries run:** `"DHL" ("Chief Learning Officer" OR "Chief People Officer" OR CHRO OR "Head of Talent" OR Personalvorstand) (appointed OR joins OR named OR ernannt) August 2026 -ecommerce -"supply chain"`; `site:dhl.com OR site:group.dhl.com (appointment OR appointed OR named OR leadership) (learning OR talent OR "Head Talent" OR "HR transformation") August 2026`; **ISO 639-1 `de`:** `"DHL" (ernannt OR übernimmt OR Leitung OR Berufung) (Personalvorstand OR Talent OR Lernen OR Personalentwicklung OR HR-Transformation) August 2026`.
- **URLs fetched/opened:** `https://www.linkedin.com/posts/anne-walther-303b196b_dhl-womeninlogistics-greatpeoplebestteams-activity-7487138666864115712-hM_U` (search-extracted **26 July 2026**; Anne Walther personal post on transition to **EVP Global HR Group Functions**; LinkedIn-only; April 2026 role start / July post — both outside window); `https://group.dhl.com/en/about-us/corporate-governance/board-of-management/thomas-ogilvie.html` (incumbent Group HR Board member since 2017); `https://reporting-hub.group.dhl.com/2025-fy/en/the-company/boards-and-committees/members-of-and-mandates-held-by-the-board-of-management/` (Ogilvie appointed until August 2030 — mandate end year, not a new appointment); `https://hrtoday.in/dr-ralph-wiechers-appointed-as-chief-people-officer-cpo-labor-director-at-sana-kliniken/` (**January 2026**, Wiechers **left** DHL for Sana Kliniken — not a DHL appointment).
- **Outcome:** Excluded as parent-row. No additional DHL Group-wide in-window people-leadership appointment beyond division-row near-misses already logged. Walther EVP HR Group Functions is LinkedIn-only and first discussed in July 2026.
- **Commercial gate:** Not scored: LinkedIn-only / wrong date.
- **Cross-signal hint:** `S1` — Anne Walther 26 July post is not an appointment announcement meeting §5 corroboration; it is VP+/EVP-tier people commentary on HR Roadmap 2030 (`not an appointment — 7.1b`). Outside this window.
- **Flags:** `RF-FETCH` (group.dhl.com Ogilvie page empty on curl). `RF-DEDUPE-ROW` vs division near-misses (Express APAC HR; DGF GSC HR; Supply Chain LinkedIn SVP HR) — none included in Part A′.

### DOVISTA

- **Families:** 1, 2, 3, 5, 6 (`da`), 7. Extended pass.
- **Queries run:** `"DOVISTA" ("Chief Learning Officer" OR "Head of Talent" OR CHRO OR "Chief People Officer" OR "Head of HR") (appointed OR joins OR named OR udnævnt) August 2026`; `site:dovista.com (appointment OR appointed OR named OR joins OR leadership) (learning OR talent OR "HR transformation" OR "organizational development") August 2026`; `site:dovista.com (news OR press OR management OR leadership) (appointed OR udnævnt OR CHRO OR "People & Culture") 2026`; **ISO 639-1 `da`:** `"DOVISTA" (udnævnt OR tiltræder OR ansat OR "ny rolle" OR leder) (talent OR læring OR HR-transformation OR organisationsudvikling OR "HR-chef" OR "People & Culture") august 2026`.
- **URLs fetched/opened:** `https://dovista.com/management/` (Annette Palmelund-Jahn listed as CHRO; no dated “new” designation); `https://dovista.com/wp-content/uploads/2024/01/DEI-Policy.pdf` (static policy naming CHRO accountability; 2024); LinkedIn snippets for Christina Birch Vosgerau Head of Organisation & Development (**Feb 2025**) and Morten Hansen 18 May 2026 post “live with phase 1 of our HRIT system implementation” (Oracle HCM) — neither is an in-window appointment.
- **Outcome:** Excluded. Incumbent CHRO since May 2023. Danish queries returned P&C Business Partner vacancies and HRIT go-live chatter, not a senior appointment in 25–31 August 2026. July 2026 O&D Consultant vacancy is a job posting, not an appointment.
- **Commercial gate:** Not scored: no in-window §5 appointment.
- **Cross-signal hint:** `S6?` — Morten Hansen LinkedIn 18 May 2026 HRIT/Oracle HCM phase-1 go-live (outside window; LinkedIn-only; orchestrator would still need company-primary corroboration for Signal 6). `S4?` for O&D Consultant posting (single listing, July).
- **Flags:** none.

---

**§7.1a local-language log (ISO 639-1 + full query string):**

- `fr` — African Development Bank: `"Banque africaine de développement" (nomination OR nommé OR nommée OR rejoint OR "prend la fonction") (talent OR "ressources humaines" OR apprentissage OR "transformation RH" OR DRH) août 2026`
- `ar` — Almarai - المراعي: `"المراعي" (تعيين OR عُين OR عُيّن OR ينضم OR منصب) (الموارد البشرية OR المواهب OR التعلم OR التطوير التنظيمي OR رئيس الموارد البشرية) أغسطس 2026`
- `de` — Bertelsmann, Inc.: `site:bertelsmann.com (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR "HR-Transformation" OR Personalvorstand) August 2026`
- `de` — DHL Ecommerce: `"DHL eCommerce" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR CHRO) August 2026`
- `de` — DHL Supply Chain: `"DHL Supply Chain" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation OR Personalvorstand) August 2026`
- `de` — DHL Express: `"DHL Express" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR Personalvorstand OR HR-Transformation) August 2026`
- `de` — DHL global forwarding: `"DHL Global Forwarding" (ernannt OR übernimmt OR Leitung OR Berufung) (Talent OR Lernen OR Personalentwicklung OR HR-Transformation) August 2026`
- `de` — DHL: `"DHL" (ernannt OR übernimmt OR Leitung OR Berufung) (Personalvorstand OR Talent OR Lernen OR Personalentwicklung OR HR-Transformation) August 2026`
- `af` — Capitec bank: `"Capitec" (aangestel OR aangestelde OR "nuwe rol" OR benoem) (talent OR leer OR "menslike hulpbronne" OR "HR-transformasie" OR mense) Augustus 2026`
- `da` — DOVISTA: `"DOVISTA" (udnævnt OR tiltræder OR ansat OR "ny rolle" OR leder) (talent OR læring OR HR-transformation OR organisationsudvikling OR "HR-chef" OR "People & Culture") august 2026`

**Master §7.2:** HR / HR-tech trade-media sweep is **pending on the orchestrator**; this lane did not run or substitute for it.

---

## Batch summary

- **Batch id:** S2-B01
- **Rows assigned:** 15
- **Rows completed:** 15
- **Rows with ≥1 Part A′ entry:** 0
- **Flags (count by type):** RF-FETCH: 4 rows (ACI Worldwide investor HTML; African Development Bank Cloudflare; DHL Express dhl.com/jina; DHL parent Ogilvie page). RF-BLOCKED-ATS: 1 (Capitec careers). RF-DEDUPE-ROW: 1 (DHL parent vs division near-misses). RF-PAYWALL: 0. RF-IDENTITY: 0. RF-WAIVER: 0.
- **Cross-signal hints:** S1 — Almarai 55-graduates CHRO quote (May 2026, out of window); S1 — Bertelsmann TMB Hermreck quote (1 Jul 2026, out of window); S1 — Capitec Women’s Month Butler/Liebenberg interview (17 Aug 2026, out of window); S1 — DHL Express ETHRWorld Sapandi interview (7 Apr 2026, out of window); S1 — DHL Supply Chain Dave Ames TA/AI-hiring post (11 Aug 2026, out of window); S1 — DHL Anne Walther HR Roadmap 2030 post (26 Jul 2026, out of window); S1? — ACI Payments Unleashed speaker; S1? — Boston Children's Becker’s CHRO list (Mar 2026); S1? — AssuredPartners Brogger podcast; S5? — Capitec IAR people/AI; S5? — Almarai Waad; S6? — DOVISTA Oracle HCM phase-1 (May 2026); S4? — Capitec L&D Manager listing; S4? — DOVISTA O&D Consultant listing.
