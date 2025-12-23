# 📈Task: 06 – Stock Price Prediction using LSTM

## 📌 Project Overview
This project is part of the RISE Internship – Machine Learning & AI Project List.  
The objective is to predict stock prices using LSTM (Long Short-Term Memory) neural networks based on historical stock market data.

---

## 🎯 Objective
To build a deep learning model using **LSTM** that learns time-series patterns from historical stock prices and predicts future trends, demonstrating a real-world application of AI in finance.

---

## 🧠 Technologies Used
- Python  
- Google Colab  
- TensorFlow / Keras  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  
- Yahoo Finance API (`yfinance`)

---

## 📊 Dataset Information
- **Source:** Yahoo Finance  
- **Stock Used:** Apple Inc. (AAPL)  
- **Data Type:** Historical stock prices (Closing Price)  
- **Time Period:** 2015 – 2024  

The dataset is fetched dynamically using the `yfinance` library.

---

## ⚙️ Project Workflow
1. Import required libraries  
2. Download historical stock data from Yahoo Finance  
3. Select and visualize closing price data  
4. Normalize data using MinMaxScaler  
5. Create time-series sequences for LSTM  
6. Split data into training and testing sets  
7. Build a deep LSTM model  
8. Train the model  
9. Predict stock prices  
10. Visualize **Actual vs Predicted Prices**

---

## 🏗️ LSTM Model Architecture
- 3 LSTM layers with Dropout
- Dense output layer
- Optimizer: Adam
- Loss Function: Mean Squared Error (MSE)

---

## 📈 Results
- The model successfully learns stock price trends
- Visualization clearly compares actual and predicted prices
- Demonstrates effective time-series forecasting using deep learning

---

Author: Adhi Narayan  
Internship: RISE 3.0 — Machine Learning and AI
