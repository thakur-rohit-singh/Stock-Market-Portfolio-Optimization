# Stock Market Portfolio Optimization

## Overview

This project focuses on optimizing a stock market portfolio by leveraging Modern Portfolio Theory (MPT). The goal is to construct an efficient portfolio that offers the best possible trade-off between risk and return. The project includes analysis of stock price trends, calculation of expected returns and volatilities, and determining correlations between different stocks to achieve optimal diversification.

## Key Features

- **Data Collection**: The project uses real-time and historical stock data from the yfinance API to analyze the performance of selected stocks over a one-year period.
- **Visualizations**: Includes detailed visualizations of stock performance, moving averages, daily returns distribution, and the correlation matrix of the selected stocks.
- **Portfolio Optimization**: Utilizes MPT to calculate expected returns, volatility, and the Sharpe ratio for each stock, and generates a series of random portfolios to identify the efficient frontier.
- **Efficient Frontier**: The project visualizes the efficient frontier, showcasing the optimal portfolios that offer the highest expected returns for a given level of risk.
- **Optimal Portfolio Identification**: Identifies the portfolio with the maximum Sharpe ratio, indicating the best risk-adjusted return, and provides the stock allocation strategy for achieving long-term investment goals.

## Objectives

- **Risk-Return Analysis**: To analyze the trade-off between risk and return for various stock portfolios.
- **Efficient Portfolio Construction**: To construct a portfolio that lies on the efficient frontier, optimizing the Sharpe ratio.
- **Stock Selection**: To determine the optimal allocation of assets that minimizes risk while maximizing returns.

## Technologies Used

- **Python**: The primary programming language used for data manipulation and analysis.
- **yfinance**: For fetching real-time and historical stock data.
- **pandas**: For data manipulation and processing.
- **Matplotlib & Seaborn**: For visualizing stock performance, correlations, and the efficient frontier.
- **NumPy**: For numerical calculations involved in portfolio optimization.

## How It Works

1. **Data Collection**: Collects stock data for selected companies using the yfinance API, focusing on key attributes like adjusted close prices, trading volume, and more.

2. **Performance Visualization**: Visualizes stock performance over time, including price trends, moving averages, and trading volumes.

3. **Daily Returns Analysis**: Calculates and visualizes the distribution of daily returns to understand stock volatility and risk.

4. **Correlation Matrix**: Analyzes correlations between stocks to determine potential diversification benefits.

5. **Portfolio Optimization**: Uses Modern Portfolio Theory to calculate expected returns, volatility, and the Sharpe ratio for each portfolio. Simulates multiple portfolios to identify the efficient frontier.

6. **Optimal Portfolio Identification**: Determines the portfolio with the maximum Sharpe ratio, providing the best risk-adjusted return and optimal asset allocation.

## Conclusion

This project provides a comprehensive approach to stock market portfolio optimization, offering valuable insights for investors looking to optimize their portfolios by balancing risk and return. The analysis and visualizations help in making informed decisions based on historical data and Modern Portfolio Theory.

## Contributions

Contributions to enhance this project are welcome. Feel free to fork the repository, make your changes, and submit a pull request.
