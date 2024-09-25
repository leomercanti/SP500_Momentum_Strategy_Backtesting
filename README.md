# SP500_Momentum_Strategy_Backtesting

## Overview

This project implements a **Momentum Strategy** using **moving averages** for the **S&P 500 index**. The strategy is based on the popular **Golden Cross** and **Death Cross** technique, using a **50-day** and **200-day** moving average. The project fetches historical data, applies the strategy, and backtests it from **January 2010 to September 2024** with a fictional starting portfolio of **$10,000**.

### Key Features
- Moving averages crossover strategy (50-day and 200-day).
- Buy and sell signals based on the crossovers (Golden Cross & Death Cross).
- Backtest results and performance metrics such as total return, annualized return, volatility, and maximum drawdown.
- Visualization of price movements and trading signals.
  
### Performance Metrics:
- **Total Return**: $3,532.37
- **Annualized Return**: 2.40%
- **Volatility**: 3.46%
- **Maximum Drawdown**: -9.79%

## Clone the repository:
   ```
   git clone https://github.com/leomercanti/SP500_Momentum_Strategy_Backtesting.git
   ```

## Files in the Repository

- **SP500_Momentum_Strategy_Backtesting.ipynb**: The main Google Colab file containing the strategy implementation and backtest.
- **README.md**: This file, providing an overview of the project.

## Libraries Used
- **yfinance**: For downloading historical S&P 500 data.
- **pandas**: For data manipulation and calculations.
- **numpy**: For numerical operations and logic.
- **matplotlib**: For plotting graphs and visualizing the strategy.

## How to Experiment

Feel free to modify the strategy by:
- Adjusting the moving average windows.
- Testing with different stocks or indexes.
- Tweaking the portfolio size or time range.
  
Make sure to backtest any changes to evaluate their impact!

## License

This project is open-source and available for anyone to use, modify, and contribute to. Feel free to fork the project and share your improvements!

---

**Explore the strategy and start building your own momentum-based trading algorithms today!**
