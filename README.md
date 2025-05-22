# Algorithmic Trading Strategy with K-Means Clustering

## Overview
This project implements an unsupervised learning-based trading strategy using K-Means clustering to group S&P 500 stocks based on technical features (RSI, Bollinger Bands, etc.) and optimizes portfolios using the Efficient Frontier.

## Features
- Fetches S&P 500 stock data using Yahoo Finance (`yfinance`).
- Calculates technical indicators (RSI, ATR, MACD, etc.).
- Clusters stocks using K-Means with predefined RSI centroids.
- Optimizes portfolio weights using PyPortfolioOpt (Max Sharpe Ratio).
- Compares strategy returns against SPY (S&P 500 ETF).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/algorithmic-trading-kmeans.git
