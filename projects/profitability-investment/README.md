# Profitability & Capital Budgeting

How can reported margins inform a clearly bounded investment case?

## Role relevance
Commercial finance · Investment appraisal

## Data
Apple FY2023–FY2025; scenarios explicitly labelled. Source: https://www.sec.gov/Archives/edgar/data/320193/000032019325000079/aapl-20250927.htm. Retrieved 2026-10-30.

## Method
Calculate reported Products and Services gross margins. Separately model a hypothetical five-year project with initial spend equal to 1% of FY2025 reported capex, annual after-tax cash inflow equal to 30% of that spend, 10% discount rate, no terminal value and no additional working capital. Compute NPV, bisection IRR and a 3×3 discount-rate/cash-flow sensitivity.

## Findings
Reported product gross margin is 36.77% versus 75.41% for services. The hypothetical project NPV is $0.02bn and IRR 15.24%.

- Products GM 36.77%
- Services GM 75.41%
- Illustrative IRR 15.24%

## Interpretation and limits
Gross margin is not contribution margin: public COGS does not separate variable and fixed costs. No SKU break-even is claimed. Project inflows, discount rate and life are assumptions; only the scale anchor comes from real capex. This is not an actual Apple project.

See [computed results](results.csv). Reproduce with `node analysis.mjs` from the repository root. This is an independent, AI-assisted portfolio case study, not employment experience or a company-issued forecast.
