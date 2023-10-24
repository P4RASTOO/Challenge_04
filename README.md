 <img width="542" alt="Screenshot 2023-10-23 at 11 15 04 PM" src="https://github.com/P4RASTOO/Challenge_04/assets/132952512/3d3ec7fa-7c9e-42cf-b809-72b699eaad84">

# Challenge_04 Report
## Overview of the Analysis:
The analysis involves creating a tool to evaluate the performance of various investment portfolios. The goal is to compare multiple portfolios based on metrics like volatility, returns, risk, and Sharpe ratios to determine which portfolio performs the best. The analysis is performed on historical daily returns of portfolios, including whale portfolios, algorithmic trading portfolios, and market indices, such as the S&P TSX 60 Index.


## Methods Used:
1) Data Preparation:
* Read and clean CSV files.
* Convert dates to DateTimeIndex.
* Handle missing values and non-numeric data.
* Convert closing prices to daily returns.
* Merge data from different portfolios into a single DataFrame.

2) Quantitative Analysis:
* Calculate and visualize daily returns and cumulative returns for all portfolios.
  Conduct risk analysis:
* Create box plots for returns.
* Calculate standard deviation.
  Determine which portfolios are riskier than the S&P TSX 60.
* Calculate annualized standard deviation.
* Calculate and visualize rolling statistics (rolling standard deviation and correlation).
* Calculate and plot the 60-day rolling beta between a chosen portfolio and the S&P TSX 60.
* Calculate Sharpe ratios for portfolios and visualize them in a bar plot.

3) Creating a Custom Portfolio:
* Choose 3-5 stocks for a custom portfolio.
* Download and calculate portfolio returns.
* Calculate weighted returns assuming an equal number of shares per stock.
* Add custom portfolio returns to the DataFrame with other portfolios.
* Conduct further analyses, including standard deviation, rolling standard deviation, correlation, beta calculation, and Sharpe ratio calculation for the custom portfolio.
