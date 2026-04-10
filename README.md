# 🏦 German Banking Sector Analysis

## Overview
Comprehensive analysis of major German banking stocks and the DAX index
using real market data fetched via yfinance. Combines financial analysis,
risk metrics, volatility modeling and SQL-style queries using pandas.

![Price History](plot1_price_history.png)

## Stocks Analyzed
- 🏦 Deutsche Bank (DBK.DE)
- 🏦 Commerzbank (CBK.DE)
- 📈 Deutsche Boerse (DB1.DE)
- 📊 DAX Index (^GDAXI)

## Analysis & Visualizations

### 📊 Financial Analysis
- Stock price history (2015–2024) with key event annotations
- Normalized performance comparison (Base = 100)
- Annual returns heatmap by year
- 30-day rolling volatility
- Return correlation matrix
- Risk vs Return scatter plot

### 🗃️ SQL-Style Analysis (using pandas)
- `SELECT AVG(Close) GROUP BY Year` — average annual price per bank
- `SELECT COUNT(*) WHERE Close > threshold` — trading days above price levels
- `SELECT YoY_Change ORDER BY Year` — year-over-year performance ranking
- `SELECT AVG(Close) GROUP BY Month` — seasonal price patterns

## Key Findings
- COVID-19 caused sharp volatility spikes across all stocks in March 2020
- Deutsche Boerse showed strongest risk-adjusted returns (highest Sharpe Ratio)
- Deutsche Bank and Commerzbank are highly correlated — they move together
- DAX index significantly less volatile than individual banking stocks
- Clear seasonal patterns visible in monthly average prices

## Tools & Libraries
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- yfinance
- scipy

## How to Run
1. Clone the repository:
2. Install dependencies:
3. Open `german_banking_analysis.ipynb` in Jupyter Lab
4. Run all cells top to bottom

## Data Source
Yahoo Finance via yfinance library — real market data updated daily.

## Author
**Nadim Elkhalil**
MSc Economic Behavior and Governance — University of Kassel
[LinkedIn][(https://linkedin.com/in/nadim-elkhalil)](https://www.linkedin.com/in/nadim-el-khalil-855b43267?utm_source=share_via&utm_content=profile&utm_medium=member_android)
