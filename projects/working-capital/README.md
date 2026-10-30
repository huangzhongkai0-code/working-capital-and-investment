# Cash Conversion & Working Capital

Where could collection and inventory changes release cash?

## Role relevance
Treasury · Working capital · Finance operations

## Data
Apple FY2023–FY2025; scenarios explicitly labelled. Source: https://www.sec.gov/Archives/edgar/data/320193/000032019325000079/aapl-20250927.htm. Retrieved 2026-10-30.

## Method
Compute FY2025 DSO/DIO/DPO using average FY2024/FY2025 balances and a standardized 365-day convention. DSO uses total sales; DIO and DPO use total cost of sales as a proxy for purchases. Scenario reduces DSO by five days and DIO by three, with DPO unchanged. Translate days into a one-time cash release at FY2025 sales/cost levels.

## Findings
The simplified cash conversion cycle is -71.8 days. The stated improvement scenario releases $7.52bn once, not recurring profit.

- DSO 32.1 days
- CCC -71.8 days
- Scenario release $7.52bn

## Interpretation and limits
Vendor non-trade receivables are excluded. Total COGS includes services and is an imperfect inventory/purchases denominator. Credit sales and purchase volumes are unavailable. The scenario is a sensitivity, not an operational recommendation.

See [computed results](results.csv). Reproduce with `node analysis.mjs` from the repository root. This is an independent, AI-assisted portfolio case study, not employment experience or a company-issued forecast.
