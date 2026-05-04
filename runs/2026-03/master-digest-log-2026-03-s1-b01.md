# Batch lane log

**Run id:** `2026-03`  
**Signal # (1–6):** 1  
**Batch id:** `S1-B01`  
**Review period:** 1–31 March 2026 (publication date rule, SOP §6)  
**Account rows in this batch:** ACI Worldwide; Admiral Group Plc; African Development Bank; Almarai - المراعي; AssuredPartners; Bertelsmann, Inc.; Boston Children's Hospital; Capitec bank; Cleaver-Brooks; DHL Ecommerce; DHL Supply Chain

---

## Part A′ — Verified entries (this signal × this batch only)

[chro-statement] (CHRO)  
Account: Bertelsmann, Inc.  
Date: 18 March 2026  
Source: Corporate press release (German newsroom; Personalvorstand quoted)  
Link: https://www.bertelsmann.de/de/media/nachrichten/talent-meets-bertelsmann-2026-internationale-studierende-gestalten-zukunftsthemen-in-berlin.html  
Signal: Immanuel Hermreck, Personalvorstand (executive board member for HR) of Bertelsmann, is quoted on the opening of applications for the 18th “Talent Meets Bertelsmann” career event: he describes bringing students together with company decision-makers, highlights participants’ energy and perspectives on current challenges, and frames the event as early identification of exceptional talent, within the group’s “Create Your Own Career” employer-branding strand (applications through 3 May 2026; event 29 June–1 July 2026, Berlin).

English mirror: https://www.bertelsmann.de/en/media/news/talent-meets-bertelsmann-2026-international-students-tackle-future-focused-topics-in-berlin.html

## Part L — Execution log

Master HR trade-media sweep (sop-master-digest §7.2): **completed** — see `run-manifest-2026-03.md` trade media audit table.

**§7.1a logged attempts (ISO 639-1 + full query string)**

| ISO | Full query string |
|-----|-------------------|
| fr | `site:afdb.org direction ressources humaines OR DRH interview mars 2026` |
| fr | `"Banque africaine de développement" DRH entretien mars 2026 compétences` |
| ar | `site:almarai.com الموارد البشرية OR رئيس الموارد البشرية مقابلة 2026` |
| de | `Bertelsmann Personalvorstand Interview März 2026 Kompetenzen` |

| Account row | Families run | Queries (full strings) | URLs fetched / channel | Outcome | Flags |
|-------------|--------------|-------------------------|-------------------------|---------|--------|
| ACI Worldwide | 1–3, 4, 5–7 | `ACI Worldwide CHRO OR "Chief People Officer" interview March 2026`; `site:aciworldwide.com CHRO OR "human resources" OR talent interview 2026`; `"ACI Worldwide" Praveena Nathawat interview podcast workforce March 2026`; `"ACI Worldwide" human resources OR CHRO statement March 2026 site:aciworldwide.com OR site:investor.aciworldwide.com` | investor.aciworldwide.com CHRO appointment (pre-window); management pages | No in-period CHRO/CPO statement | — |
| Admiral Group Plc | 1–3, 4, 5–7 | `Admiral Group CHRO "Chief People Officer" March 2026 interview`; `site:admiralgroup.co.uk HR leadership interview podcast 2026`; `Admiral Group "Zareena Brown" interview podcast workforce March 2026` | admiralgroup.co.uk management; admiraljobs.co.uk blog timeout | No verified Part A′; jobs blog not confirmed | **RF-FETCH** (admiraljobs.co.uk timeout) |
| African Development Bank | 1–3, 6 (fr×2), 5–7 | English + fr §7.1a above | afdb.org IWD 2026 piece 06-Mar-2026 | Excluded: speaker Director Gender/Women/Civil Society, not CHRO/CPO tier | — |
| Almarai - المراعي | 1–3, 4, 6 (ar), 5–7 | English + ar §7.1a | almarai.com paths | No in-period attributed CHRO statement | — |
| AssuredPartners | 1–3, 4, 5–7 | AssuredPartners CHRO queries + Andrea Brogger podcast | insurance-search.com captivate podcast | Excluded: episode publication date not confirmed in Mar 2026 window | — |
| Bertelsmann, Inc. | 1–3, 6 (de), 4, 5–7 | de §7.1a + site passes | bertelsmann.de DE/EN PR 18 Mar 2026; firmenpresse.de republish | Included Part A′ | — |
| Boston Children's Hospital | 1–3, 4, 5–7 | BCH CHRO / Lisa Abbott queries | childrenshospital.org newsroom; beckershospitalreview.com | No Part A′; Becker’s 403 | **RF-FETCH** (Becker’s 403) |
| Capitec bank | 1–3, 4, 5–7 | Capitec CHRO interview queries | careers; third-party | No in-window CHRO statement | — |
| Cleaver-Brooks | 1–3, 4, 5–7 | Cleaver-Brooks CHRO queries | cleaverbrooks.com | No Mar 2026 CHRO statement | — |
| DHL Ecommerce | 1–3, 4, 5–7 | DHL Ecommerce CHRO queries | dhl.com ecommerce pages | No in-period qualifying signal | — |
| DHL Supply Chain | 1–3, 4, 5–7 | DHL Supply Chain CHRO queries | peoplemattersglobal.com interview | Excluded: publication 30 Nov 2023, outside window | — |

## Batch summary

- Rows assigned: 11  
- Rows with ≥1 Part A′ entry: 1 (Bertelsmann, Inc.)  
- Flags: RF-FETCH ×2 | Master §7.2 sweep: completed (manifest audit table)  

---

_File:_ `runs/2026-03/master-digest-log-2026-03-s1-b01.md`
