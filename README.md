# unsupervised-trading-strat
Algorithmic trading strategy using unsupervised learning (K-means clustering) on the S&P 500 index.

Project steps:
-Download/Load SP500 stocks prices data.
-Calculate different features and indicators on each stock.
-Aggregate on monthly level and filter top 150 most liquid stocks.
-Calculate Monthly Returns for different time-horizons.
-Download Fama-French Factors and Calculate Rolling Factor Betas.
-For each month fit a K-Means Clustering Algorithm to group similar assets based on their features.
-For each month select assets based on the cluster and form a portfolio based on Efficient Frontier max sharpe ratio optimization.
-Visualize Portfolio returns and compare to SP500 returns.
