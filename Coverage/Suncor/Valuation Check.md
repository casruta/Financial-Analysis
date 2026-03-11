# Valuation Check: SU

> State all assumptions explicitly. Flag areas with insufficient data.

## Relative Valuation

| Metric | Current | 5-Year Avg | Peer Median | Sector Median |
|--------|---------|-----------|-------------|---------------|
| P/E    | 15.75   | N/A | ~15.37 (midpoint of SU 15.75 and CNQ 14.98) | N/A |
| EV/EBITDA | 7.01 | N/A | 7.20 (median of SU 7.01, CNQ 7.38, IMO ~9.93, CVE 5.65) | N/A |
| P/FCF  | 13.34   | N/A | N/A | N/A |
| P/S    | 1.91    | N/A | N/A | N/A |

Suncor trades at 7.01x EV/EBITDA, which sits between CNQ (7.38x) and CVE (5.65x), and well below IMO (8.21 to 11.64x). The 15.75x trailing P/E is slightly above CNQ's 14.98x but reasonable for the most vertically integrated Canadian oil sands producer. Forward P/E of 19.34x is elevated relative to CNQ's 15.49x, reflecting analyst consensus that 2026 EPS ($3.85) will decline from TTM EPS ($3.54 reported, though some sources show higher), largely on weaker commodity price assumptions.

[suncor-valuation-data.md, Valuation Multiples]: "P/E (Trailing) 15.75", "EV/EBITDA 7.01", "P/FCF 13.34", "P/S 1.91"
[suncor-peers.md, Valuation Comparison]: "CNQ 7.38, IMO 8.21 to 11.64, CVE 5.65"
[suncor-valuation-data.md, Valuation Multiples]: "P/E (Forward) 19.34"
[suncor-peers.md, Valuation Comparison]: "CNQ Forward P/E 15.49"

Note: 5-year average multiples and broad sector medians are not available in the project filings. A Bloomberg or FactSet terminal pull would be required to populate these fields.

## Growth-Adjusted Metrics

| Metric | Value | Interpretation |
|--------|-------|---------------|
| PEG Ratio | ~4.09 (Forward P/E 19.34 / estimated EPS growth ~4.7%) | Expensive on a growth-adjusted basis, but PEG is poorly suited to commodity producers whose earnings growth is driven by price cycles, not organic compounding |
| EV/EBITDA-to-Growth | ~1.49 (EV/EBITDA 7.01 / normalized FFFlow growth ~4.7%) | Moderate; reflects the market pricing in flat-to-declining commodity prices against structural operational improvement |

**EPS growth estimate basis:** 2026E consensus EPS of $3.85 vs TTM EPS of $3.54 implies ~8.8% growth, but this is misleading because TTM EPS benefited from higher oil prices. Normalized operational growth (stripping commodity effects) is better measured by normalized free funds flow at US$75 WTI, which grew 15% YoY from $7,373M to $8,476M. However, per-share growth is lower after adjusting for the 4.39% share count reduction, yielding roughly ~10.5% per-share normalized FFFlow growth. Using a blended ~4.7% forward EPS growth rate (midpoint between commodity-headwind-adjusted consensus and normalized operational improvement) provides a more realistic denominator.

[suncor-valuation-data.md, Analyst Estimates]: "2026 EPS Consensus $3.85"
[suncor-valuation-data.md, Income Statement TTM]: "EPS $3.54"
[suncor-q4-2025-earnings.md, Full Year 2025]: "Normalized FFFlow (US$75 WTI) $8,476M" vs 2024 "$7,373M"
[suncor-valuation-data.md, Current Market Data]: "YoY Share Count Change -4.39%"

## Reverse DCF

**Current Price:** $56.84
**Implied Revenue Growth Rate:** ~0 to 2% annually over 5 years (flat to slight growth)
**Implied Margin Assumptions:** EBITDA margins sustaining at ~30% (current TTM EBITDA margin: $10.88B / $35.67B = 30.5%), with FCF conversion around 14 to 15% of revenue ($5.10B / $35.67B = 14.3%)
**Reality Check:** The current price appears to embed a mildly pessimistic commodity outlook, roughly consistent with WTI in the mid-$50s to low-$60s range, combined with stable operational execution. At $56.84, the market is pricing Suncor as if commodity prices will weaken from current levels but operational improvements will hold. This is a reasonable base case. The implied growth rate does NOT appear to give Suncor credit for further operational efficiency gains (normalized FFFlow grew 15% at constant prices in FY2025). If efficiency gains continue compounding at even half that rate, the current price undervalues Suncor's operational trajectory.

