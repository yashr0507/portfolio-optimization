# Constrained Portfolio Optimization

A Python-based portfolio optimization project that uses Monte Carlo simulation to generate random portfolios, identify optimal asset allocations, and analyze how portfolio constraints affect risk-adjusted performance.

## Overview

Portfolio optimization is one of the fundamental problems in quantitative finance. This project simulates thousands of possible portfolios using historical market data and compares unconstrained optimization with a constrained portfolio where no single asset can exceed 30% of the total allocation.

The project evaluates expected return, volatility, and Sharpe ratio while visualizing the Efficient Frontier and optimal portfolios.

## Assets Used

* Apple (AAPL)
* Microsoft (MSFT)
* NVIDIA (NVDA)
* Coca-Cola (KO)
* Gold Futures (GC=F)
* S&P 500 Index (^GSPC)

## Features

* Historical market data collection using yfinance
* Daily and annualized return calculations
* Annualized covariance matrix
* Monte Carlo simulation of 10,000 portfolios
* Efficient Frontier visualization
* Maximum Sharpe Ratio Portfolio
* Minimum Variance Portfolio
* Portfolio weight visualization
* Portfolio allocation constraint (maximum 30% per asset)
* Comparison between constrained and unconstrained optimization

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* yfinance

## Visualizations

The project generates:

* Covariance Heatmap
* Efficient Frontier (Unconstrained)
* Efficient Frontier (Constrained)
* Maximum Sharpe Portfolio Allocation
* Performance Comparison Tables

## Key Concepts

* Portfolio Expected Return
* Portfolio Volatility
* Covariance Matrix
* Diversification
* Efficient Frontier
* Sharpe Ratio
* Maximum Sharpe Portfolio
* Minimum Variance Portfolio
* Portfolio Constraints
* Monte Carlo Simulation

## Future Improvements

* Deterministic optimization using scipy.optimize
* Risk-free rate adjusted Sharpe ratio
* Sector allocation constraints
* Transaction cost modelling
* Interactive dashboards using Plotly or Dash
