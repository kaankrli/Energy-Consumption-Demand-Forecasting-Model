# ⚡ EnerVision: Energy Consumption and Demand Forecasting

This project simulates an energy company's data-driven approach to forecasting electricity consumption using **time series models** like ARIMA, Prophet, and LSTM.  
It also includes trend and seasonality analysis, plus energy-saving recommendations.

---

## 🧩 Project Overview
**Scenario:**  
EnerVision, a smart-energy provider, wants to:
- Understand daily and weekly consumption patterns  
- Detect peak hours and holidays  
- Forecast next week’s energy demand  
- Propose energy optimization strategies  

---

## 🧠 Methods Used
- Exploratory Data Analysis (EDA)
- Time Series Decomposition
- Forecasting: `ARIMA`, `Prophet`, and optional `LSTM`
- Feature Engineering (lags, rolling means)
- Visualization with `matplotlib` & `seaborn`

---

## 📦 Dataset
- **File:** `energy_consumption_2000_rows.csv`  
- **Records:** 2,000 hourly readings  
- **Features:**
  - `timestamp`
  - `consumption_kwh`
  - `temperature_C`
  - `day_of_week`, `hour`
  - `is_holiday`, `is_weekend`, `is_peak_hour`, `is_offpeak`

---

## 🧰 Tech Stack
| Category | Tools |
|-----------|-------|
| Data Manipulation | pandas, numpy |
| Visualization | matplotlib, seaborn |
| Time Series | statsmodels, prophet |
| Deep Learning | tensorflow (optional) |

---

## 🚀 How to Run on Google Colab
1. Upload the following files to Colab:
   - `EnerVision_Energy_Forecasting.ipynb`
   - `energy_consumption_2000_rows.csv`
2. Install required libraries:
   ```bash
   !pip install prophet tensorflow statsmodels
