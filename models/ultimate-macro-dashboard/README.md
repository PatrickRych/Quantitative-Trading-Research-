# Ultimate Macro Dashboard — model note

**Purpose.** A reported Excel framework for aligning macroeconomic time series to a weekly grid, constructing rolling standardized factors, generating four macro-regime weights, and analyzing historical asset returns, PCA and regression attribution.

The prepared report describes FRED-sourced indicators, a five-layer pipeline and a four-state Goldilocks / Reflation / Stagflation / Deflation model. The historical model values are dated; they are not current macro readings. This note describes the **reported implementation**, not a verified or downloadable workbook.

## Verification priorities

- Check historical data **vintages and release timestamps**; using today's revised FRED values can introduce look-ahead bias even when rolling z-score windows end at the preceding row.
- Reconcile report dates and sample counts, and review last-observation-carried-forward behavior, observation staleness and missing-data rules.
- Check signal lag, overlapping 4- and 13-week forward outcomes, rare-regime sample size and execution assumptions.
- Verify PCA fit dates and regression chronology; full-sample PCA can create retrospective information leakage in historical analyses.
- Softmax outputs are normalized model weights, **not automatically statistically calibrated event probabilities**.
- Recompute reported metrics against the original workbook and data before asserting validation.

**Publication:** Editorially qualified PDF prepared offline, awaiting rights/privacy review. No report download is linked until public upload is complete. Original workbook and raw data were not provided for independent replication.