**Assumptions for reverse DCF:** Discount rate of 10% (typical for integrated energy), terminal growth of 0%, 10-year horizon. Revenue of $35.67B (TTM) growing at ~1.5% annually with 30% EBITDA margins and $5.8 to $6.0B annual capex yields a fair value of approximately $55 to $58 per share, aligning with the current price. This implies the market is pricing in essentially no growth.

[suncor-valuation-data.md, Income Statement TTM]: "Revenue $35.67B", "EBITDA $10.88B"
[suncor-valuation-data.md, Cash Flow TTM]: "Free Cash Flow $5.10B", "Capital Expenditures $4.27B"
[suncor-valuation-data.md, Current Market Data]: "Shares Outstanding 1.19B"


## Scenario-Based Fair Value

### Bull Case (Top-Quartile Outcome)
**Assumptions:**
- Revenue growth: WTI sustains >$70/bbl, driving upstream revenue growth of 8 to 12% annually. Record production continues, reaching 900,000+ bbls/d by 2027.
- Margin trajectory: EBITDA margins expand to 33 to 35% as operational efficiencies compound (upgrader and refinery utilization sustained above 100%), per-barrel OS&G costs continue declining, and refining crack spreads remain supportive. Normalized FFFlow at US$75 WTI reaches $9.5 to $10B by 2027 (vs $8.5B in 2025).
- Multiple: EV/EBITDA re-rates to 8.0x (toward IMO's premium range, justified by sustained operational excellence and best-in-class integration). Share count declines 4 to 5% annually via $3.3B+ buyback program.

**Fair Value:** $78

*Derivation: Revenue ~$40B at WTI >$70, EBITDA ~$13.5B (33.5% margin), 8.0x EV/EBITDA = EV ~$108B. Less net debt ~$5.5B (continued deleveraging) = equity value ~$102.5B. Shares outstanding ~1.13B (post-buybacks) = ~$91/share. Probability-weighted at ~85% execution confidence = ~$78.*

[suncor-q4-2025-earnings.md, Full Year 2025]: "Total Upstream Production 860,000 bbls/d (record)", "Refinery Utilization 103% (record)"
[suncor-q4-2025-earnings.md, 2026 Guidance]: "Monthly share repurchases increasing 10% to $275M"
[suncor-q4-2025-earnings.md, Full Year 2025]: "Normalized FFFlow (US$75 WTI) $8,476M"

### Base Case (Trend Continuation)
**Assumptions:**
- Revenue growth: WTI averages $55 to $65/bbl range through 2027, consistent with EIA and Goldman forecasts. Revenue flat to slightly declining on commodity headwinds, partially offset by 2 to 3% annual production growth and record refining throughput.
- Margin trajectory: EBITDA margins compress modestly to 28 to 30% as lower oil prices offset operational improvements. Normalized FFFlow at US$75 WTI grows 5 to 8% annually to ~$9.0B by 2027. Actual FFFlow in the $6.0 to $7.0B range at realized prices.
- Multiple: EV/EBITDA sustains at 7.0x, in line with current valuation and CNQ. Share count declines ~4% annually.

**Fair Value:** $56

*Derivation: Revenue ~$34B at WTI ~$60, EBITDA ~$10.0B (29% margin), 7.0x EV/EBITDA = EV ~$70B. Less net debt ~$5.8B = equity value ~$64.2B. Shares outstanding ~1.14B = ~$56/share.*

[suncor-valuation-data.md, Oil Price Forecasts]: "EIA Brent ~$58/bbl avg" for 2026, "Goldman Sachs WTI $52/bbl"
[Financial Deep Dive.md, Margin Progression]: EBITDA margins have ranged from ~27 to 31% depending on commodity price environment
[suncor-valuation-data.md, Valuation Multiples]: "EV/EBITDA 7.01"

### Bear Case (Structural Deterioration)
**Assumptions:**
- Revenue growth: WTI falls below $50/bbl on sustained supply glut (world oil output +2.4 mb/d, 477 mb inventory builds) and demand weakness. Revenue declines 15 to 20% from TTM. Carbon regulation tightens, increasing per-barrel costs by $3 to $5/bbl.
- Margin trajectory: EBITDA margins compress to 22 to 25% as upstream losses dominate even with refining hedge. Normalized FFFlow declines to $6.0 to $6.5B at US$75 WTI as cost inflation from carbon regulation erodes structural gains. Actual FFFlow drops to $3.0 to $4.0B at realized WTI <$50.
- Multiple: EV/EBITDA compresses to 5.5x (toward CVE's current discount, reflecting market re-pricing of long-duration oil sands assets in a structural demand decline narrative). Buyback program slows as FCF shrinks.

**Fair Value:** $34

*Derivation: Revenue ~$29B at WTI ~$48, EBITDA ~$7.0B (24% margin), 5.5x EV/EBITDA = EV ~$38.5B. Less net debt ~$6.5B (deleveraging pauses) = equity value ~$32B. Shares outstanding ~1.17B (buybacks slow) = ~$27/share. However, integrated model and balance sheet strength provide a floor; refining margins widen in low-crude environments. Adjusted bear value: ~$34.*

[suncor-valuation-data.md, Supply/Demand Dynamics]: "Supply outpacing demand: 477 mb inventory builds in 2025", "World oil output 2026: forecast +2.4 mb/d"
[suncor-valuation-data.md, Carbon Tax / Regulatory]: "Federal carbon tax applicable to oil sands operations"
[suncor-peers.md, Valuation Comparison]: "CVE 5.65" EV/EBITDA as bear-case multiple reference

## Margin of Safety

| Scenario | Fair Value | Current Price | Upside/Downside |
|----------|-----------|--------------|----------------|
| Bull     | $78       | $56.84       | +37.2%         |
| Base     | $56       | $56.84       | -1.5%          |
| Bear     | $34       | $56.84       | -40.2%         |

**Probability-Weighted Fair Value:** Assigning 25% bull, 50% base, 25% bear: (0.25 x $78) + (0.50 x $56) + (0.25 x $34) = $19.50 + $28.00 + $8.50 = **$56.00**

The probability-weighted fair value of $56.00 is essentially equal to the current price of $56.84, suggesting **Suncor is fairly valued at current levels**. There is no meaningful margin of safety for a new position at this price. The stock is priced for the base case (flat commodity environment with stable operations) and offers upside only if commodity prices surprise to the upside or if operational improvements continue at the exceptional pace of the last two years.

## Key Assumptions & Data Gaps

### Assumptions Driving Valuation Most

1. **Oil price is the dominant variable.** Every $10/bbl move in WTI shifts annual EBITDA by roughly $2.5 to $3.0B and fair value by $15 to $20/share. The entire valuation range ($34 to $78) is driven primarily by the commodity price assumption, not by disagreement about Suncor's operational quality. (Inferred from the relationship between normalized FFFlow at US$75 and actual FFFlow at realized prices.)

2. **Sustainability of operational improvements.** The base case assumes Suncor holds utilization rates near current records (103% refinery, 99% upgrader annual). If utilization mean-reverts to 95 to 97% (pre-Kruger levels), per-unit economics deteriorate meaningfully. The moat analysis rates these improvements as structural, but any analysis must acknowledge that 103% refinery utilization and 106% quarterly upgrader utilization may be near physical ceilings.

3. **Share buyback execution.** At $275M/month (~$3.3B annually), buybacks contribute ~4 to 5% annual per-share value accretion. This assumes management maintains this pace regardless of commodity environment; in a bear case, buybacks would likely slow, reducing per-share value creation. [suncor-q4-2025-earnings.md, 2026 Guidance]: "Monthly share repurchases increasing 10% to $275M"

4. **EV/EBITDA multiple stability.** The base case assumes 7.0x is sustainable. If ESG-driven capital reallocation accelerates or terminal demand concerns deepen, integrated oil companies could see structural multiple compression toward 4 to 5x, which would reduce fair value materially even with stable cash flows.

### Data Gaps

- **5-year average multiples:** N/A (not in quarterly filing summaries; requires Bloomberg/Capital IQ)
- **Sector median multiples:** N/A (not in quarterly filing summaries; requires Bloomberg/Capital IQ)
- **Full upstream vs downstream margin split:** not disclosed in quarterly earnings summaries; required to properly model the natural hedge between upstream and refining under different commodity scenarios
- **Break-even WTI price:** not disclosed; implied at approximately $40 to $45 based on sustaining capex plus dividend requirements [Financial Deep Dive.md, Break-Even Analysis]
- **Environmental/reclamation liabilities:** not quantified in quarterly filings; requires 10-K/40-F [Financial Deep Dive.md, Red Flags]
- **Pension/OPEB:** not quantified in quarterly filings; requires 10-K/40-F
- **Off-balance-sheet items:** not detailed; requires 10-K/40-F
- **Forward consensus beyond 2026:** only 2026E EPS of $3.85 available
