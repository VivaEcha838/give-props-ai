# GivePropsAI — 2026 Live Season Results
*Extracted from production pipeline outputs*
*Last Updated: 2026-04-12*

> **Data sources:**
> - `index.html` — daily summary table + pick-by-pick grading log (77 picks tracked through 04-11)
> - `picks_table_2026-04-11.html` — ungraded picks slate for April 11 (V2 dual-filter + V1 + EXP models)
> - `picks_table_2026-04-12.html` — ungraded picks slate for April 12 (V2 dual-filter + V1 + EXP models)
>
> **Unit basis:** $100 flat stake per pick (confirmed by totals: 76 graded picks × $100 = $7,600 staked)
>
> **Coverage gap:** No production data found for March 25 – April 4 (season open through first week). First graded game day in the data is April 5, 2026.

---

## Season Summary
*(Through April 11, 2026 — April 12 picks pending grading)*

| Metric | Value |
|--------|-------|
| Total Game Days | 7 (Apr 5–11) |
| Total Picks (graded) | 76 of 77 tracked (1 pending) |
| Record | 43–33 |
| Win Rate | 56.6% |
| Total P/L | −$99.35 (−0.99 units) |
| Total Staked | $7,600 |
| ROI | −1.3% |

---

## Daily Results

| Date | Picks | Record | Win % | P/L ($) | P/L (units) | Running P/L | Markets |
|------|-------|--------|-------|---------|-------------|-------------|---------|
| 2026-04-05 | 14 | 8–6 | 57.1% | −$22.11 | −0.22 | −0.22 | K 3–2 · H 3–1 · BB 2–3 |
| 2026-04-06 | 4 | 3–1 | 75.0% | +$82.81 | +0.83 | +0.61 | K 2–0 · BB 1–1 |
| 2026-04-07 | 22 | 9–12¹ | 42.9% | −$448.75 | −4.49 | −3.88 | K 3–4 · H 1–2 · BB 5–6 |
| 2026-04-08 | 10 | 7–3 | 70.0% | +$222.40 | +2.22 | −1.66 | K 2–0 · H 1–0 · BB 4–3 |
| 2026-04-09 | 5 | 4–1 | 80.0% | +$176.84 | +1.77 | +0.11 | H 1–0 · BB 3–1 |
| 2026-04-10 | 9 | 5–4 | 55.6% | −$117.41 | −1.17 | −1.06 | K 2–2 · H 1–0 · BB 2–2 |
| 2026-04-11 | 13 | 7–6 | 53.8% | +$6.87 | +0.07 | −0.99 | K 1–1 · H 2–0 · BB 4–5 |
| 2026-04-12 | TBD | Pending | — | — | — | — | Picks posted, not yet graded |
| **TOTAL** | **77** | **43–33** | **56.6%** | **−$99.35** | **−0.99** | **−0.99** | |

> ¹ April 7 includes 1 pick (Drew Rasmussen BB Under 1.5) still showing PENDING in the data; W-L record reflects graded picks only.

---

## Results by Market
*(Computed from pick-by-pick grading log in `index.html`; excludes 1 pending pick)*

| Market | Record | Win % | P/L ($) | P/L (units) |
|--------|--------|-------|---------|-------------|
| Strikeouts (K) | 13–9 | 59.1% | +$240.78 | +2.41 |
| Hits Allowed (H) | 9–3 | 75.0% | +$365.04 | +3.65 |
| Walks (BB) | 21–21 | 50.0% | −$705.17 | −7.05 |
| **TOTAL** | **43–33** | **56.6%** | **−$99.35** | **−0.99** |

---

## Results by Confidence Tier
*(Computed from pick-by-pick grading log in `index.html`; excludes 1 pending pick)*

> **Note on tier labels:** The production data uses three tiers — ELITE, PREMIUM, and PICK. No "Strong" or "Standard" tier labels were found in the data files.

| Tier | Record | Win % | P/L ($) | P/L (units) |
|------|--------|-------|---------|-------------|
| ELITE | 21–16 | 56.8% | −$35.91 | −0.36 |
| PREMIUM | 6–2 | 75.0% | +$304.01 | +3.04 |
| PICK | 16–15 | 51.6% | −$367.45 | −3.67 |
| **TOTAL** | **43–33** | **56.6%** | **−$99.35** | **−0.99** |

---

## Data Gaps & Notes

- **March 25 – April 4:** No production result files found covering the season-opening period. First graded day in the repository is April 5.
- **April 12:** Picks slate was posted (`picks_table_2026-04-12.html`, commit `daec14a`) but no grading data is present yet. This was noted in the commit message as "first day of V2 dual-filter tracking."
- **April 11 pending picks:** The picks tables in `picks_table_2026-04-11.html` show V2, V1, and EXP model slates all marked "Pending" — these appear to be the pre-game posting format; the graded results are captured in `index.html`.
- **Model versions:** The picks tables distinguish V2 (dual-filter), V1, and EXP model variants. The summary-level `index.html` data does not break out performance by model version.
- This is described as a **"V2 live forward test"** in the data — not a backtest.
