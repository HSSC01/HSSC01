# Hon Sing Sam Chung – Institutional Finance & Investment Modelling

This repository curates a set of finance-focused modelling frameworks designed to mirror tools used in investment banking, private equity, and asset management.

## Focus Areas

- Macroeconomic and balance-sheet stress testing
- Private equity and leveraged buyout modelling
- M&A valuation and transaction analysis
- Portfolio construction and risk management
- Factor-based equity strategies

## Flagship Projects

### Macro-Financial Stress Testing
Scenario-based macro-financial stress testing framework for evaluating the impact of adverse macroeconomic conditions on bank balance sheets, credit losses, and capital adequacy.

Used to analyse:
- Conditional capital depletion under adverse macro scenarios
- Timing and magnitude of CET1 shortfalls
- System-level vulnerability to macro-financial shocks

  
→ Repository: `macro-financial-stress-testing`

### M&A Valuation Engine
Comprehensive corporate valuation framework for analysing acquisition targets and evaluating transaction economics across multiple valuation methodologies.

Used to analyse:
- Standalone enterprise value using trading comparables and precedent transactions
- Intrinsic firm value via multi-scenario discounted cash flow modelling
- Deal economics including control premiums, consideration structure, and accretion/dilution outcomes
- Sensitivity of valuation to key assumptions such as WACC, terminal value, and strategic synergies

→ Repository: `mna-valuation-engine`

## Project Index

| Repository | Domain | Description | Status |
|----------|------|------------|--------|
| macro-financial-stress-testing | Risk / Macro | Scenario-based macro-financial stress testing of bank balance sheets and capital adequacy under adverse macroeconomic conditions | Completed |
| mna-valuation-engine | Investment Banking | M&A valuation engine including DCF, comparable companies, precedent transactions | Completed |
| lbo-model-private-equity | Private Equity / LevFin | Leveraged buyout model covering sources & uses, debt tranches, cash sweep mechanics, and exit IRR / MOIC sensitivity | Planned |
| pe-operating-model | Private Equity | Operating model focused on revenue drivers, cost structure optimisation, working capital dynamics, and value creation levers | Planned |
| pe-portfolio-monitor | Private Equity | Portfolio company monitoring framework with KPI tracking, covenant surveillance, and cash-flow stress scenarios | Planned |
| equity-factor-strategies | Asset Management / Hedge Funds | Long/short equity factor strategies with transaction costs, drawdown analysis, and regime sensitivity | Planned |
| multi-asset-portfolio-engine | Portfolio Management | Multi-asset allocation framework using mean-variance optimisation, risk parity, volatility targeting, and stress testing | Planned |
| portfolio-risk-overlay | Portfolio Management / Quant | Execution and risk overlay system covering position sizing, drawdown controls, exposure limits, and capital allocation rules | Planned |


## How to Use

Each repository contains:
- A detailed README explaining financial intuition
- Clear assumptions and limitations
- Reproducible outputs
- Modular components suitable for extension

## Disclaimer

These projects are for educational and demonstration purposes only and do not constitute investment advice or reflect proprietary models of any institution.
