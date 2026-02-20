# Trader-Behavior-Sentiment-Analysis
# Trader Performance vs Market Sentiment Analysis

## Objective
The objective of this project is to analyze how Bitcoin market sentiment (Fear & Greed Index) influences trader behavior and profitability using Hyperliquid trading data.

## Data Preparation
- Loaded trader dataset and sentiment dataset
- Converted timestamps to daily format
- Merged datasets using date column
- Checked missing values and duplicates
- Created trading metrics such as win rate, trade frequency and long/short bias

## Analysis Performed
The following metrics were analyzed:
- Profit and Loss distribution across sentiment
- Trade frequency during Fear vs Greed
- Long vs Short behavior
- Trader performance segmentation

## Key Insights
1. During Greed sentiment, traders executed more trades and suffered larger losses.
2. Fear sentiment showed more stable trading behavior and controlled PnL.
3. BUY positions were dominant during Greed, indicating emotional trading patterns.

## Strategy Recommendations
- Avoid overtrading during Extreme Greed periods
- Reduce position size in highly optimistic markets
- Prefer selective entries during Fear sentiment

## How to Run
1. Install dependencies:
   pip install pandas numpy matplotlib seaborn

2. Run the notebook:
   trader_sentiment_analysis.ipynb
