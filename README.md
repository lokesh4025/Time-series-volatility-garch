# 📊 Volatility Modeling and Forecasting using GARCH Family Models (NIFTY 50)

## 📌 Project Overview
This project models and forecasts volatility in Indian equity markets using the **GARCH(1,1) framework**.  
We used **NIFTY 50 daily data (2015–2025)**, tested for stationarity, fitted the model, and applied a volatility-scaled trading strategy.  

The study confirms volatility clustering in NIFTY 50 returns and demonstrates how GARCH-based forecasts can be used in **risk management and portfolio strategies**.  

---

## 📂 Files in Repository
- `Garch_Model.ipynb` → Full Jupyter/Colab code  
- `GARCH_Project_Report.pdf` → Final project report  
- `README.md` → Project documentation  

---

## 📊 Key Findings
- NIFTY prices are non-stationary, while returns are stationary.  
- GARCH(1,1) showed **high persistence (α + β = 0.966)**.  
- Daily volatility forecast ≈ **0.7%**.  
- The GARCH-based strategy reduced volatility and drawdowns but underperformed in returns compared to Buy & Hold.  

---

## 📈 Performance Comparison

| Metric            | Market (Buy & Hold) | GARCH Strategy |
|-------------------|---------------------|----------------|
| **Annual Return** | 9.79%              | 5.71%          |
| **Annual Volatility** | 17.59%          | 14.19%         |
| **Sharpe Ratio**  | 0.62               | 0.46           |
| **Max Drawdown**  | -40.04%            | -35.24%        |

---

## 🛠️ Tools & Libraries
- Python (`pandas`, `numpy`, `yfinance`)  
- Statistical libraries (`statsmodels`, `arch`)  
- Performance evaluation (`empyrical`)  

---

## 👨‍🎓 Author
**Lokesh Kumar**  
MBA (Finance with Marketing Minor)  
Jaypee University, Anoopshahr  

**Guided by:**  
Dr. Rahul Kumar  

---

## 📅 Date
August 2025
