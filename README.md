# ⏱️ Time Series Forecasting Model Comparison

This repository contains multiple time series forecasting models implemented using the same dataset to compare their performance and forecast accuracy. The primary goal is to identify which model performs best for energy demand forecasting using historical data.

## 📂 Files Included

| File Name                      | Description |
|-------------------------------|-------------|
| `PJME_hourly.csv`             | Dataset used for all models (Hourly PJME Energy Demand). |
| `ARIMA_Time_Series.ipynb`     | Time series forecasting using ARIMA. |
| `SARIMA_Time_Series.ipynb`    | Forecasting using SARIMA (Seasonal ARIMA). |
| `RNN_Time_Series.ipynb`       | Forecasting using a basic Recurrent Neural Network. |
| `LSTM_Time_Series.ipynb`      | Forecasting using LSTM (Long Short-Term Memory network). |
| `GRU_Time_Series.ipynb`       | Forecasting using GRU (Gated Recurrent Unit network). |
| `Time_Series_PJME_Hourly.ipynb` | Data preprocessing and visualization notebook. |
| `multiTimeline.csv`           | Alternate dataset for experimentation. |
| `AirPassengers.csv`           | Alternate dataset for experimentation. |
| `Time_series_MultiTimeline.ipynb` | Model implementation on alternate dataset. |
| `Time_Series_AirPassengers.ipynb` | Classic time series modeling using AirPassengers data (for comparison/study). |

## 🧠 Models Implemented

1. **ARIMA** – Traditional statistical model for forecasting.
2. **SARIMA** – Seasonally adjusted ARIMA.
3. **RNN** – Basic recurrent neural network.
4. **LSTM** – Deep learning-based model suited for long-term dependencies.
5. **GRU** – Similar to LSTM but more computationally efficient.

## 📊 Objective

- Use the same dataset (`PJME_hourly.csv`) across all models.
- Train, validate, and compare results.
- Analyze forecasting accuracy and computational efficiency.
- Determine which model provides the best real-world performance for energy demand prediction.

## 📌 Key Results

- Performance metrics like RMSE, MAE, and visual plots were used to evaluate each model.
- Deep learning models (LSTM and GRU) handled long-term patterns better.
- ARIMA/SARIMA performed well with fewer resources but struggled with seasonality compared to deep learning models.

## 🛠️ Tools Used

- Python (NumPy, Pandas, Matplotlib, Seaborn)
- Statsmodels (for ARIMA/SARIMA)
- TensorFlow / Keras (for RNN, LSTM, GRU)
- Google Colab

## 🔗 Connect with Me

Feel free to check the LinkedIn post highlighting this project and my learnings: https://www.linkedin.com/in/sowjanya-kiran-datascientist/ 
---
