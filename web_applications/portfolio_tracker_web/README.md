# Investment Portfolio Tracker Web Application

## Overview
Comprehensive web-based investment portfolio management system with real-time market data, performance analytics, and risk assessment tools.

## Files
- `portfolio_app.py` - Main Flask application with user authentication
- `database_models.py` - SQLAlchemy database models and relationships
- `api_connections.py` - Market data API integrations (Yahoo Finance, Alpha Vantage)
- `templates/` - HTML templates with responsive dashboard design
- `static/` - CSS, JavaScript, and charting libraries
- `requirements.txt` - Python dependencies and versions

## Core Features
### 📊 **Portfolio Management**
- **Multi-Portfolio Support**: Separate tracking for different accounts
- **Asset Classes**: Stocks, bonds, ETFs, mutual funds, crypto, cash
- **Transaction Tracking**: Buy, sell, dividend, split recording
- **Cost Basis**: FIFO, LIFO, specific lot identification
- **Performance Metrics**: Total return, IRR, TWR calculations

### 📈 **Real-time Market Data**
- **Price Updates**: 15-minute delayed quotes (free tier)
- **Market Indicators**: Major indices and sector performance
- **News Integration**: Relevant financial news by holdings
- **Economic Calendar**: Earnings dates, dividend schedules
- **Technical Analysis**: Moving averages, RSI, MACD indicators

### 🎯 **Analytics & Reporting**
- **Performance Dashboard**: Gain/loss, allocation, trends
- **Risk Analysis**: Beta, standard deviation, VaR calculations
- **Benchmark Comparison**: S&P 500, custom benchmark tracking
- **Tax Reporting**: Capital gains/losses, dividend income
- **Correlation Analysis**: Portfolio diversification metrics

## Dashboard Components
### 🏠 **Homepage Dashboard**
