# Stock Price Prediction using LSTM

This collaborative project was developed as part of the Erdos Institute Data Science Boot Camp – Summer 2022, by Team Random.  
We implemented a deep recurrent neural network LSTM  to predict stock prices for AMD, Facebook (FB), Apple (AAPL), Tesla (TSLA), and Starbucks (SBUX). 
The project demonstrates how deep recurrent neural network LSTM can be applied to time series data for financial forecasting.

---

## Model Overview

We used a Keras-based Sequential LSTM model with the following architecture:

- Two LSTM layers with 64 and 32 units respectively
- Dropout: 20%
- Activation Function: ReLU
- Optimizer: Adam
- Loss Function: Mean Squared Error (MSE)
- Input Shape: 3D tensor [samples, time steps, features]
- Epochs: 3
- Batch size: 1

---

##  Data

- Source: Yahoo Finance
- Time Range: June 2, 2012 – June 2, 2022
- Features: Daily Opening Prices
- Preprocessing:
  - Training set: up to January 24, 2022
  - Testing set: last 90 days (Jan 25 – Jun 2, 2022)
  - Normalization: `StandardScaler` from `scikit-learn`
---
## The Jupiter notebook file containing our work is named "main.ipynb".

## 📊 Results
Full results and visualizations are available in the project presentation slide"Report".

---

