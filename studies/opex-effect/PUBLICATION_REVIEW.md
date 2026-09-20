# OPEX research paper — publication review

**Status: Publication edition prepared; binary PDF upload and provenance confirmation outstanding.** Editorial review dated September 2026. This review concerns the supplied report, **not** the original Excel workbook or independent reproduction of any backtest.

## File and presentation inspection

- Inspected the complete supplied 13-page PDF and the earlier 14-page candidate (including its editorial notice).
- The report includes its own-looking regression chart, lookback chart, horizon charts and historical equity-curve graphic. Five embedded image objects were retained in the cleaned publication edition. No external hyperlink, explicit copyright notice, source-image credit, or obvious third-party logo was found in extracted text and page inspection. **This does not prove who made the graphics or whether underlying price data can be redistributed.**
- The edition has a new editorial cover distinguishing source claims from verified research. A stray drafting header was removed and a trailing header-only page was omitted. Main research text, tables, statistics, captions and figures were otherwise preserved.
- The report's original PDF metadata title was unrelated to its content; the publication edition carries a research-specific title. No private trading-system draft is included.

## Unresolved quantitative issues

| Issue | Evidence in supplied paper | Publication treatment |
|---|---|---|
| Equity-expiry event count | States 80 *monthly* events January 2020–December 2025, which spans 72 months | Label 80 as an unverified source claim; reconcile exact event log, duplicates, weekly/quarterly expiries, and exclusions before inferential claims. |
| VIX-expiry event count | States 276 *monthly* events May 2004–December 2025, which spans 260 months | Label 276 as unverified; obtain exact dates and event definition. |
| Comparison as control | OPEX sample 2020–2025, VIX sample 2004–2025 | Distinct windows and instrument settlement make this a comparison, **not** a matched causal control. |
| Statistical selection | Six lookbacks, eight forward horizons and selloff/rally splits; no untouched holdout documented | Report nominal statistics as exploratory, not proof of a stable alpha. |
| Performance accounting | No costs; workbook and event-level trade logs not supplied | No independent claim that the Sharpe, cumulative return, drawdown or execution rule has been verified. |
| Proposed mechanism | Dealer gamma hedging narrative without observed hedge inventory or flow data | Present as a hypothesis rather than a demonstrated causal explanation. |

**Rights assessment:** Visual/source-marker screening found no obvious pasted third-party branded figures, but attribution and permissions cannot be established from a PDF alone. Confirm that the author created or is entitled to share its figures and that source-data terms allow this form of published aggregate research. Do not publish raw licensed market-data extracts without separately checking rights. This is a publication screening record, not legal clearance.

## Publication handoff

The PDF filename prepared for this folder is `OPEX_Event_Study.pdf`. It contains the full report, all five embedded charts, and a front-sheet disclosure. The GitHub connection currently used for the project supports text-file publication but did not provide a usable binary-file upload action for this workflow; the PDF must be uploaded through GitHub's file uploader. **Do not insert a live PDF link until that path exists and is verified.**

The independent audit remains a separate future phase requiring the original workbook, event dates, prices and trade logs.
