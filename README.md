# Quantitative Trading Research

**Independent Excel-based research into market regimes, options behavior, cross-asset relationships, and calendar effects.**

I develop models and studies to make trading research more systematic: define a hypothesis, organize and align the data, make calculations transparent, investigate the results, and document where the work may fail. This repository is a reading room for the research and a roadmap toward reproducible Excel and code releases.

> **Publication status — research index available; PDF reports pending release clearance.** Five reports have been prepared, but their underlying workbooks and data have not been independently verified. The PDFs will be linked here only after third-party redistribution rights and final visual/privacy review are confirmed. This repository contains **no private trading-system draft**.

## Backtested research studies

| Study | Research question | Study period (as reported) | Read the note |
|---|---|---|---|
| Options-expiration effect | Are SPY returns before equity-options expiry associated with subsequent returns? How does the comparison differ around VIX expiry? | Equity OPEX 2020–2025; VIX expiry 2004–2025 | [Study note](studies/opex-effect/README.md) |
| Stock–bond reversal & window dressing | Do SPY/TLT returns exhibit reversal or continuation around month boundaries? | 2004–2025 | [Study note](studies/stock-bond-calendar/README.md) |

These are historical, in-sample analyses. Published statistics in the source reports are **not independently replicated**, and the tests do not establish a live trading edge. Notably, the options-expiration study's event count and the stock–bond study's portfolio accounting and execution assumptions need reconciliation.

## Model research reports

| Model | What it is intended to analyze | Read the note |
|---|---|---|
| Ultimate Macro Dashboard | Weekly macro-data alignment, factor z-scores, four-state regime weights, conditional historical analysis and PCA | [Model note](models/ultimate-macro-dashboard/README.md) |
| QUANT Macro Rotation | Cross-asset spread monitoring, macro composites, quadrant classifications and IV/RV comparisons | [Model note](models/macro-rotation/README.md) |
| QUANT Lens | Single-ticker volatility regimes, trend measures, options analysis, regression diagnostics and hedge calculations | [Model note](models/quant-lens/README.md) |

These notes describe **reported workbook implementations**, not downloadable or independently tested software. The original Excel workbooks were not included with these five reports. Historical model readings must not be treated as live signals.

## How I structure research

1. Specify the hypothesis and make the signal's information cutoff explicit.
2. Align dates and distinguish missing or stale data from observations genuinely equal to zero.
3. Define formulas, position sizing, execution timing, financing and costs.
4. Report negative tests, sensitivity to parameter choices, and limitations alongside positive findings.
5. Separate in-sample exploration from out-of-sample, walk-forward and live validation.

## Reproducibility and publication status

- [x] Research index and study/model notes organized.
- [x] Five editorially qualified report editions prepared offline.
- [ ] Confirm redistribution rights for any third-party charts, data and excerpts and visually inspect each PDF.
- [ ] Publish the five PDF reports and enable direct download links.
- [ ] Audit calculations using source workbooks/data; document revisions and original publication dates.
- [ ] Add reproducible Excel demonstrations or scripts as permissions and verification allow.

**Research disclaimer:** Historical observations and exploratory models are not investment advice, audited performance, or evidence that an anomaly will persist. No live trade recommendation is made by this repository.
