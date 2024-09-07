# Project: Implied-Volatility-for-Call-Options

## Overview

This project focuses on analyzing **Bank of America's** financial data using two distinct methods to calculate its call option implied volatility:

1. **Black-Scholes Model**: Using financial statements from **Bank of America**, including data from quarterly call reports, the implied volatility was calculated by treating the bank's equity as a call option. Total assets were used as the current stock price and total liabilities as the strike price. The Black-Scholes model was applied with assumptions about asset volatility, risk-free rates, and a zero-coupon bond structure.

2. **Market Data from Yahoo Finance**: Current **BofA** option data from **Yahoo Finance**, one of the most popular sources of financial data, was used to estimate implied volatility through market prices. The calculation relied on the current stock price, option prices, and the risk-free rate derived from treasury bonds.

Both methods revealed patterns in implied volatility over time and across strike prices, offering a comparison between model-generated and market-driven volatility estimates.

## References
- Bank of America Corporation (BAC) - Options [Link to paper](https://finance.yahoo.com/quote/BAC/options/) 
- Black-Scholes Formula and Python Implementation [Link to paper](https://aaronschlegel.me/black-scholes-formula-python.html)
- 
