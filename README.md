# Portfolio Analysis
Here I am analysing my personal portfolio, where I have traded XRPGBP since 2023/01/17 and have since then performed well enough to withdraw my initial capital.
The notebook follows the order:
- Pulls Kraken trading history through my read-only API.
- Cleans the trading data.
- Extracts daily price history for XRPGBP from the zip file provided by kraken (you can download it following the notebook).
- Analyses performance and visualises with charts.
- Monte Carlo simulation (assuming normal distribution).

# Strategy
I have followed BTCUSD through the halving cycles and treating it as a leading indicator decided to enter when the previous cycles have formed a low. Then most of the buy and sells activities have been triggered my technical analysis, with an idea to minimise risk. Once I saw my portfolio grew 4 times I decided to withraw my initial capital, which of course reduces the values on the metrics below.

# Metrics
At time of writing, for trading activity from 2023/01/17 until available data 2025/03/31 the metrics stand as:
- Pearson Correlation: 0.88
- Sharpe Ratio: 1.1
- Sortion Ratio: 1.7
- Cummulative Return: 185%
- Annualized Return: 87.5%
- Volatility: 56.84%
- Max Drawdown: 37.52%
- Calmar Ratio: 2.33
- Beta: 0.54
- Alpha: 0.0055
- Treynor Ratio: 0.32%
- Information Ratio: 0
- VaR 95%: 3.45%
- Expected Shortfall 95%: 5.82%
