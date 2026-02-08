# ✈️ Airline Passenger Demand Forecasting using ARIMA

## 📌 Project Overview
Airline companies rely heavily on accurate passenger demand forecasting to optimize aircraft allocation, workforce planning, and route scheduling.  
This project implements a **time series forecasting pipeline using the ARIMA model** to predict monthly airline passenger demand based on historical data.

The dataset exhibits a **long-term growth trend and seasonality**, making it **non-stationary**. To address this, appropriate **differencing techniques** are applied before building the ARIMA model.

---

## 🎯 Objectives
- Analyze historical airline passenger data
- Identify and handle non-stationarity in time series data
- Build an ARIMA model with optimal parameters *(p, d, q)*
- Evaluate forecasting accuracy using statistical metrics
- Forecast future passenger demand

---

## 🧾 Dataset Description
- **Dataset Name:** AirPassengers (Box & Jenkins)
- **Time Period:** January 1949 – December 1960
- **Frequency:** Monthly
- **Target Variable:** Number of airline passengers
- **Characteristics:**  
  - Upward trend  
  - Seasonality  
  - Non-stationary time series  

The dataset is created directly within the code and does not require external files.

---

## 🛠️ System Requirements
- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels  

Install dependencies using:
```bash
pip install pandas numpy matplotlib statsmodels scikit-learn
