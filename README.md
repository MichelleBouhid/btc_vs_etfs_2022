# Asset class comparison: Bitcoin against equity, gold, bond and energy ETFs

Original analysis, 2022. Published unchanged in October 2026 as a record of early work. Text and comments in Portuguese.

Compares daily returns of SPY (S&P 500), BRK-A (Berkshire Hathaway), BTC-USD, GDX (gold miners), TLT (long Treasuries) and XLE (energy), from 2015 to 2022: cumulative and log returns, volatility, rolling 21-day volatility, correlation, rolling beta against SPY and annualised Sharpe ratio.

Data from Yahoo Finance via yfinance. The CSV files used in 2022 will be added to a `dados` folder.

Files: the notebook (.ipynb) opens directly on GitHub with all outputs. The PDF and HTML are exports of the same notebook.

Known limitations, as I would revise them today:
- Beta is computed with the asset's own variance in the denominator instead of the market's. The beta charts are therefore wrong.
- Close price is used instead of adjusted close, so dividend-paying ETFs are understated against BTC and BRK-A.
- Sharpe ratio assumes a zero risk-free rate.

A revised version with data through 2026 is planned.

Contact: michelle.bouhid@gmail.com
