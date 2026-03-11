# Equity Research

Independent, long-form equity research built with structured analysis and real filing data. Each company in the coverage universe has a dedicated folder containing the full investment thesis, financial analysis, competitive positioning, and quarterly earnings updates.

## Coverage Universe

| Ticker | Company | Recommendation | Fair Value | Report Date | Link |
|--------|---------|---------------|------------|-------------|------|
| SU | Suncor Energy | HOLD | $56.00 | 2026-03-11 | [Full Report](Coverage/Suncor/README.md) |

## Repository Structure

```
Coverage/
  Suncor/
    README.md                  <- Investment thesis and equity research report
    Business Overview.md       <- Company and segment analysis
    Industry Scan.md           <- Competitive landscape
    Financial Deep Dive.md     <- Multi-year financial trends
    Moat Analysis.md           <- Competitive advantages assessment
    Management Review.md       <- Leadership and governance evaluation
    Valuation Check.md         <- Multiples, scenarios, and fair value
    Bear Case.md               <- Counter-thesis and risk analysis
    Decision Log.md            <- Investment decision journal
    Earnings/                  <- Quarterly earnings updates
    filings/                   <- Source documents (10-K, 10-Q, transcripts, proxies)
    CLAUDE.md                  <- AI analyst rules for this company
  TICKER/                      <- Template folder (copy for new coverage)
```

## Adding New Coverage

1. Copy the `Coverage/TICKER/` template folder and rename it to the company ticker (e.g., `AAPL`)
2. Add filings to the `filings/` subfolder: 10-K, 10-Q, earnings transcripts, proxy statements, investor presentations
3. Work through the analysis files in sequence: Business Overview, Industry Scan, Financial Deep Dive, Moat Analysis, Management Review, Valuation Check, Bear Case
4. Compile findings into the `README.md` as the final investment thesis
5. Add the company to the Coverage Universe table above

## Quarterly Maintenance

After each earnings release, add the new filing to `filings/` and create a quarterly update in the `Earnings/` folder. Refresh the Valuation Check after significant price moves.

## Research Standards

All analysis is sourced exclusively from company filings and public data. No fabricated numbers, no placeholder data, no training-data assumptions. Every metric is cited to its source document. See each company's `CLAUDE.md` for the full research discipline rules.
