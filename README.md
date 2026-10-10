# Nike: DCF & Comparable Company Valuation

A five-year Excel valuation of Nike (NYSE: NKE) using unlevered discounted cash flow, operating scenarios, and comparable-company multiples. The analysis tests how much margin recovery is embedded in the reference share price.

**Project period:** May–September 2026, with an October 2026 model update.  
**Valuation reference:** October 9, 2026 market data; Nike's fiscal year ends May 31.  
**Units:** USD millions, except per-share values and ratios.

## Files and links

- **[Download the Excel model](https://github.com/prakharss9/nike_dcf_comps_valuation_model/blob/35ca6b2062092d9dbcaf2695a8923e518cb3e702/Nike%20DCF%20%26%20Comps%20Valuation%20Model.xlsx):** workbook with a WACC calculation, DCF, operating cases, peer multiples, and sensitivity analysis.
- **[Read the detailed analysis](https://gist.github.com/prakharss9/10cb0281c85aa2dcd756e27f49f91f61):** project write-up covering assumptions, the valuation bridge, and risks.

Download the workbook and open it in Microsoft Excel to inspect the formulas. This README assumes the file is uploaded at the repository root under its original filename, `NKE_DCF_Model_Final.xlsx`.

## Investment question

Does the reference price adequately reflect Nike's earnings recovery, or does it offer a meaningful margin of safety? The model isolates revenue growth, operating margins, the discount rate, and terminal growth as valuation drivers.

## Key results

| Scenario | Implied value per share | Versus $34.71 reference price | FY2031 EBIT margin |
|---|---:|---:|---:|
| Downside | $24.13 | -30% | 8.0% |
| Base | $35.17 | +1% | 11.0% |
| Upside | $44.77 | +29% | 13.5% |

**Conclusion:** Hold at the reference price under the modeled assumptions. The base case offers little upside, and the downside and upside cases show substantial sensitivity to the margin-recovery path.

The model's 25% downside / 50% base / 25% upside weighting produces a value of $34.81 per share. These probabilities are judgmental assumptions, not estimated likelihoods.

## Model structure

- **Summary:** valuation outputs and the investment conclusion.
- **Assumptions:** WACC inputs, balance-sheet adjustments, operating cases, and terminal assumptions.
- **DCF:** projected unlevered cash flows, discount factors, terminal value, enterprise-to-equity bridge, and exit-multiple cross-check.
- **Comps:** selected peer EV/EBITDA multiples and implied values.
- **Sensitivities:** WACC versus terminal growth and scenario comparisons.
- **Football Field:** tabular valuation ranges across methods; this sheet is not a plotted chart.

## Methodology

- **Operating forecast:** revenue and EBIT margins drive earnings; NOPAT, D&A, capital expenditures, and changes in working capital drive unlevered free cash flow.
- **Cost of capital:** CAPM estimates the cost of equity, combined with the assumed after-tax cost of debt using capitalization weights.
- **DCF:** forecast cash flows and a perpetuity-growth terminal value are discounted to the valuation reference date.
- **Equity bridge:** enterprise value is adjusted for debt, cash, and short-term investments, then divided by diluted shares.
- **Cross-checks:** peer EV/EBITDA multiples and a 12.0x terminal EBITDA multiple provide alternative valuation estimates.

## Selected assumptions

| Input | Value |
|---|---:|
| Risk-free rate | 5.24% |
| Equity risk premium | 5.00% |
| Beta | 1.04 |
| Pre-tax cost of debt | 5.80% |
| Tax rate | 20% |
| WACC | 9.66% |
| Terminal growth | 3.00% |
| Base-case FY2031 EBIT margin | 11.0% |
| Capital expenditures / revenue | 1.8% |

The beta comes from a 60-month return regression against SPY. The equity risk premium, cost of debt, terminal growth, and outer-year operating assumptions are modeling choices.

The FY2027 and FY2028 operating inputs were informed by consensus data. Later forecasts assume a gradual recovery rather than reproduce management guidance.

## Cross-checks and sensitivity

- **Peer multiple approach:** the selected peer median is about 10.0x EV/EBITDA, implying $31.38 per share when applied to FY2026 EBITDA.
- **Terminal multiple approach:** a 12.0x exit EBITDA multiple implies $40.74 per share.
- **Discount rate sensitivity:** a 50-basis-point WACC change moves base-case value by about $2.50–$3.00 per share.
- **Terminal dependence:** about 79% of base-case enterprise value comes from the discounted terminal value.

The methods should not be averaged mechanically. Their differences reflect distinct earnings bases, dates, growth expectations, and terminal assumptions.

## How to use

1. Open the workbook and review **Assumptions**.
2. Change blue input cells to test alternative growth, margins, discount rates, or terminal assumptions.
3. Set `Assumptions!B3` to `1` for base, `2` for downside, or `3` for upside.
4. Review **DCF** and **Summary** for updated formula-driven valuation outputs.
5. Evaluate how dependent the conclusion is on terminal value and margin recovery.

**Sensitivity limitation:** the sensitivity table and scenario snapshot are fixed outputs, not live Excel data tables. They do not automatically refresh after input changes.

## Data provenance and limitations

Financial statements, consensus estimates, prices, price histories, peer ratios, and macro inputs were obtained through Perplexity's finance data tools. Verify company inputs against original filings before professional use; the repository is not an audited financial-data source.

Peer multiples use each company's latest available fiscal year-end rather than one common market date. Some are several months old, so they are indicative cross-checks, not a current trading-comparables set.

The model simplifies seasonal cash flow using a stub-year adjustment and working capital using a revenue-change assumption. It does not include a fully linked three-statement forecast or comprehensive dilution and lease adjustments. Terminal growth and steady-state reinvestment should be evaluated together before relying on the output.

## Author and disclosure

**Prakhar Singh Sisodia**  
Boston University, Questrom School of Business | Finance & Banking  
[LinkedIn](https://linkedin.com/in/prakharsisodia)

Prepared with AI assistance as an academic learning project. Values are scenario outputs as of the stated reference date, not current price targets or investment advice.
