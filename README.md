# Portfolio-Optimization
Strategic Stock Investment Analysis: Comparing Buy-and-Hold with Momentum Trading within Modern Portfolio Theory
Overview:
This project aims to create a stock portfolio that optimally balances the trade-off between risk and return, comparing various investment strategies.Utilized libraries like Pandas, NumPy, Seaborn for data manipulation and visualization, Pyomo with the IPOPT solver for optimization, and integrated Yahoo Finance for stock analysis.

Collected historical stock price data for 30 tickers, representing 10 stocks from three different sectors, spanning from January 1, 2017, to December 31, 2021. Extracted 'adjclose' prices and created a dataframe 'prep_data' with adjusted close prices for all tickers. Cleaned the data and performed Exploratory Data Analysis (EDA), visualizing the time series analysis of stock values by sector. Conducted Momentum Trading to identify the top 3 performing stocks from each sector based on the crossing points of the moving average.

Our goal is to allocate money into stocks to maximize the expected return while accounting for risk tolerance, with added constraints. We performed Momentum Trading on the selected portfolio to identify the best strategy for each stock. Finally, we analyzed how our portfolio performed for a $100K investment using different strategies.

SECTORS :
Energy Sector , Finance Sector , Materials Sector

TOP 3 Chosen Stocks from each sector:
Energy Sector:
TRGP (Targa Resources Corp)
FANG (Diamondback Energy, Inc)
MRO (Marathon Oil Corporation)

Finance Sector:
BX (The Blackstone Group Inc.)
HIG (The Hartford Financial Services Group, Inc.)
MET (MetLife, Inc.)

Materials Sector:
NUE (Nucor Corporation)
STLD (Steel Dynamics, Inc.)
SHW (Sherwin-Williams Company)

Portfolio Allocations Across Different Risk Levels:
<img width="320" alt="image" src="https://github.com/SaiDeepikaBandari/Portfolio-Optimization/assets/163686372/ccb2c7c2-3441-4415-82f0-d410e8cd5f9a">
The graph "Optimal Stock Allocation for Different Risk Levels" shows the varying proportions of a portfolio dedicated to nine different stocks at increasing levels of risk, depicted on the x-axis. The red line, representing 'BX', demonstrates a prominent increase in its portfolio share with rising risk, suggesting its role as a high-risk, high-return option. Conversely, 'SHW' the stock indicated by the yellow line, which decreases in allocation as risk increases, is likely preferred in lower-risk settings. Other stocks maintain smaller, steadier allocations, indicating their lesser influence on the portfolio's overall risk or a balanced role across different risk levels. This visualization is key for investors to align their portfolio allocations with their risk preferences.

The efficient frontier plot visualizes the trade-off between risk and return for the different portfolio allocations.
Plot with Efficent frontier:
<img width="352" alt="image" src="https://github.com/SaiDeepikaBandari/Portfolio-Optimization/assets/163686372/e146ae4a-d55e-4ec8-9adb-092a337b315d">

The graph illustrates the relationship between risk and return for a set of portfolios comprising the selected stocks. On the x-axis, which represents risk measured by standard deviation, we see values ranging from approximately 0.00025 to beyond 0.00045. The y-axis, representing the expected return of the portfolios, spans from just above 0.0012 to approximately 0.0016.




