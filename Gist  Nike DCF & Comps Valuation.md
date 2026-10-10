# Nike (NKE): DCF & Comparable Company Valuation

**Independent academic project** | Boston University, Questrom | Market data as of Oct 9, 2026 | $ in millions except per share

> Illustrative exercise, not investment advice. Cost of debt, equity risk premium, terminal growth and the outer-year margin recovery path are my own assumptions.

## Summary
**Recommendation: HOLD.** Nike's operating margin fell from 12.3% in FY2024 to 8.2% in FY2026 and the stock trades at $34.71 (52-week range $31.97 to $70.44). My base-case DCF values it at **$35.17**, within 2% of the market price, so the market already prices in a margin recovery to about 11% by FY2031.

| Case | Value per share | vs. $34.71 | FY2031 EBIT margin |
|---|---|---|---|
| Downside | $24.13 | -30% | 8.0% |
| **Base** | **$35.17** | **+1%** | **11.0%** |
| Upside | $44.77 | +29% | 13.5% |
| Probability-weighted (25/50/25) | $34.81 | +0% | |

I would turn Buy below roughly $29 (about 20% upside to the base case) or on evidence of gross-margin recovery.

## Cost of capital
| Input | Value |
|---|---|
| Risk-free rate (10Y UST, Oct 9, 2026) | 5.24% |
| Equity risk premium (assumption) | 5.00% |
| Beta (60-month regression vs. SPY) | 1.04 |
| Cost of equity | 10.44% |
| Pre-tax cost of debt (assumption) | 5.80% |
| Tax rate | 20% |
| Debt / equity weights | 13.4% / 86.6% |
| **WACC** | **9.66%** |

## Base-case projections
| | FY2027E | FY2028E | FY2029E | FY2030E | FY2031E |
|---|---|---|---|---|---|
| Revenue | 42,923 | 43,107 | 44,832 | 47,073 | 49,427 |
| EBIT | 2,404 | 2,845 | 3,811 | 4,707 | 5,437 |
| EBIT margin | 5.6% | 6.6% | 8.5% | 10.0% | 11.0% |
| Unlevered FCF | 2,189 | 2,176 | 2,791 | 3,452 | 4,020 |

FY2027 and FY2028 revenue ($42.9B and $43.1B) and margins follow analyst consensus (EBIT derived from consensus EBITDA less D&A). Outer-year growth (4% to 5%) and the margin recovery path are my assumptions. D&A is 1.6% and capex 1.8% of revenue; change in NWC is 10% of the change in revenue.

## Valuation bridge (base case)
| | $mm |
|---|---|
| PV of FCF (FY2027 stub to FY2031) | 10,467 |
| PV of terminal value (3.0% growth) | 40,506 |
| **Enterprise value** | **50,973** |
| Less: debt | (7,942) |
| Plus: cash & short-term investments | 9,027 |
| **Equity value** | **52,058** |
| Diluted shares (mm) | 1,480 |
| **Value per share** | **$35.17** |

Terminal value is 79% of enterprise value, and the implied terminal EV/EBITDA is 10.0x.

## Cross-checks
- **Exit-multiple method (12.0x FY2031 EBITDA):** $40.74 per share. The gap versus the perpetuity-growth method shows how much the answer depends on terminal assumptions.
- **Peer EV/EBITDA comps:** Lululemon, Deckers, V.F. Corp, Columbia, Birkenstock, On Holding and Amer Sports. The median is 10.0x; applied to Nike's FY2026 EBITDA of $4,544mm it implies about **$31.38** per share (25th to 75th percentile: $28.42 to $50.51).
- **Caveat:** peer multiples are at each company's latest fiscal year-end (some 6 to 12 months old) because only annual ratio data was available. Crocs, Under Armour, adidas and PUMA were excluded (distorted or negative EBITDA, or no ratio data pulled).

## Sensitivity: base-case value per share
**WACC vs. terminal growth**

| WACC \ g | 2.0% | 2.5% | 3.0% | 3.5% | 4.0% |
|---|---|---|---|---|---|
| **8.66%** | $36.28 | $38.72 | $41.60 | $45.03 | $49.20 |
| **9.16%** | $33.65 | $35.72 | $38.12 | $40.95 | $44.33 |
| **9.66%** | $31.37 | $33.14 | $35.17 | $37.54 | $40.32 |
| **10.16%** | $29.37 | $30.90 | $32.64 | $34.64 | $36.96 |
| **10.66%** | $27.61 | $28.93 | $30.44 | $32.15 | $34.11 |

- +/-50bp of WACC moves the value by about $2.50 to $3.00 per share.
- Each 1 point of FY2031 EBIT margin is worth about $3 per share.

## Key risks
Tariffs and supply chain costs, China demand, wholesale vs. direct-to-consumer mix, and the pace of gross-margin recovery.

## Data sources
FY2023 to FY2026 financials, consensus estimates, peer ratios, quotes and price history from Perplexity finance data; 10-year Treasury yield from U.S. Treasury data as of Oct 9, 2026.

## Files
The full Excel model (live DCF, scenario switch, comps, sensitivities, football field) is available on request: prakhars@bu.edu.

*Author: Prakhar Singh Sisodia, Boston University (Questrom), Finance & Banking. [LinkedIn](https://linkedin.com/in/prakharsisodia)*
