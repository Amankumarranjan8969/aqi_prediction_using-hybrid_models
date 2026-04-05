# 🌍 AQI Prediction Using Hybrid Models (CatBoost + ARIMA)

## 🔹 Overview
This project focuses on predicting **Air Quality Index (AQI)** and **PM2.5 concentration** using a hybrid modeling approach that combines **CatBoost** and **ARIMA**.

The work was carried out during my association with **CSIR–Central Building Research Institute (CSIR-CBRI)**, where the objective was to develop an accurate and reliable system for **air quality monitoring and forecasting** using historical pollution and weather data.

The hybrid model effectively captures both **time-series patterns (trend & seasonality)** and **complex nonlinear relationships**, leading to improved prediction performance.

---

## 🔹 Key Features
- Hybrid model combining **CatBoost + ARIMA**
- Utilizes **pollution + meteorological data**
- Handles **trend, seasonality, and nonlinear patterns**
- Robust **data preprocessing pipeline**
- Advanced **feature engineering techniques**
- Performance evaluation using **RMSE and R² score**
- Comparative analysis with individual models

---

## 🔹 Tech Stack
- **Language:** Python
- **Libraries & Tools:**
  - Pandas, NumPy
  - Scikit-learn
  - CatBoost
  - Statsmodels (ARIMA)
  - Matplotlib, Seaborn

---

## 🔹 Methodology

### 1. Data Collection
- Air pollution data (AQI, PM2.5)
- Weather data (temperature, humidity, wind speed)

### 2. Data Preprocessing
- Handling missing values
- Removing outliers
- Time alignment of datasets

### 3. Feature Engineering
- Lag features
- Rolling statistics
- Seasonal decomposition

### 4. Model Development
- **ARIMA Model**
  - Captures time dependency
  - Handles trend and seasonality

- **CatBoost Model**
  - Captures nonlinear relationships
  - Works well with structured data

### 5. Hybrid Approach
- Combine outputs of ARIMA and CatBoost
- Improves prediction accuracy

### 6. Evaluation Metrics
- RMSE (Root Mean Square Error)
- R² Score

---

## 🔹 Results
- Hybrid model outperformed individual models
- Improved AQI prediction accuracy
- Better handling of pollution spikes
- Stable forecasting performance

---

## 🔹 Applications
- Smart city monitoring
- Public health systems
- Environmental analytics
- Industrial pollution tracking

---

## 🔹 Future Scope
- Use LSTM/GRU models
- Deploy as web dashboard
- Real-time IoT integration
- Add map-based visualization
- climate control

---

## 🔹 Folder Structure
project-root/
│── data/
│── notebooks/
│── models/
│── src/
│── results/
│── README.md
---

## 🔹 Acknowledgment
This project was developed during my work with **CSIR–Central Building Research Institute (CSIR-CBRI)**.

---

## 🔹 Short Description
Hybrid AQI prediction system using CatBoost and ARIMA with weather and pollution data for accurate forecasting.
