# rainfall-prediction-using-ML

A Streamlit web application that predicts the likelihood of rainfall based on weather data using multiple machine learning models. This project supports model training, evaluation, and prediction based on historical or manually entered weather data.

## 🚀 Features

- Load and preprocess rainfall dataset
- Train models: Logistic Regression, XGBoost, and SVC
- Handle imbalanced data using oversampling
- Choose imputation strategy for missing values
- Standardize data using `StandardScaler`
- Automatically evaluate models and select the best one
- Save and reload the best model
- Predict rainfall by:
  - Selecting a date from the dataset
  - Manually entering feature values


## 🧪 ML Models Used

- Logistic Regression
- XGBoost Classifier
- Support Vector Classifier (SVC)

## 🧪 ML Models Used

- Logistic Regression
- XGBoost Classifier
- Support Vector Classifier (SVC)

Dataset
The dataset should be a CSV file named Rainfall.csv.

Required columns include:

day (date)

rainfall (target variable: "yes" or "no")

Any number of weather-related features like humidity, wind, pressure, etc.

Columns maxtemp and mintemp will be dropped automatically.
