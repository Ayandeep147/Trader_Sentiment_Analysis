# Trader Performance vs Market Sentiment Analysis

## Overview
This project analyzes how market sentiment (Fear vs Greed) affects trader behavior and performance using historical trading data.

## Methodology
- Cleaned and preprocessed sentiment and trader datasets
- Standardized columns and handled missing values
- Converted timestamps and aligned datasets on a daily level
- Merged datasets to analyze sentiment impact
- Computed key metrics: PnL, win rate, trade size, and trade direction
- Performed segmentation analysis based on trade size and trader frequency

## Key Insights
- Traders achieve higher average PnL during Fear despite lower win rates, indicating high-risk high-reward behavior
- Trade sizes are larger during Fear, suggesting higher conviction trading
- Traders exhibit contrarian behavior by buying during Fear and selling during Greed
- Larger trades generate significantly higher returns than smaller trades
- Infrequent traders outperform during Fear, while frequent traders perform better during Greed

## Strategy Recommendations
- Focus on fewer, high-conviction trades during Fear conditions
- Reduce position sizes and avoid overtrading during Greed periods
- Align trading frequency with market sentiment for better performance

## How to Run
- Open the notebook in Google Colab or Jupyter Notebook
- Run all cells sequentially
