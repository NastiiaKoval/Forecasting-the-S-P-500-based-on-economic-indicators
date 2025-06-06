# 📈 Forecasting the S&P 500 with Macroeconomic Indicators and ML

This project predicts the future values of the S&P 500 index using machine learning models, time series analysis, and macroeconomic data (e.g., CPI, GDP,interest rates). It combines financial technical indicators with external economic signals to improve forecast accuracy.

---

## 📂 Project Overview

- Forecast target: **S&P 500 closing prices**
- Tools & Models:
  - `XGBoost` — with lagged and engineered features
  - `LSTM` — deep learning sequence model
  - `ARIMA`, `Prophet`, `Theta` — classical time series forecasting
- Feature Engineering:
  - Lag features (returns, macro indicators)
  - Rolling mean, std, volatility, momentum
  - Macroeconomic indicators from FRED (CPI, UR, IR, etc.)
- Evaluation metrics:
  - **MAE**, **MAPE**
  - Forecast vs. Actual plots

---

## 📊 Sample Indicators Used

- CPI (Consumer Price Index)
- Unemployment Rate
- Interest Rate
- Consumer Confidence Index
- PPI (Producer Price Index)
- Retail Sales
- Non-Farm Payrolls

---

## 🧠 Machine Learning Models

| Model      | Description                                     |
|------------|-------------------------------------------------|
| XGBoost    | Gradient boosting on engineered macro features  |
| LSTM       | Sequence model capturing temporal dependencies  |
| ARIMA      | Baseline statistical time series forecast       |
| Prophet    | Facebook's trend + seasonality forecast tool    |

---

## 📈 Example Outputs

- Visual forecast comparison (actual vs. predicted)
- MAE / MAPE values per model
- Classification of trend (↑ / ↓)

