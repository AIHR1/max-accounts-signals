# Runner brief — 2026-W36 (read before discovery)

**Run id:** `2026-W36`  
**Review period:** 25 August 2026 through 31 August 2026 **inclusive**  
**Run date:** 31 August 2026  
**Date rule:** Publication / announcement / first-seen date per the assigned child SOP §6. Manually filter search hits to this window; do not trust search-engine date operators alone.  
**User-approved waivers:** none. Do **not** use RF-WAIVER for time, tooling, or capacity. If you cannot finish every assigned row, append a CHECKPOINT section naming unfinished rows.

## Disk write (blocking)

Write **one** file at the exact path given in your Task prompt, using `templates/batch-lane-log-template.md` structure.

First line of body: `Batch id: S{N}-B{MM} | Signal: {N} | Run id: 2026-W36`

**Forbidden Part L filler** (do not copy these as the only cell text across rows): `Multiple full-query`, `per subagent`, `Candidate URLs opened/fetched per lane`, `families 1–7 per`, `Outcome per §8.1 (included/excluded + reason)`, `Cross-signal hints where applicable`, “evidence in orchestrator session”.

Each account row **must** appear in Part L with **row-specific full query strings** you actually ran, URLs you opened/fetched (or “none beyond search snippets”), outcome, commercial-gate note, Cross-signal hint if applicable, and flags.

## Discovery

Read and follow the assigned child SOP under `sops/` **Sections 5, 6, 7, 8**. For **each row**:

- Families **1–3** minimum with **distinct query shapes** (not trivial rephrases).
- Family **4** when the SOP requires it (named leader for S1; executive-move outlets for S2; etc.).
- If 1–3 are empty/weak: extended pass families **5–7** (or 5–6 if that is all the SOP lists). Log “extended pass”.
- Use the **exact account name** from the table at least once per row. Division rows (DHL*, Orange*, Logitech*, Viasat*) are **atomic** — do not assume one search covers siblings unless you log why and still include each row name.
- Fetch/open candidate primary URLs (WebFetch, curl with browser UA / HTTP/1.1, official mirrors, wire copies, PDFs, `https://r.jina.ai/http(s)://…` last resort). Log every channel.

## Commercial gate (`sops/sop-master-digest.md` §4.1)

Score 1–5 on Relevance, Actionability, Stakeholder clarity, Specificity, Timing. Include in Part A′ only if **≥18/25** and Relevance **≥3** and Specificity **≥3**, and you can answer Why AIHR / capability gap / stakeholder from the public evidence.

Always exclude: investor/strategy noise without workforce detail; generic GenAI slogans; capex/plant without people capability; internships/graduates/campus; single generic job postings; employer branding; boilerplate talent-risk disclosures; generic IT/data hiring without HR/workforce-capability cluster.

## Cross-signal (mandatory)

Every URL you actually retrieve/open goes in Part L with included/excluded + reason. If excluded for **this** SOP §5 but clearly matches another signal, set `Cross-signal: S#` (or `S#?`). Signal 2: if not an appointment but VP+/CHRO-tier people commentary exists, **must** set `Cross-signal: S1`.

## §7.1a local language (mandatory for listed rows)

Log **ISO 639-1 + full query string** for every non-English attempt. Use **August-window date tokens that match the language**:

- French: `août` 2026 (not `juin`)
- German: `August` 2026 (not `Juni` / not French `juin`)
- Arabic: `أغسطس` 2026
- Danish: `august` 2026
- Afrikaans: `Augustus` 2026
- Chinese: `八月` 2026 or `8月` 2026

**Mandatory language rows in this run (apply on every signal you are assigned):**

- `fr`: African Development Bank; ENGIE; Orange Group; Orange SA; Orange Business; Pierre Fabre Laboratories; RATP Dev; Schneider Electric
- `de`: Bertelsmann, Inc.; DHL Ecommerce; DHL Supply Chain; DHL Express; DHL global forwarding; DHL; METRO AG; Phoenix Contact
- `ar`: Almarai - المراعي; Emirates group
- `da`: DOVISTA
- `af`: Capitec bank; Momentum Metropolitan; Stellenbosch University; Toyota SA; Woolworths
- `zh`: Galaxy Entertainment Group

Do not paste the same English boilerplate into every language query. Use real local titles/vocabulary from the child SOP §7.1a / family 6 examples.

## Part A′ format

Use master SOP §8 template with exact tag:

- S1 `[chro-statement]` (CHRO)
- S2 `[leadership-appointment]` (LEAD)
- S3 `[transformation-initiative]` (TRANS)
- S4 `[hiring-trends]` (HIRE)
- S5 `[skills-gaps]` (SKILL)
- S6 `[hr-technology]` (HRTECH)

Fields: Account, Date, Source, Link, What changed, Why it matters, Relevant stakeholder, Commercial hypothesis, Score, optional Signal.

Omit rows with no qualifying hit from Part A′ (they still belong in Part L).

## Signal-specific reminders

**S1:** Attributed VP+ HR/talent/learning statement on skills, L&D, workforce strategy, HR transformation, people analytics, or AI-workforce. Family 4 named pass when identity is publicly resolvable.

**S2:** New appointment / new remit in L&D, talent (strategic), OD, HR transformation. CHRO/CPO **appointments** belong here. Interviews that are **not** appointments → exclude + `Cross-signal: S1`. No LinkedIn-only moves without company/press corroboration.

**S3:** Enterprise-scale transformation **with** workforce/capability angle. Exclude generic AI/productivity/capex without people implications.

**S4:** Cluster of **3+** professional-track HR/L&D/people-analytics/HRIS/change/leadership-capability roles **or** explicit company hiring statement in those domains. Exclude intern/graduate/campus and generic IT hiring. TTEC: Radancy `https://www.ttecjobs.com/en/search-jobs` exposes category facets in HTML; use official `site:ttecjobs.com/en/job` detail pages. Wood Mackenzie: Workday CXS POST `https://woodmac.wd3.myworkdayjobs.com/wday/cxs/woodmac/woodmaccareers/jobs` with JSON `{"appliedFacets":{},"limit":20,"offset":0,"searchText":"HR"}`.

**S5:** Company-attributed, specific, business-tied skills gap / reskill / upskill / workforce-constraint language (filings, earnings, official letters). Not SOP1 interview voice unless it is also a formal disclosure. Not boilerplate “attract and retain” risk language.

**S6:** Confirmed implementation/go-live/rollout of LMS/LXP/HRIS/skills platform/people analytics **with company-primary or customer-corroborated** evidence. Vendor-only “X selected our product” without customer confirmation is excluded.

## Batch summary

End with: batch id, rows assigned, rows with ≥1 Part A′ entry, flag counts, list of Cross-signal hints.

If incomplete: `## CHECKPOINT — incomplete batch` with unfinished rows, reason, next step.

Do **not** edit the merged digest, manifest, or other batches’ files.
