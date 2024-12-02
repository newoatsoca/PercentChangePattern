# PercentChangePattern

## Overview
This Python application is a powerful stock pattern detection and visualization tool that helps investors and traders identify potential trading patterns using historical stock data from the Alpaca Markets API.

## Features
- Detect stock price patterns based on percentage change thresholds
- Analyze stock data across different timeframes (1 minute, 5 minutes, daily)
- Visualize detected patterns with interactive matplotlib graphs
- Flexible time range selection (last year, month, or day)
- Customizable percentage change threshold

## Prerequisites
- Python 3.7+
- Required Libraries:
  - alpaca-trade-api
  - matplotlib
  - pandas

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/newoatsoca/PercentChangePattern.git
   cd PercentChangePattern
   ```

2. Install required dependencies:
   ```bash
   pip install alpaca-trade-api matplotlib pandas
   ```

3. Set up Alpaca API Credentials:
   - Sign up for an Alpaca Markets account
   - Replace `API_KEY` and `API_SECRET` in the script with your actual credentials

## Usage
Run the script and follow the interactive prompts:

1. Enter the stock symbol (e.g., 'TSLA', 'AAPL', 'NVDA')
2. Choose time range:
   - 1: Last year
   - 2: Last month
   - 3: Single day
3. Select timeframe (e.g., '1Min', '5Min', '1D')
4. Set percentage change threshold

Example:
```bash
python findPattern.py
```

## Sample Output
The tool generates:
- Console output with detected pattern details
- Overall stock price graph with pattern markers
- Separate graphs for each detected pattern group

## Customization
- Adjust `change_threshold` in the code to fine-tune pattern detection sensitivity
- Modify time ranges and timeframes as needed

## License
MIT License
Copyright (c) 2024 Owen Acosta

## Disclaimer
This tool is for educational purposes. Always conduct thorough research and consult financial advisors before making investment decisions. I am not a financial advisor.
