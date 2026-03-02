# Time Series Forecasting using LSTM and GRU

This project implements deep learning models for time series forecasting using Keras (TensorFlow backend).

The objective is to predict future values based on historical data using recurrent neural networks.

---

## Project Goals

- Forecast daily website traffic metrics:
  - Page Loads
  - Unique Visits
  - Returning Visits
- Forecast daily mean temperature from climate data
- Compare LSTM and GRU architectures
- Engineer seasonal features for improved predictive performance

---

## Datasets

1. daily-website-visitors.csv  
   Contains daily website traffic metrics.

2. DailyDelhiClimate.csv  
   Contains daily climate observations including mean temperature and pressure.

---

## Methodology

- Time-based train / validation / test split
- Data scaling using StandardScaler
- Sequence generation using lookback windows
- LSTM (Long Short-Term Memory) neural networks
- GRU (Gated Recurrent Unit) neural networks
- Outlier removal using the IQR method
- Seasonal feature engineering using sine/cosine encoding
- Model evaluation using validation and test sets

---

## Tools & Libraries

- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## Key Learning Outcomes

- Implemented deep learning models for sequential data
- Applied proper time series preprocessing techniques
- Compared LSTM and GRU performance
- Engineered cyclical features for seasonal modeling
- Built reproducible forecasting pipelines

---

Author: Sana Gill  
Field: Computer Science
