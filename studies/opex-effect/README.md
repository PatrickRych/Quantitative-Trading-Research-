# Options-expiration effect — study note

**Question.** Are SPY returns before equity-options expiration associated with subsequent returns? How does the same method behave around VIX expiry?

The prepared report describes conditional and unconditional OLS regressions, six pre-event lookbacks, multiple forward horizons and hypothetical seven-trading-day holding periods. It reports equity OPEX observations in 2020–2025 and VIX expiry observations in 2004–2025. These results are *reported by the authoring workbook/report*, not independently replicated.

## Outstanding verification

- **Calendar reconciliation:** the report calls its sample 80 *monthly* equity-OPEX events from January 2020 through December 2025, a span of 72 calendar months. Inspect actual event dates, event eligibility and any additional expirations before treating 80 as verified.
- Validate each pre-event information cutoff, event-day entry, forward horizon, prices and dividend treatment.
- Compare equity OPEX and VIX expiry over a common sample as well as their separate original periods; differences in history preclude a direct causal control interpretation.
- Account for multiple lookbacks, horizons and conditioning choices; use untouched holdout/walk-forward data and sensitivity to exceptional events.
- Recompute return aggregation, overlapping trades, transaction costs and financing before describing any hypothetical P&L as implementable.
- A proposed gamma-hedging mechanism is a **hypothesis**, not demonstrated dealer-position evidence.

**Publication:** Editorially qualified PDF prepared offline, awaiting rights/privacy review. No report download is linked until its public upload is complete. Raw event logs and the original workbook were not supplied for replication.
