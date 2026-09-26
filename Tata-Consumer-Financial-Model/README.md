# Tata Consumer Products — Equity Research & Valuation Model

## Overview

This project is an equity research and valuation model built for
**Tata Consumer Products Limited (TATACONSUM)**.

The model combines historical financial analysis, financial forecasting,
cost of capital estimation, intrinsic valuation, relative valuation and
risk analysis into a single integrated Excel model.

The project was built to develop a practical understanding of how
financial statements are transformed into forecasts and ultimately into
a valuation framework.

---

## Objective

The main objectives of this project were to:

- Analyze historical financial performance
- Understand the relationship between the three financial statements
- Perform financial ratio and common-size analysis
- Forecast key operating metrics
- Estimate the company's cost of capital
- Calculate intrinsic value using DCF
- Perform comparable-company valuation
- Analyze valuation sensitivity
- Understand equity risk and Value at Risk

---

# Model Structure

The model follows the following broad workflow:

**Data Collection → Historical Analysis → Ratio Analysis → Forecasting
→ WACC → Intrinsic Growth → DCF → Relative Valuation → Risk Analysis**

---

## 1. Historical Financial Analysis

Historical financial information was organized into an integrated
financial statement structure.

The model includes:

- Profit & Loss Statement
- Balance Sheet
- Cash Flow Statement
- Quarterly financial information
- Historical financial statement data
- Raw financial statement data

Key financial metrics analyzed include:

- Revenue
- EBITDA
- EBIT
- Profit Before Tax
- Net Profit
- EPS
- Working Capital
- Debt
- Cash Flow from Operations
- Capital Expenditure
- Free Cash Flow

---

## 2. Ratio Analysis

The model contains a detailed ratio analysis covering profitability,
efficiency, liquidity and cash-flow related metrics.

Examples include:

- Profit margins
- Return ratios
- Asset turnover
- Debtor turnover
- Creditor turnover
- Inventory turnover
- Fixed asset turnover
- Capital turnover
- Debtor days
- Payable days
- Inventory days
- Cash Conversion Cycle
- CFO/Sales
- CFO/Total Assets
- CFO/Total Debt

Historical averages and medians are also calculated for several metrics.

---

## 3. Common Size Analysis

Common-size financial statements were prepared to analyze financial
statement items as percentages of relevant totals.

This helps identify changes in:

- Cost structure
- Profitability
- Asset composition
- Liability composition
- Capital structure

---

## 4. Forecasting

The model forecasts important operating metrics using historical trends.

Forecasting includes:

- Revenue / Sales
- EBITDA
- EPS
- Growth rates

Historical observations are used to generate forward estimates using
trend-based forecasting techniques.

---

## 5. Beta & Regression Analysis

The model estimates Tata Consumer's equity beta using historical
monthly returns and market returns.

The regression analysis includes:

- Tata Consumer monthly returns
- NIFTY market returns
- Regression beta
- R-squared
- Statistical regression output
- Adjusted beta

The model also uses peer-company beta information as part of the
cost-of-capital framework.

---

## 6. WACC — Weighted Average Cost of Capital

A detailed WACC calculation is included.

The model calculates:

### Cost of Debt

- Pre-tax cost of debt
- Tax rate
- After-tax cost of debt

### Cost of Equity

Using:

- Risk-free rate
- Equity risk premium
- Levered beta

### Capital Structure

The model analyzes:

- Debt
- Equity
- Current capital structure
- Target capital structure

The final WACC is then used as the discount rate in the DCF valuation.

---

## 7. Intrinsic Growth & ROIC

The model calculates:

- Invested Capital
- NOPAT
- ROIC
- Net Capex
- Change in Working Capital
- Reinvestment
- Reinvestment Rate
- Expected Growth

This section connects the company's operating performance with its
long-term growth assumptions.

---

# 8. DCF Valuation

A Discounted Cash Flow valuation is used to estimate the intrinsic
value of Tata Consumer.

The DCF includes:

- EBIT
- Tax rate
- NOPAT
- Reinvestment rate
- Free Cash Flow to Firm (FCFF)
- Discounting factor
- Present Value of FCFF
- Terminal Value
- Cash
- Debt
- Equity Value
- Equity Value per Share

The model also incorporates a terminal growth assumption and WACC.

---

## 9. DCF Sensitivity Analysis

A sensitivity table is included to examine how changes in:

- WACC
- Terminal Growth Rate

affect the estimated equity value per share.

This demonstrates the sensitivity of DCF valuation to key assumptions.

---

## 10. Comparable Company Valuation

Relative valuation is performed using a peer set from the FMCG/consumer
space.

The comparable-company analysis includes:

- Hindustan Unilever
- ITC
- Nestle India
- Britannia Industries
- Marico
- Godrej Consumer
- Dabur India
- Other selected comparable companies

The model calculates:

- Enterprise Value
- Equity Value
- EV/Revenue
- EV/EBITDA
- P/E

Statistical measures including:

- High
- 75th Percentile
- Average
- Median
- 25th Percentile
- Low

are used to derive implied valuation ranges for Tata Consumer.

---

## 11. Football Field Analysis

A football-field analysis is used to visually compare valuation ranges
obtained from different approaches.

The model includes ranges from:

- Comparable Company Valuation
- DCF Bear Case
- DCF Base Case
- DCF Bull Case
- 52-Week High / Low

This provides a consolidated view of the valuation outputs from
different methodologies.

---

# 12. Value at Risk & Monte Carlo Simulation

The model also includes a risk-analysis section.

### Historical Approach

Historical stock returns are analyzed to estimate potential downside
using different confidence levels.

### Monte Carlo Simulation

The model generates simulated returns using a statistical distribution
and uses the simulated outcomes to estimate Value at Risk.

The analysis includes:

- Mean return
- Standard deviation
- Minimum return
- Maximum return
- Simulated returns
- VaR percentage
- VaR in INR

---

# Key Financial Concepts Applied

Through this project, I applied and explored:

- Financial Statement Analysis
- Ratio Analysis
- Common Size Analysis
- Financial Forecasting
- Revenue Forecasting
- EBITDA Forecasting
- EPS Forecasting
- Beta Estimation
- Regression Analysis
- CAPM
- Cost of Debt
- Cost of Equity
- WACC
- ROIC
- Reinvestment Rate
- Free Cash Flow to Firm
- DCF Valuation
- Terminal Value
- Sensitivity Analysis
- Comparable Company Valuation
- EV/Revenue
- EV/EBITDA
- P/E
- Football Field Analysis
- Value at Risk
- Monte Carlo Simulation

---

# Model Flow
```text

Historical Financial Data
          ↓
Financial Statement Analysis
          ↓
Ratio & Common Size Analysis
          ↓
Forecasting
          ↓
Beta / Market Analysis
          ↓
WACC
          ↓
ROIC & Reinvestment Analysis
          ↓
DCF Valuation
          ↓
Comparable Company Valuation
          ↓
Football Field Analysis
          ↓
Risk Analysis / VaR
