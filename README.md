# Stock Research with Claude — Setup Template

Based on the [BearBull guide](https://www.bearbull.io/blog/Guide/Research-With-Claude-AI).

## How to Use

### 1. Copy the Template
For each new stock, copy the entire `Research/TICKER/` folder and rename `TICKER` to the actual ticker symbol (e.g., `AAPL`, `MSFT`).

### 2. Add Filings
Place company filings in the `filings/` subfolder:
- 10-K (annual report)
- 10-Q (quarterly reports)
- Earnings call transcripts
- Proxy statements (DEF 14A)
- Investor presentations

### 3. Run Analysis in Claude Code
Open a terminal in the stock's folder and start Claude Code. The `CLAUDE.md` research rules load automatically.

Run each step sequentially using the slash commands:
```
/01-business-overview
/02-industry-scan
/03-financial-deep-dive
/04-moat-analysis
/05-management-review
/06-valuation-check
/07-bear-case
```

### 4. Quarterly Maintenance
After each earnings release, add the new report/transcript to `filings/` and run:
```
/08-earnings-update
```

### 5. Decision Journal
When making investment decisions:
```
/09-decision-entry
```

## Folder Structure
```
Research/
  TICKER/
    CLAUDE.md                  ← Research rules (auto-loaded)
    Business Overview.md       ← Step 1
    Industry Scan.md           ← Step 2
    Financial Deep Dive.md     ← Step 3
    Moat Analysis.md           ← Step 4
    Management Review.md       ← Step 5
    Valuation Check.md         ← Step 6
    Bear Case.md               ← Step 7
    Decision Log.md            ← Step 9
    Earnings/
      TEMPLATE - Quarterly Update.md  ← Step 8 template
    filings/                   ← Drop 10-K, 10-Q, transcripts here
    .claude/
      commands/                ← Slash commands for each step
```

## Analysis Sequence
- **First-time analysis**: Steps 1–7 complete, then Step 9
- **Quarterly maintenance**: Step 8 after each earnings release
- **Price moves**: Optionally refresh Step 6 after significant price changes
- **Long-term value**: The Decision Log builds a historical record of thesis evolution
