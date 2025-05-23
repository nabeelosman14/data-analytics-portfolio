# 💹 Crypto Trading: ML + Expert Strategy (MSc Dissertation)

## 📋 Overview
This MSc project investigates whether machine learning can improve upon traditional expert trading strategies in the cryptocurrency market. The study simulates multiple expert-driven approaches (contrarian, momentum, mean reversion) and compares their performance with a machine learning-enhanced strategy using LSTM. Additionally, clustering and portfolio optimisation techniques are used to test diversification.

## 📅 Project Summary
- Duration: 3 months
- Data: 5 years of historical crypto data from Binance API
- Focus: Comparing standalone strategies vs ML-enhanced logic
- Evaluation Metrics: Return, Sharpe Ratio, Max Drawdown, Volatility

## 🧰 Tools Used
- Python (Pandas, NumPy, Matplotlib, Scikit-learn, Keras)
- Binance API (for data)
- Jupyter Notebook
- Quantitative finance logic (mean-variance optimisation, technical indicators)

## 🎯 Objectives
- Implement expert strategies (momentum, contrarian, mean reversion)
- Train an LSTM model to predict signal success for strategy enhancement
- Apply K-means clustering + Mean-Variance Optimisation to reduce risk
- Evaluate strategies on financial KPIs

---

## 📂 Files & Access

### 📁 Code

| Notebook | Description |
|----------|-------------|
| [`Contrarian Strategy.ipynb`](./Code/Contrarian%20Strategy.ipynb) | Simulates traditional contrarian logic using technical thresholds |
| [`Mean reversion strategy.ipynb`](./Code/Mean%20reversion%20strategy.ipynb) | Trades on the assumption that prices revert to historical mean |
| [`Momentum trading Strategy.ipynb`](./Code/Momentum%20trading%20Strategy.ipynb) | Follows trends based on recent directional strength |
| [`LSTM+ Contrarian.ipynb`](./Code/LSTM%2B%20Contrarian.ipynb) | Enhances contrarian strategy with LSTM-based prediction layer |
| [`k-means + mean variance portfolio optimisation(MVO).ipynb`](./Code/k-means%20%2B%20mean%20variance%20portfolio%20optimisation(MVO).ipynb) | Clusters coins and applies MVO for risk-adjusted portfolio allocation |

### 📁 Report
- 📄 [MSc Final Project Report (PDF)](./Report/MSc%20Final%20Project%20Report.pdf)

---

## 🧠 Skills Demonstrated
- Designing and implementing expert trading systems
- Applying machine learning (LSTM) to trading logic
- Portfolio optimisation with clustering and MVO
- Working with API-driven time-series data
- Strategy evaluation using quantitative finance metrics

---

## 📊 Data Access
- Historical data was extracted from the [Binance API](https://github.com/binance/binance-spot-api-docs)
- Datasets included OHLCV pricing, technical indicators, and signals for coins like BTC, ETH, and BNB
- Data files are not included due to size and reproducibility — however, notebooks contain data-fetching code or references to the API

---

> 📁 [Return to Main Portfolio](..)
