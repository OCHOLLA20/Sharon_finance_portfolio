# Credit Risk Assessment Model

## Overview
Comprehensive credit risk model incorporating Sharpe ratio analysis, probability of default calculations, and portfolio risk metrics.

## Files
- `risk_model.py` - Python risk calculation engine
- `sharpe_ratio_analysis.xlsx` - Risk-adjusted return analysis
- `loan_data.csv` - Sample loan portfolio (500 records)

## Risk Metrics Calculated
- **Probability of Default (PD)**: Individual and portfolio level
- **Loss Given Default (LGD)**: Recovery rate analysis
- **Exposure at Default (EAD)**: Credit exposure calculations
- **Expected Loss**: PD × LGD × EAD
- **Value at Risk (VaR)**: 95% and 99% confidence levels
- **Sharpe Ratio**: Risk-adjusted portfolio performance

## Model Validation
- **Accuracy**: 87% default prediction accuracy
- **ROC AUC**: 0.91 for classification model
- **Backtesting**: 2-year historical validation
- **Stress Testing**: Economic downturn scenarios

## Applications
- Loan approval decision support
- Portfolio risk monitoring
- Pricing optimization
- Regulatory capital calculation (Basel III)
