# QUANT Lens — model note

**Purpose.** A reported single-ticker analysis workbook integrating volatility-state estimation, four-category regime labeling, trend indicators, options-pricing comparisons, rolling regression diagnostics and hedge calculations.

The report describes a two-state volatility Markov model, regime-conditioned distributions, a trend scorecard, IV/RV/skew measures, and options scenario tools. It is broader than a standalone trend-following study. Any ticker price or regime label in the report is a dated historical snapshot, not a live quote. The original workbook (`QUANT_Lense.xlsx`, as named in the report) was not submitted.

## Verification priorities

- The reported Markov method uses **retrospective smoothed** state probabilities and full-sample calibration. Historical smoothed labels may use future information and cannot be treated as available trading signals without causal, walk-forward reconstruction.
- Distinguish probability of an option expiring in the money from probability of touching a strike during its life; verify risk-neutral versus real-world probability assumptions.
- Reconcile the report's IV-versus-RV arithmetic, volatility-versus-variance terminology, options prices and hedge-risk formulas.
- Check missing or stale vendor-supplied options data and how unavailable feeds propagate to the dashboard.
- Validate the sample and any regime-conditional Sharpe ratios, particularly categories with very few observations, against the original workbook.
- Remove unrelated drafting material from the report edition before any release (the prepared offline edition states this has been done; visually check the final PDF).

**Publication:** Editorially qualified PDF prepared offline, awaiting rights/privacy review. No report download is linked until public upload is complete. The workbook and inputs were not provided for independent replication.
