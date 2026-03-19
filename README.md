# Hon Sing Sam Chung – Institutional Finance & Quantitative Investment Systems

This repository presents a set of finance-focused modelling frameworks spanning **quantitative asset management, macro-financial risk, and corporate valuation**, designed to reflect institutional investment workflows.

The projects are structured to demonstrate how **alpha signals, portfolio construction, and risk frameworks** interact within real-world investment systems.

---

## Focus Areas

- Quantitative asset pricing and systematic trading strategies  
- Multi-asset portfolio construction and risk management  
- Macroeconomic and balance-sheet stress testing  
- Private equity and leveraged buyout modelling  
- M&A valuation and transaction analysis  

---

## Flagship Projects

### Volatility-Conditioned Momentum Engine (Multi-Asset)
A multi-asset systematic trading framework that conditions time-series momentum exposure on volatility regimes, extending a regime-dependent asset pricing insight into a fully implemented trading system.

Used to analyse:
- Regime-dependent behaviour of momentum (continuation vs reversal)
- Cross-asset signal robustness (equities, bonds, commodities, FX)
- Transaction cost sensitivity (0, 2, 10 bps) and turnover dynamics
- Crisis-period performance (GFC, COVID, 2022 inflation bear)
- Statistical significance (HAC inference) and factor exposure (CAPM)

→ Repository: `volatility-conditioned-momentum-engine`

---

### Macro-Financial Stress Testing
Scenario-based macro-financial stress testing framework for evaluating the impact of adverse macroeconomic conditions on bank balance sheets, credit losses, and capital adequacy.

Used to analyse:
- Conditional capital depletion under adverse macro scenarios  
- Timing and magnitude of CET1 shortfalls  
- System-level vulnerability to macro-financial shocks  

→ Repository: `macro-financial-stress-testing`

---

### M&A Valuation Engine
Comprehensive corporate valuation framework for analysing acquisition targets and evaluating transaction economics across multiple valuation methodologies.

Used to analyse:
- Standalone enterprise value using trading comparables and precedent transactions  
- Intrinsic firm value via multi-scenario discounted cash flow modelling  
- Deal economics including control premiums, consideration structure, and accretion/dilution outcomes  
- Sensitivity of valuation to key assumptions such as WACC, terminal value, and strategic synergies  

→ Repository: `mna-valuation-engine`

---

## Project Index

| Repository | Domain | Description | Status |
|----------|------|------------|--------|
| volatility-conditioned-momentum-engine | Quant / Asset Management | Volatility-conditioned multi-asset momentum engine with regime switching, transaction costs, crisis analysis, and statistical validation | Completed |
| macro-financial-stress-testing | Risk / Macro | Scenario-based macro-financial stress testing of bank balance sheets and capital adequacy under adverse macroeconomic conditions | Completed |
| mna-valuation-engine | Investment Banking | M&A valuation engine including DCF, comparable companies, precedent transactions | Completed |
| multi-asset-portfolio-engine | Portfolio Management | Multi-asset portfolio construction framework covering mean-variance optimisation, risk parity, volatility targeting, and stress testing | In progress |
| lbo-model-private-equity | Private Equity / LevFin | Leveraged buyout model covering sources & uses, debt tranches, cash sweep mechanics, and exit IRR / MOIC sensitivity | Planned |
| pe-operating-model | Private Equity | Operating model focused on revenue drivers, cost structure optimisation, working capital dynamics, and value creation levers | Planned |
| pe-portfolio-monitor | Private Equity | Portfolio company monitoring framework with KPI tracking, covenant surveillance, and cash-flow stress scenarios | Planned |
| equity-factor-strategies | Asset Management / Hedge Funds | Long/short equity factor strategies with transaction costs, drawdown analysis, and regime sensitivity | Planned |
| portfolio-risk-overlay | Portfolio Management / Quant | Execution and risk overlay system covering position sizing, drawdown controls, exposure limits, and capital allocation rules | Planned |

---

## System Architecture (Conceptual)

The projects collectively reflect a layered investment framework:

- **Signal Layer**  
  Systematic strategies (e.g. volatility-conditioned momentum) generating directional views  

- **Portfolio Layer**  
  Multi-asset allocation, weighting schemes, and diversification  

- **Risk & Execution Layer**  
  Transaction costs, drawdown control, and capital allocation constraints  

This structure mirrors how institutional investment systems are designed in practice.

---

## How to Use

Each repository contains:
- A detailed README explaining financial intuition  
- Clear assumptions and limitations  
- Reproducible outputs (CSV and visual diagnostics)  
- Modular components suitable for extension  

---

## Disclaimer

These projects are for educational and demonstration purposes only and do not constitute investment advice or reflect proprietary models of any institution.
