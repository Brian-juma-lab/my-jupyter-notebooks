📈 ARIMA Time Series Forecasting – Safaricom (SCOM) Stock Prices
This project demonstrates how to build and evaluate an ARIMA (AutoRegressive Integrated Moving Average) model to forecast Safaricom (SCOM) stock prices using Python and Jupyter Notebook.

🔍 Project Overview
Dataset: Historical stock data for SCOM (Safaricom) including daily closing prices.

Goal: Forecast future stock prices using the ARIMA model.

Techniques Used:

Time series preprocessing

Stationarity testing

ARIMA modeling

Forecast visualization

Model evaluation (RMSE & MAPE)

Model serialization with joblib

🛠️ Tools & Libraries
Python 3.x

Jupyter Notebook

Pandas

Matplotlib & Seaborn

Statsmodels

scikit-learn

joblib

📁 Files Included
scom_forecasting.ipynb — the main Jupyter Notebook with step-by-step implementation

SCOM data.csv — raw stock data

arima_model.pkl — saved ARIMA model for reuse

README.md — project description

📊 Key Results
Model used: ARIMA(1,1,1)

Forecast Horizon: 30 days

Evaluation Metrics:

RMSE: 1.32

MAPE: 6.13%
