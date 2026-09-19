# QUANT Macro Rotation — model note

**Purpose.** A reported Excel research framework that compares cross-asset price ratios and market spreads, constructs Growth / Inflation / Credit / Stress composites, assigns a macro-quadrant label, and compares implied with realized volatility for selected instruments.

The prepared report describes 19 cross-asset series and a separate implied-versus-realized-volatility analysis. Any model snapshot from May 2026 is historical and should not be read as a live regime classification. The corresponding `QUANT_Macro_Rotation.xlsx` workbook was not supplied in this batch.

## Verification priorities

- Reconcile dates across different instruments, especially when market calendars and missing prices differ.
- Trace and investigate the report's flagged IWF/IWD and DBC/TLT price-feed anomalies against primary source data.
- Verify ratio construction and distinguish proxy ETF ratios from breakeven inflation derived from Treasury yields.
- Label `implied volatility minus realized volatility` as a **volatility spread**; a variance premium requires a consistent squared-volatility definition.
- Independently audit exact formulas, unit conventions and data dependencies in the workbook.
- The report does not provide established out-of-sample regime-conditional trading performance; do not imply predictive validation.

**Publication:** Editorially qualified PDF prepared offline, awaiting rights/privacy review. No report download is linked until public upload is complete. Original workbook and input data were not provided for replication.
