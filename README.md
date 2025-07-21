# 🧠 Internship Projects: Wine Quality Classification & Stock Price Prediction

This repository contains two major machine learning projects completed as part of an internship. These projects demonstrate skills in supervised learning, model evaluation, deep learning, and time-series forecasting.

---

## 📌 Project 1: Wine Quality Classification

### 🎯 Objective:
To build a classification model that predicts the quality of wine based on various physicochemical properties.

### 🗂 Dataset Overview:
- Source: UCI Machine Learning Repository  
- Features: Acidity, Alcohol content, Sugar level, pH, Sulphates, etc.  
- Target Variable: Wine quality (integer scale from 0 to 10)

### 🔍 Workflow:

- **Data Cleaning & Preprocessing:**
  - Handled missing values and outliers
  - Standardized features using a scaling technique
  - Converted quality into categorical bins (if needed for classification)

- **Model Development:**
  - Used Random Forest Classifier as the primary model
  - Applied GridSearchCV for hyperparameter tuning (optimized number of trees)
  - Performed 10-fold cross-validation to ensure robust accuracy estimation

- **Model Evaluation:**
  - Evaluated using accuracy, precision, recall, F1-score, and confusion matrix
  - Achieved high classification accuracy with well-balanced performance across classes

### 📈 Outcome:
- Best accuracy obtained using a Random Forest with optimized number of estimators  
- Alcohol, Volatile Acidity, and Sulphates were among the most influential features

---

## 📌 Project 2: Stock Price Prediction Using LSTM

### 🎯 Objective:
To forecast stock prices using past historical data and deep learning techniques (LSTM networks).

### 🗂 Dataset Overview:
- Source: Yahoo Finance (e.g., Apple, TCS, etc.)
- Features: Open, High, Low, Close, Volume
- Data Type: Time series (daily frequency)

### 🔍 Workflow:

- **Data Collection & Preprocessing:**
  - Collected data using `yfinance`
  - Applied Min-Max scaling to normalize price ranges
  - Converted data into supervised learning format using windowing techniques

- **Model Architecture:**
  - Built a 4-layer LSTM (Long Short-Term Memory) network
  - Used dropout layers for regularization to prevent overfitting
  - Compiled using Adam optimizer and mean squared error as the loss function

- **Model Training:**
  - Trained on sequences of stock prices for temporal pattern learning
  - Used closing prices as the prediction target
  - Validation was done visually and through RMSE (Root Mean Squared Error)

### 📈 Outcome:
- The LSTM model effectively captured long-term dependencies in stock price movements  
- Outperformed traditional regression methods in both trend prediction and error metrics

---

## 🎓 Internship Outcomes

- Gained hands-on experience in both classification and time series forecasting
- Applied both traditional ML models and advanced deep learning architectures
- Practiced model evaluation, hyperparameter tuning, and feature engineering

---

