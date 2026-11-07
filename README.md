📊 Comparing Bitcoin vs Ethereum: Volatility & Returns Analysis
📌 Project Overview

This project analyzes the performance of Bitcoin (BTC) and Ethereum (ETH) over the last 12 months using Python.
We explore price trends, daily returns, volatility, and risk/reward profiles to better understand the behavior of the two largest cryptocurrencies.

The analysis demonstrates how data science can be applied to financial datasets using tools like pandas, matplotlib, and yfinance.

🛠️ Tools & Libraries

Python 3

pandas → data manipulation

matplotlib → visualization

yfinance → crypto/financial data collection

📂 Data Collection

Data Source: Yahoo Finance
 via yfinance

Tickers: BTC-USD and ETH-USD

Period: Last 1 year

Interval: Daily

import yfinance as yf
btc = yf.download("BTC-USD", period="1y", interval="1d")
eth = yf.download("ETH-USD", period="1y", interval="1d")

🔎 Analysis Performed

Price Trends – BTC vs ETH closing price chart.

Daily Returns Distribution – Histogram comparison of volatility.

Most Volatile Days – Largest daily swings in BTC and ETH.

Monthly Average Returns – Average return by month.

Risk/Reward Profile – Sharpe ratios to compare returns relative to risk.

📈 Key Findings

Bitcoin (BTC) is more stable, with fewer extreme swings.

Ethereum (ETH) is more volatile but showed higher monthly returns in several periods.

The most volatile day for BTC was 2024-11-11, with a return of +10.22%.

The most volatile day for ETH was 2025-05-08, with a return of +21.80%.

BTC’s Sharpe ratio was higher (1.33 annualized vs. 0.93 for ETH), so BTC returned more per unit of risk over this period. ETH swung harder without enough extra return to make up for it.

✅ Conclusion

BTC may be more suitable for risk-averse investors seeking stability.

ETH offers higher potential returns but comes with higher risk.

From a data science perspective, this project shows how to:

Collect real-world data.

Explore and visualize financial datasets.

Quantify risk and reward.

Present findings in a structured report.

🚀 Future Work

Expand analysis to other cryptocurrencies (ADA, AVAX, SOL).

Use more advanced risk metrics (Sortino ratio, maximum drawdown).

Explore portfolio diversification strategies with multiple assets.

📂 Project Files

BTC_Analysis.ipynb → Jupyter/Colab notebook with the code, charts and results.

Comparing_Bitcoin_vs_Ethereum_Volatility_&_Returns_Analysis.ipynb → Written walkthrough of the analysis and findings.

README.md → Project overview (this file).

👤 Author

Carlos Arroyo

💼 LinkedIn: [linkedin.com/in/coarroyo30](https://www.linkedin.com/in/coarroyo30)

