# Kailasa Capital Trading Strategies

## Overview
This repository contains a comprehensive suite of algorithmic trading strategies developed by Kailasa Capital for the Indian equity markets, specifically targeting Nifty 50 and Nifty Bank indices. The strategies are implemented in Python using Jupyter notebooks and leverage various technical analysis techniques to generate trading signals.

## Strategies Implemented

### Strategy 1: Indicator-Based (Daily Timeframe)
- Files: `NF_DAILY_STRATEGY_1.ipynb`, `NB_DAILY_STRATEGY_1.ipynb`
- Approach: Combines RSI, MACD, and SMA indicators to identify trading opportunities
- Timeframe: Daily

### Strategy 2: Trend-Based (15-Minute Timeframe)
- Files: `NF_15MIN_STRATEGY_2.ipynb`, `NB_15MIN_STRATEGY_2.ipynb`
- Approach: Uses custom Renko chart implementation with time-of-day filters
- Timeframe: 15-minute intraday

### Strategy 3: Momentum-Based (60-Minute Timeframe)
- Files: `NIFTY50_60MIN_STRATEGY_3.ipynb`, `NIFTYBANK_60MIN_STRATEGY_3.ipynb`
- Approach: Employs Renko charts with Supertrend indicators to capture momentum
- Timeframe: 60-minute (hourly)

## Key Features
- Multiple timeframes and approaches for diversified trading opportunities
- Comprehensive backtesting from 2020 to 2025
- Advanced risk management framework with dynamic position sizing
- Slippage modeling for realistic performance estimation
- Detailed performance metrics and analytics

## Documentation
- `Kailasa-Capital-Strategies-Report.docx`: Complete documentation of all strategies, mathematical foundations, and implementation details

## Dataset
The `/datasets` directory contains historical OHLCV data for Nifty 50 and Nifty Bank indices across multiple timeframes:
- Daily data
- 60-minute data
- 15-minute data

## Requirements
To run the notebooks in this repository, you need the following dependencies:
```
pandas>=1.5.0
numpy>=1.21.0
matplotlib>=3.5.0
seaborn>=0.12.0
ta>=0.10.0
stocktrends>=0.0.1
python-dateutil>=2.8.2
```

Install dependencies using: `pip install -r requirements.txt`

## Usage
1. Clone this repository
2. Install required dependencies using `pip install -r requirements.txt`
3. Open the Jupyter notebooks to explore the strategies
4. The notebooks are self-contained with data loading, strategy implementation, and performance analysis

## Disclaimer
*The strategies and analyses presented are based on historical data and do not guarantee future results. All trading involves risk, and past performance is not indicative of future returns.* 