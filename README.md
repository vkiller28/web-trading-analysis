# 📈 Web3 Trading & Market Sentiment Analysis

A data science project analyzing how trader behavior aligns with market sentiment using the Bitcoin Fear & Greed Index and historical Hyperliquid trading data.  
The project explores whether sentiment-driven signals can improve trading decisions and risk management.

---

## 🚀 Project Summary

This project investigates the relationship between:

- Market sentiment (Fear vs Greed)
- Trader behavior and profitability
- Risk exposure and leverage usage
- Trade outcome prediction

Using statistical analysis and machine learning, the project uncovers patterns that can support smarter trading strategies.

---

## 🎯 Objectives

- Analyze how sentiment affects profitability and risk  
- Identify hidden patterns in trading behavior  
- Evaluate whether sentiment can predict trade outcomes  
- Build predictive models for trade performance  

---

## 📂 Project Structure

ds_mukul/
├── notebook_1.ipynb # EDA & Data Preparation
├── notebook_2.ipynb # Modeling & Analysis
├── csv_files/
│ ├── historical_data.csv
│ └── fear_greed_index.csv
├── outputs/ # Visualizations & model results
├── ds_report.pdf # Final report
└── README.md


---

## 📊 Datasets

### 1️⃣ Hyperliquid Historical Trader Data
Includes:
- Account  
- Coin  
- Execution Price  
- Size  
- Side (Buy/Sell)  
- Timestamp  
- PnL  
- Leverage  

(~211K rows)

### 2️⃣ Bitcoin Fear & Greed Index
Includes:
- Date  
- Sentiment classification  
(Fear, Greed, Extreme Fear, Extreme Greed)

(~365 rows)

---

## 🔍 Key Analysis

✔ Time-series analysis of sentiment vs trading activity  
✔ Profitability comparison across sentiment zones  
✔ Risk analysis based on leverage usage  
✔ Statistical testing of sentiment impact  
✔ Predictive modeling for trade outcomes  

---

## 🤖 Machine Learning

Models used:
- Linear Models  
- XGBoost  
- Time-series forecasting (Prophet / ARIMA)

Goal:
Predict trade profitability using sentiment + trade features.

---

## 🛠️ Tech Stack

**Data Processing**  
- pandas  
- numpy  

**Visualization**  
- matplotlib  
- seaborn  
- plotly  

**ML & Stats**  
- scikit-learn  
- xgboost  
- scipy  
- statsmodels  

**Time Series**  
- Prophet  
- ARIMA  

---

## 📈 Key Insights

- Trader risk-taking increases during Greed phases  
- Extreme Fear often precedes profitable entries  
- Leverage misuse strongly correlates with losses  
- Sentiment adds predictive value to trade outcomes  

---

## 💼 Real-World Value

This project demonstrates:

- Financial data analysis skills  
- ML modeling on real-world datasets  
- Time-series analysis capability  
- Risk & behavioral analytics  
- End-to-end DS workflow

---

## ▶️ How to Run

1. Clone the repo

git clone https://github.com/vkiller28/your-repo-name.git


2. Install requirements

pip install -r requirements.txt


3. Open notebooks and run sequentially

---

## 👨‍💻 Author

**Mukul Mhatre**  
Electronics & AI Enthusiast  
GitHub: @vkiller28

---

## ⭐ If you found this useful

Consider giving the repo a star!
