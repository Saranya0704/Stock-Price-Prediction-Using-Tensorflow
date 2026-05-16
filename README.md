# 📈 Stock Price Prediction using LSTM & TensorFlow

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview
This project predicts the closing price of **Apple Inc. (AAPL)** stock
using a deep learning model built with LSTM (Long Short-Term Memory) 
neural networks and TensorFlow.

## 📊 Dataset
- Source: **Yahoo Finance** (via yfinance)
- Stock: **Apple Inc. (AAPL)**
- Period: **2015 - 2024**
- Feature: **Closing Price**

## 🧠 Model Architecture
- 2 LSTM layers (50 units each)
- 2 Dropout layers (20%)
- 2 Dense layers
- Optimizer: Adam
- Loss: Mean Squared Error

## 🛠️ Libraries Used
- TensorFlow / Keras
- yfinance
- scikit-learn
- pandas
- numpy
- matplotlib

## 🚀 How to Run
1. Clone the repository
2. Install dependencies:
   pip install yfinance tensorflow scikit-learn pandas numpy matplotlib
3. Open stock_prediction.ipynb in Google Colab or Jupyter
4. Run all cells

## 📈 Results
- The model learns historical price patterns
- Generates predictions that closely follow actual stock prices
- Evaluated using MSE and RMSE metrics


