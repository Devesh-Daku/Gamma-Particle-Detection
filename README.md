# Seoul Bike Demand Forecasting 🚴‍♂️📈

This project aims to predict bike rental demand in Seoul, South Korea, based on environmental and seasonal data using regression techniques. The dataset was obtained from the UCI Machine Learning Repository.

## 📁 Dataset Overview

The dataset includes hourly rental data and related features such as:
- Temperature
- Humidity
- Wind speed
- Visibility
- Dew point temperature
- Solar radiation
- Rainfall
- Snowfall
- Date & time features

## 🧹 Data Preprocessing

- Cleaned null and inconsistent entries.
- Converted date/time columns to extract meaningful features (hour, day, month).
- Dropped irrelevant or highly correlated features based on exploratory analysis.

## 📊 Exploratory Data Analysis (EDA)

Used **Pandas**, **Matplotlib**, and **Seaborn** to:
- Visualize seasonal and hourly rental patterns.
- Analyze correlation between demand and weather factors.
- Understand distribution and outliers in the data.

## 🔍 Feature Engineering

- Removed redundant features that didn’t improve performance.
- Normalized numerical features for neural network input.

## ⚙️ Regression Models

### 📐 Linear Regression
- Applied multiple linear regression models using individual and combined features.
- Evaluated performance using metrics like MAE, RMSE, and R² Score.

### 🧠 Neural Network Regression (TensorFlow)
- Built a basic single-layer neural network model to predict bike demand.
- Compared results with linear regression to assess improvements.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib / Seaborn

## 📌 Future Improvements

- Use LSTM or GRU models for time series forecasting.
- Add more contextual features (holidays, events).
- Deploy the model as an API or interactive dashboard.

---

This project highlights end-to-end demand forecasting using real-world time series data and demonstrates both classical and deep learning regression techniques.
