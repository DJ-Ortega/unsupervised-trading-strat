# unsupervised-trading-strat

Algorithmic trading strategy using unsupervised learning (K-means clustering) on the S&P 500 index.

## Project steps

- Download/Load S&P 500 stock price data.
- Calculate different features and indicators on each stock.
- Aggregate on a monthly level and filter the top 150 most liquid stocks.
- Calculate monthly returns for different time horizons.
- Download Fama-French factors and calculate rolling factor betas.
- For each month, fit a K-Means clustering algorithm to group similar assets based on their features.
- For each month, select assets based on the cluster and form a portfolio based on Efficient Frontier max Sharpe ratio optimization.
- Visualize portfolio returns and compare to S&P 500 returns.
