# Algorithmic_Trading

## MACD Crossover Backtesting Strategy

### Overview

This script contains a basic backtesting strategy implemented in Python using moving average crossovers. The strategy fetches historical stock price data from Yahoo Finance, applies a moving average crossover strategy, and evaluates its performance.

### Usage

1. Install the required packages:

   ```bash
   pip install -r requirements.txt

2. Run the script:

    ```bash
    python MACD_Crossover.ipynb
    ```

3. Use the configure function to input asset tickers and date ranges, as well as MACD parameter values.

4. View the generated time series plot with MACD buy/sell signals.


### Configuration

Modify the configure function in backtest_strategy.py to customize the strategy settings such as assets, start date, and moving average window lengths.

## Dependencies

- pandas
- yfinance
- matplotlib
- pandas
- numpy

## Contributors

- [Nicky Taylor](https://github.com/CoderNicky)

Feel free to contribute, report issues, or suggest improvements!

### License

This project is licensed under the MIT License - see the LICENSE file for details.
