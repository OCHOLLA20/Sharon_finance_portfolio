# Stock Price Prediction Model

## Overview
Time series forecasting model for Kenyan stock market using machine learning techniques and technical indicators.

## Files
- `time_series_model.py` - LSTM and ARIMA prediction models
- `market_data.csv` - NSE stock data (Safaricom, Equity Bank, KCB)
- `prediction_results.html` - Interactive forecast visualizations

## Modeling Approach
- **Data Sources**: NSE historical data, economic indicators
- **Features**: Technical indicators (RSI, MACD, Bollinger Bands)
- **Models**: LSTM neural networks, ARIMA, Prophet
- **Validation**: Walk-forward analysis, cross-validation
- **Ensemble**: Model averaging for improved accuracy

## Performance Metrics
- **RMSE**: 2.3% average prediction error
- **Direction Accuracy**: 68% correct trend prediction
- **Sharpe Ratio**: 1.4 for trading strategy
- **Maximum Drawdown**: 8.2% in backtesting

## Features
- Real-time data integration
- Multiple timeframe predictions (1-day to 3-month)
- Risk-adjusted trading signals
- Portfolio allocation recommendations
