#🌍 AQI Prediction Using Hybrid Models (CatBoost + ARIMA)
🔹 Overview

This project focuses on predicting Air Quality Index (AQI) and PM2.5 concentration using a hybrid modeling approach that combines CatBoost and ARIMA.

The work was carried out during my association with CSIR–Central Building Research Institute (CSIR-CBRI), where the objective was to develop an accurate and reliable system for air quality monitoring and forecasting using historical pollution and weather data.

The hybrid model effectively captures both time-series patterns (trend & seasonality) and complex nonlinear relationships, leading to improved prediction performance.

#🔹 Key Features
Hybrid model combining CatBoost + ARIMA
Utilizes pollution + meteorological data
Handles trend, seasonality, and nonlinear patterns
Robust data preprocessing pipeline
Advanced feature engineering techniques
Performance evaluation using RMSE and R² score
Comparative analysis with individual models
🔹 Tech Stack
Language: Python
Libraries & Tools:
Pandas, NumPy
Scikit-learn
CatBoost
Statsmodels (ARIMA)
Matplotlib, Seaborn
🔹 Methodology
1. Data Collection
Air pollution data (AQI, PM2.5)
Weather data (temperature, humidity, wind speed, etc.)
2. Data Preprocessing
Handling missing values
Removing outliers
Time alignment of datasets
3. Feature Engineering
Lag features for time dependency
Rolling statistics (mean, variance)
Seasonal decomposition
4. Model Development
ARIMA Model
Captures temporal dependencies
Handles trend and seasonality
CatBoost Model
Handles nonlinear relationships
Works efficiently with structured data
5. Hybrid Approach
Combine predictions from ARIMA and CatBoost
Enhances overall forecasting accuracy
6. Model Evaluation
RMSE (Root Mean Square Error)
R² Score (Coefficient of Determination)
🔹 Results
Hybrid model outperformed individual models
Improved accuracy in AQI and PM2.5 prediction
Better handling of sudden pollution spikes
More stable and reliable forecasting
🔹 Applications
Smart city air quality monitoring systems
Public health advisory platforms
Environmental data analytics
Industrial pollution tracking
🔹 Future Scope
Integration with LSTM/GRU models for deep learning-based forecasting
Deployment as a web-based dashboard
Real-time prediction using IoT sensors
Geospatial AQI visualization using maps
🔹 Folder Structure
├── data/
├── notebooks/
├── models/
├── src/
├── results/
├── README.md
🔹 Acknowledgment

This project was developed as part of practical work associated with CSIR–Central Building Research Institute (CSIR-CBRI), contributing towards research in environmental monitoring and predictive analytics.

Hybrid AQI prediction system using CatBoost and ARIMA, developed during work at CSIR-CBRI, leveraging weather and pollution data for accurate air quality forecasting.
