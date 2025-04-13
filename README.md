# 📊 Stocks Portfolio Robo-Advisor

A data-driven portfolio analysis and investment simulation tool leveraging real-time market data via the Yahoo Finance API. Combines statistical modeling with Monte Carlo simulations to optimize and visualize portfolio performance.

---

## 💡 Overview

Fetches and analyzes data from **3,000+ public stocks** using the Yahoo Finance API (`yfinance`) to simulate thousands of potential investment outcomes. Designed to mimic robo-advisor logic for dynamic risk-adjusted decision-making.

---

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:** NumPy, Pandas, Matplotlib, YFinance  
- **API:** Yahoo Finance (via `yfinance`)  
- **Environment:** Anaconda, Jupyter Notebook  

---

## ⚙️ Features

- 📈 Real-time stock data ingestion via Yahoo Finance API  
- 🎲 Monte Carlo simulations for return forecasting and risk modeling  
- 📊 Visualizations for ROI distribution, volatility, and asset correlation  
- 🧼 Built-in data cleaning, multithreading, and batch processing  

---

## 🚀 Getting Started

```bash
git clone https://github.com/kylekapoor/robo-advisor
cd robo-advisor
conda create --name advisor-env python=3.10
conda activate advisor-env
pip install -r requirements.txt
jupyter notebook
