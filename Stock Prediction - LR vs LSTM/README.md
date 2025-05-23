# 📈 Stock Price Prediction – Linear Regression vs LSTM

## 📋 Overview
This project compares two approaches — traditional Linear Regression and an LSTM neural network — to predict Brent Oil prices using historical data. The goal is to evaluate model performance using RMSE and assess their suitability for time series forecasting.

## 📅 Project Summary
- Dataset: Brent Oil prices (20 years)
- Methods: Feature engineering, supervised ML, deep learning (LSTM)
- Focus: Predictive accuracy and model interpretability

## 🧰 Tools Used
- Python (Pandas, NumPy, Scikit-learn, Keras)
- Jupyter Notebook
- Excel (for quick data inspection)
- Matplotlib (for visualisation, if used)

## 🔍 Approach

### 🔹 Linear Regression
- Features: MA3 and MA9 (moving averages)
- Output: Future Brent Oil price
- Performance:
  - R² score: 0.9991
  - RMSE: ~0.92

### 🔹 LSTM (Long Short-Term Memory)
- Input: Time-sequenced Brent Oil prices
- Scaling: MinMaxScaler + inverse transform
- Performance:
  - Train RMSE: 0.99
  - Test RMSE: 1.78
- Observation: Slight overfitting

## 📂 Files & Access

### 📁 Code
- 🧪 [LSTM Model](./Code/LSTM.ipynb)
- 📄 [Linear Regression Model](./Code/Linear%20regression.ipynb)

### 📁 Data
- 📊 [Brent Oil Dataset](./Data/BrentOilPrices.csv)

### 📁 Report
- 📄 [Full Report (PDF)](./Report/Report.pdf)

## 🧠 Skills Demonstrated
- Supervised learning using moving averages
- Neural network modelling with LSTM
- Time series data transformation and reshaping
- Performance comparison using RMSE
- Model selection and overfitting analysis

---

> 📁 [Return to Main Portfolio](..)
