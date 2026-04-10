# german-banking-sector-analysis
Analysis of German banking stocks (Deutsche Bank, Commerzbank, DAX) using Python, yfinance and World Bank API
# 🏦 German Banking Sector Analysis

## Overview
Analysis of major German banking stocks and the DAX index using 
real market data fetched via yfinance. Includes risk metrics, 
volatility analysis and SQL-style queries using pandas.

## Stocks Analyzed
- 🏦 Deutsche Bank (DBK.DE)
- 🏦 Commerzbank (CBK.DE)
- 📈 Deutsche Boerse (DB1.DE)
- 📊 DAX Index (^GDAXI)

## Analysis Performed
- Stock price history (2015–2024)
- Normalized performance comparison
- Annual returns heatmap
- 30-day rolling volatility
- Return correlation matrix
- Risk vs Return scatter plot
- SQL-style queries using pandas (GROUP BY, WHERE, ORDER BY)

## Key Findings
- COVID-19 caused sharp volatility spikes across all stocks in March 2020
- Deutsche Boerse showed strongest risk-adjusted returns (highest Sharpe Ratio)
- Deutsche Bank and Commerzbank highly correlated — move together
- DAX index significantly less volatile than individual banking stocks

## Tools & Libraries
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- yfinance
- scipy

## How to Run
1. Clone the repository
2. Install dependencies:
3. 3. Open `german_banking_analysis.ipynb` in Jupyter Lab
4. Run all cells top to bottom

## Author
**Nadim Elkhalil**
MSc Economic Behavior and Governance — University of Kassel
https://www.linkedin.com/in/nadim-el-khalil-855b43267?utm_source=share_via&utm_content=profile&utm_medium=member_android
