# 🌤️ Weather Forecasting - Temperature Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting temperature using historical weather data and machine learning techniques. The goal is to build a regression model that can forecast temperature based on various environmental features like humidity, pressure, wind speed, and date-based components.

---

## 🧠 Technologies Used

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📁 Dataset

- File: `cleaned_weather.csv`
- Columns include:
  - Temperature (Target Variable)
  - Date (converted to day, month, year)
  - Humidity, Wind Speed, Pressure, etc.
- Missing values are handled during preprocessing.

---

## 🚀 Features

- Data cleaning and preprocessing
- Feature engineering (date extraction)
- Categorical encoding
- Model training using **Random Forest Regressor**
- Evaluation using R² Score and RMSE
- Visualization of Actual vs Predicted Temperature

---

## 📊 Model Performance

The model is evaluated on the test set using:
- **R² Score**
- **Root Mean Square Error (RMSE)**

These metrics give a measure of how close the predictions are to the actual temperatures.

---

## 📌 How to Run

1. Clone the repository or download the code.
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
