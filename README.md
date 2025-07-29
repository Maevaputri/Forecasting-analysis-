# 📊 Time Series Forecasting of E-Commerce Sales (2019)

This project analyzes and forecasts daily sales transaction data throughout 2019 using Python. The goal is to support the marketing team in identifying sales trends and predicting future activity.

## 🔧 Tools & Libraries
- Python
- pandas, matplotlib, seaborn
- statsmodels (Holt-Winters, ARIMA/SARIMA)
- scikit-learn
- Prophet (optional)

## 📌 Key Highlights
- Aggregated GMV per day/week/month
- Top 10 products and top 5 cities by sales
- Rush hour analysis
- Time series forecasting using:
  - Naive Forecast
  - Holt-Winters
  - SARIMA
- Model evaluation: RMSE, MAE, MAPE

## 📁 Project Structure
forecasting-sales-2019/
├── data/ # Raw monthly sales CSV files
├── notebooks/ # Jupyter Notebook for analysis
├── images/ # Optional visual assets
├── README.md # Project documentation
└── requirements.txt # Python dependencies


## 📈 Forecasting Result

Best model: **Naive Forecast**  
MAPE: **80.25%**

The data shows stable daily transactions. Advanced models (SARIMA, Holt-Winters) do not outperform simple baselines. Recommendation: Focus on short-term promotional campaigns and operational readiness during peak hours.

---

## 👥 Author
Maeva Putri – Data Science Bootcamp Final Project

##Requirements
pandas
numpy
matplotlib
seaborn
scikit-learn
statsmodels
prophet


