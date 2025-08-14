# DataScienceResearchProjectB
This repository contains files for Data Science Project B- Detecting Anomalies in Satellite Orbit Data- Vadde Venkata Kamala Sindhoori- a1905610- University of Adelaide

# Anaomaly Detection in Satellite Orbit Data using ARIMA & XGBoost

## 📌 Project Overview
This project implements **time series forecasting** and **residual-based anomaly detection** for satellite maneuver detection using two different modeling approaches:
- **ARIMA (AutoRegressive Integrated Moving Average)**
- **XGBoost (Extreme Gradient Boosting)**

The analysis is performed on multiple satellites, with each notebook tailored to a specific dataset. The primary goal is to:
1. Preprocess satellite orbital data.
2. Fit forecasting models (ARIMA or XGBoost).
3. Calculate residuals between forecasts and actual observations.
4. Perform Qualitative Analysis
5. Apply threshold-based anomaly detection to identify possible maneuvers.
6. Evaluate detections against ground truth maneuver timestamps using a fair and robust evaluation framework

---

## 📂 File Structure

### **ARIMA-based Notebooks**
- `ARIMA_Fengyuan_2E_Notebook.ipynb`
- `ARIMA_Fengyun_2F_Notebook.ipynb`
- `ARIMA_Fengyun_2H_Notebook.ipynb`
- `ARIMA_SARAL_Notebook.ipynb`
- `ARIMA_Sentinel_3A_Notebook.ipynb`
- `Refactored_ARIMA_Code.ipynb`

### **XGBoost-based Notebooks**
- `XGBoost_Fengyun_2E.ipynb`
- `XGBoost_Fengyun_2F.ipynb`
- `XGBoost_Fengyun_2H.ipynb`
- `XGBoost_SARAL.ipynb`
- `XGBoost_Sentinel_3A.ipynb`
- `Refactored_XGBoost_Code.ipynb`

---

## ⚙️ Requirements

### **Python Packages**
Install the required packages:

pip install pandas numpy matplotlib statsmodels scikit-learn xgboost scipy pmdarima

