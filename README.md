# Trader-Performance-vs-Market-Sentiment
## Setup
pip install pandas numpy matplotlib seaborn scipy statsmodels

## How to Run
1. Place CSV files in /data folder
2. Run the Jupyter notebook: Trade_Sentiment_Analysis.ipynb
3. Create /outputs folder for ouputs

## Methodology
- Merged trade data with Fear & Greed index on Date
- Created features: Win, Leverage
- Computed daily PnL, volatility, win rate
- Analyzed trader behavior by sentiment

## Key Insights
- Volatility is highest during Fear and Extreme Greed
- Win rate varies across sentiment regimes
- Traders use higher leverage during Greed periods
- Frequent traders are more sensitive to sentiment
- Consistent winners outperform inconsistent traders

## Strategy Recommendations
- Reduce leverage during Fear regimes
- Limit position size during Extreme Greed
- Apply stricter risk management for frequent traders
- Prefer stable regimes (Neutral/Greed) for deployment
