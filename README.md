# 🌍 Atmospheric CO₂ Level Prediction using R

This project analyzes atmospheric CO₂ concentration data over time using various machine learning and time series models in R. It includes data cleaning, preprocessing, modeling, and performance evaluation.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `raw_dataset.csv` | Original unprocessed CO₂ dataset |
| `clean_dataset.csv` | Cleaned and preprocessed dataset used for modeling |
| `co2_analysis.Rmd` | R Markdown file with complete analysis and visualizations |

---

## 📌 Project Highlights

- 📊 Time-series forecasting of atmospheric CO₂ levels
- 🧹 Data cleaning & transformation from raw input
- 🧠 Comparison of 5 different models:
  - Linear Regression
  - Random Forest
  - ARIMA
  - Prophet
  - XGBoost
- ✅ Evaluation metrics: RMSE and MAE
- 📉 Visualizations comparing actual vs predicted values

---

## 🔗 Dataset

👉 **Raw Dataset Download**: [Click here to access](https://climatedata.imf.org/pages/climatechange-data)

---

## 🧠 Model Performance

| Model              | RMSE     | MAE     |
|-------------------|----------|---------|
| Linear Regression | 33.56    | 3.16    |
| Random Forest     | 36.57    | 19.48   |
| ARIMA             | 33.47    | 5.54    |
| Prophet           | 33.51    | 4.83    |
| XGBoost           | 35.34    | 16.18   |

---

## 🛠 How to Use

1. Open the `.Rmd` file in **RStudio**
2. Ensure required packages are installed:
   ```r
   install.packages(c("tidyverse", "lubridate", "forecast", "prophet", "randomForest", "xgboost", "Metrics"))
