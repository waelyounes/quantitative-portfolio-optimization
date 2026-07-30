# 📈 Quantitative Portfolio Optimization & Strategy Backtesting

## 📌 Project Overview
An end-to-end Quantitative Finance pipeline built in Python. This project provides automated financial data ingestion, portfolio risk-return evaluation using **Monte Carlo Simulation**, interactive dashboards with **Plotly**, and historical strategy evaluation through **SMA Crossover Backtesting**.

---

## 🛠️ Key Features
* **Data Ingestion:** Automated downloading of historical adjusted close prices using `yfinance`.
* **Statistical Analysis:** Annualized returns, volatility, correlation matrices, and Sharpe ratio calculations.
* **Portfolio Optimization:** Monte Carlo simulation running 5,000+ random portfolio weight allocations to generate the **Efficient Frontier** and pinpoint the **Max Sharpe Ratio Portfolio**.
* **Interactive Visualizations:** Dynamic line charts, correlation heatmaps, and scatter plots built using `Plotly`.
* **Strategy Backtesting:** Historical testing of a Simple Moving Average (SMA) crossover strategy, complete with **Maximum Drawdown (Max DD)** calculation and shift alignment to prevent look-ahead bias.

---

## 🏗️ Theoretical Framework
The project implements core financial engineering concepts:
1. **Modern Portfolio Theory (Markowitz MPT):** Diversification logic to optimize expected return against portfolio variance.
2. **Sharpe Ratio Optimization:** Measuring risk-adjusted efficiency relative to the risk-free rate.
3. **Risk & Downside Management:** Quantifying maximum peak-to-trough losses.

---

## 💻 Tech Stack
* **Language:** Python
* **Data & Math:** Pandas, NumPy
* **Financial Data:** yfinance
* **Data Visualization:** Plotly, Matplotlib

---

## 🚀 How to Run
1. Open the notebook `portfolio_optimization_quant.ipynb` in Google Colab or Jupyter Notebook.
2. Run all cells sequentially to view statistics, interactive charts, and backtest results.
