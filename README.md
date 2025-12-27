# Securities-Analysis-and-Portfolio-Management

This project focuses on constructing an optimal portfolio using financial data from five selected stocks and one market index. The analysis involves calculating key financial metrics, generating the Markowitz efficient frontier, identifying the tangency portfolio, and performing CAPM analysis to evaluate stock performance.

Objectives :

1. Data Selection: Analyze 5 stocks (Axis Bank, Indigo, Jubilant, JK Cements, Fortis) and 1 index (Nifty 50) using daily closing prices for the financial year (April 1, 2024 to March 31, 2025).
2. Statistical Analysis: Calculate average daily returns, variance, standard deviation, covariance, and correlation matrices for all securities.
3. Portfolio Optimization: Generate and plot the Markowitz efficient frontier and identify the tangency portfolio using the risk-free rate.
4. CAPM Analysis: Calculate the Beta of each stock via regression against the market index, determine the required rate of return using the Capital Asset Pricing Model (CAPM), and compare it with actual average returns to identify undervalued/overvalued stocks.

Technologies Used : Python, Pandas, NumPy, Matplotlib, SciPy, Statsmodels, Yfinance

Key Results : The notebook generates the following outputs,
1. Annualized Return and Volatility tables.
2. Correlation and Covariance matrices.
3. Optimal portfolio weights for the Tangency Portfolio.
4. A plot of the Efficient Frontier with the Capital Market Line (CML).
5. Regression plots for each stock showing Beta.
6. A final summary table classifying stocks as "undervalued" or "overvalued" based on CAPM predictions.
