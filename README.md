# Data Science Assignment - Mukul

## Project Overview
Analyzing the relationship between trader behavior and market sentiment using Bitcoin Fear & Greed Index and historical Hyperliquid trading data.

## Objective
- Explore how trading behavior (profitability, risk, volume, leverage) aligns or diverges from market sentiment (fear vs greed)
- Identify hidden trends and signals for smarter trading strategies
- Build predictive models to forecast trading outcomes based on sentiment

## Directory Structure
```
ds_mukul/
├── notebook_1.ipynb           # EDA & Data Preparation
├── notebook_2.ipynb           # Modeling & Analysis  
├── csv_files/                 # Raw and processed data
│   ├── historical_data.csv    # Hyperliquid trading data (~211K rows)
│   └── fear_greed_index.csv   # Bitcoin sentiment data (~365 rows)
├── outputs/                   # Generated visualizations and models
├── ds_report.pdf             # Final analysis report
└── README.md                 # This file
```

## Datasets
1. **Historical Trader Data**: Hyperliquid exchange data with columns:
   - Account, Coin, Execution Price, Size, Side, Timestamp, PnL, Leverage, etc.
   
2. **Bitcoin Fear & Greed Index**: Market sentiment indicators with:
   - Date, Classification (Fear/Greed/Extreme Fear/Extreme Greed)

## Google Colab Notebooks
- **Notebook 1 (EDA)**: [Data Analysis & Exploration](https://colab.research.google.com/drive/1P4EToc1jwd0ynMheBJjMKC0_pHmIYMNH)
- **Notebook 2 (Modeling)**: [Machine Learning & Predictions](https://colab.research.google.com/drive/16t8SRVGChWrHcj2jX9IXUEuuUZ81z3dd)

## Key Analysis Areas
- Time-series analysis of trading patterns vs sentiment
- Statistical testing of sentiment impact on profitability
- Predictive modeling for trade outcomes
- Risk assessment across different market conditions

## How to Use
1. Open notebooks in Google Colab using the links above
2. Notebooks will automatically load data from GitHub raw URLs
3. Run cells sequentially to reproduce analysis
4. Generated outputs will be saved to `outputs/` folder

## Technologies Used
- **Data Processing**: pandas, numpy
- **Visualization**: matplotlib, seaborn, plotly
- **Statistics**: scipy, statsmodels
- **Machine Learning**: scikit-learn, xgboost
- **Time Series**: prophet, ARIMA

---
**Author**: Mukul  
**Date**: October 2025  
**Assignment**: Data Science Challenge