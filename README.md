# 🇵🇰 Pakistan Mutual Fund Intelligence Platform  
### Data-Driven Mutual Fund Analytics · ML Forecasting · Risk & Sector Intelligence Dashboard
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🔍 Overview

The **Pakistan Mutual Fund Intelligence Platform** is a data science system designed to analyze, compare, and forecast mutual fund performance in Pakistan using machine learning, macroeconomic indicators, and financial data processing.

It integrates NAV history, MUFAP data, PSX indicators, and global macro signals to generate actionable investment insights.

---

## 🚀 Key Features

| Feature | Description |
|--------|-------------|
| 📊 Fund Analytics | Compare equity, balanced, and income funds |
| 🤖 ML Forecasting | NAV prediction using Prophet & regression models |
| 🌍 Macro Integration | Inflation, interest rates, global indicators |
| 🧠 Risk Analysis | Volatility, Sharpe ratio, drawdown metrics |
| 🧾 Sector Exposure | Fund allocation breakdown |
| 📈 Visual Dashboard | Interactive Plotly charts |
| 🕸️ Data Pipeline | MUFAP-style data ingestion and cleaning |

---

## 🧰 Tech Stack

- Python
- Pandas / NumPy
- Scikit-learn
- Facebook Prophet
- Plotly / Matplotlib
- BeautifulSoup
- yFinance
- SciPy

---

## 📡 Data Sources

- MUFAP (Mutual Funds Association of Pakistan)
- Pakistan Stock Exchange (PSX)
- State Bank of Pakistan (SBP)
- Yahoo Finance (global indicators)

---

## 🏗️ Workflow
Data Collection → Cleaning → Feature Engineering → ML Forecasting → Visualization

---

## 📸 Demo & Visual Outputs

### 📊 NAV Performance
![NAV Performance](asset/5_year_historical_nav_performance.png)

### 🌍 Macro Impact
![Macro Impact](asset/Fund%20Returns%20vs.%20Global%20Macro%20Indicators.png)

### 🤖 Feature Importance
![Feature Importance](asset/GBM%20feature%20importance.png)

### ⚠️ Stress Testing
![Stress Test](asset/Global%20Macro%20Stress%20Test%20%E2%80%94%20Estimated%20NAV%20Impact%20by%20Scenario.png)

### 📈 Balanced Fund Projection
![Balanced Fund](asset/Meezan_Balanced_Funds_5_Year_Nav_Projection.png)

### 💰 Cash Fund Projection
![Cash Fund](asset/Meezan_Bank_Cash_Fund_5_Year_Nav_Projection.png)

### 📊 Mutual Fund Projection
![Mutual Fund](asset/Meezan_Bank_Mutual_Funds_5_Year_Projection.png)

### 🧾 Portfolio Composition
![Portfolio](asset/Portfolio_Composition_OGD_Dependency_Analysis.png)

### 📉 Volatility Analysis
![Volatility](asset/annual_votality.png)

### 📊 Benchmark Dashboard
![Benchmark](asset/bechmark%20dashborard.png)

### 📌 Investment Plan
![Investment Plan](asset/investment_plan.png)
---

## 📊 Outputs

- Mutual fund performance comparison
- 5-year NAV forecasts
- Risk-return analysis
- Sector allocation breakdown
- Macro sensitivity insights

---

## ⚙️ Installation


git clone https://github.com/your-username/pakistan-mutual-fund-intelligence.git
cd pakistan-mutual-fund-intelligence

pip install -r requirements.txt

Manual install:
pip install prophet yfinance plotly scikit-learn requests beautifulsoup4 pandas numpy

---

## ▶️ Usage
jupyter notebook Pakistan_MutualFund_Intelligence.ipynb
Steps:

- Load dataset / scrape data
- Clean and preprocess
- Feature engineering
- Train forecasting model
- Visualize results

---
## 📌 Use Cases
- Investment analysis
- Mutual fund benchmarking
- Academic financial research
- Portfolio risk assessment
- Fintech prototyping

---
## ⚠️ Disclaimer

This project is for educational and research purposes only.
It does not constitute financial advice.

---
## 📈 Future Improvements
- Real-time NAV API integration
- LSTM / Transformer forecasting
- Portfolio optimization engine
- Streamlit dashboard
- Automated investment signals


---
⭐ If you find this useful, consider starring the repository.

---
