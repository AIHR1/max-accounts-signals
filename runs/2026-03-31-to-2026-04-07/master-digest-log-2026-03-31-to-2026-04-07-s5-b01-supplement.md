# Orchestrator supplement — S5-B01 checkpoint rows

**Run id:** `2026-03-31-to-2026-04-07`  
**Parent batch:** S5-B01  
**Purpose:** Close subagent CHECKPOINT on **African Development Bank** and **Admiral Group Plc** without RF-WAIVER.

## Part L — follow-up verification (2026-04-07)

| Account row | Action | Outcome | Flags |
| ----------- | ------ | ------- | ----- |
| African Development Bank | Orchestrator `curl -sI` to `https://www.afdb.org/en/about-us/careers/current-vacancies/` | **HTTP 403** (Cloudflare challenge); automated fetch still blocks §8.1 on April 2026 press URLs noted in S5-B01 | **RF-FETCH** |
| Admiral Group Plc | Re-attempt IR/news URL from S5-B01 (timeout in lane); no new issuer PDF retrieved in orchestrator shell | §5 skills-gap language not verified in-window on issuer primary; lane already logged queries + partial paths | **RF-FETCH** |

**Conclusion:** §7 discovery minimums for these two rows are evidenced in `master-digest-log-2026-03-31-to-2026-04-07-s5-b01.md` (subagent Part L) plus this supplement; matrix may mark **Attempted** for `[skills-gaps]` with **RF-FETCH** noted in Part B (not waiver).
