## Portfolio Optimization of the S&P 500 Communication Services Sector

This project implements a mean-variance portfolio optimization model to construct a Sharpe-ratio-maximizing long-only portfolio for companies in the Communication Services sector of the S&P 500.

The portfolio is optimized using historical market data, analyst target prices, and Modern Portfolio Theory (MPT). The final portfolio is evaluated using expected return, annualized volatility, and Sharpe ratio.

**Overview**

The goal of this project is to identify the optimal allocation of capital across Communication Services companies while maximizing the expected risk-adjusted return.

Unlike traditional portfolio optimization that estimates expected returns from historical averages, this project uses analyst target prices from Yahoo Finance to provide forward-looking return estimates.

The optimization is performed using Sequential Least Squares Programming (SLSQP) under realistic investment constraints.

**Features**

- Downloads historical stock prices using **yfinance**
- Automatically selects Communication Services companies from the S&P 500
- Cleans and filters financial data
- Estimates expected returns using analyst target prices
- Computes annualized covariance matrices
- Optimizes portfolio weights by maximizing the Sharpe ratio
- Produces visualizations of portfolio allocation
- Compares optimized portfolio performance with the S&P 500

**Results**

Optimized Portfolio:

| Ticker | Weight |
|---------|--------:|
| CHTR | 41.02% |
| TMUS | 23.69% |
| NWSA | 18.27% |
| OMC | 15.12% |
| TTD | 1.90% |

Performance:

| Metric | Value |
|--------|-------:|
| Expected Annual Return | 46.08% |
| Annualized Volatility | 24.38% |
| Sharpe Ratio | 1.89 |

The optimized portfolio outperformed the historical long-run risk-adjusted performance of the S&P 500 in terms of expected Sharpe ratio, while remaining concentrated in a small number of Communication Services companies.


**Author**

Silvia Barnes Franco

*Physics Undergraduate, Programming with Mathematical Applications Project*

*This project is available under the MIT License*
