# 📊 Daily Website Visitors Forecasting

Time Series Forecasting using Recurrent Neural Networks (RNN) – LSTM

---

## 📌 Overview

This project focuses on forecasting daily website traffic using time series modeling techniques, specifically Long Short-Term Memory (LSTM) networks. The goal is to capture complex temporal patterns such as seasonality, trends, and user behavior over time.

---

## 📂 Dataset

Source: https://www.kaggle.com/datasets/bobnau/daily-website-visitors  

The dataset contains 5 years of daily traffic data from a statistical forecasting website (statforecasting.com), including:

- Page Loads  
- Unique Visitors  
- First-Time Visitors  
- Returning Visitors  

Total observations: **2,167 days**  
Date range: **September 14, 2014 – August 19, 2020**

---

## 📊 Problem Statement

The objective is to build models capable of predicting website traffic, including:

- 1-day ahead forecasts  
- 7-day ahead forecasts  
- Weekly traffic predictions  

This involves handling time series characteristics such as:
- Day-of-week seasonality  
- Academic calendar trends  
- Temporal dependencies  

---

## 🧠 Approach

- Data preprocessing and time series transformation  
- Feature scaling and sequence generation  
- Implementation of LSTM (RNN) model  
- Model training and evaluation  
- Forecasting future traffic patterns  

---

## 🔍 Key Insights

- Website traffic exhibits strong weekly seasonality  
- Patterns align with academic schedules and user behavior  
- LSTM models effectively capture temporal dependencies in the data  

---

## 🛠️ Tools & Technologies

- Python  
- TensorFlow / Keras  
- Pandas, NumPy  
- Matplotlib / Seaborn  

---

## 🚀 Future Improvements

- Compare LSTM performance with ARIMA/ETS models  
- Hyperparameter tuning for improved accuracy  
- Incorporate additional external features (e.g., holidays, events)  
