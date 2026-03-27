# Oil-Gas-Price-Forecasting-with-SARIMA-and-SARIMAX

## 📌 Problem Statement
Energy price forecasting is critical for economic planning and decision-making. This project compares SARIMA and SARIMAX models to predict oil and gas prices using time series data.

Time series forecasting of oil and gas prices using SARIMA and SARIMAX models on FRED data, with performance comparison and model evaluation.
This project focuses on time series forecasting of oil and gas prices using classical statistical models, specifically SARIMA and SARIMAX, applied to publicly available data from the Federal Reserve Economic Data (FRED) database.

The objective of this analysis is to:

Model and forecast energy price trends
Compare the performance of univariate (SARIMA) vs multivariate (SARIMAX) approaches
Evaluate how incorporating external variables improves forecasting accuracy

## 12 Step Forecast Comparison 
![Forecast](image/12step_forecast_comparison.JPG)

## 🔍 Dataset
The dataset includes:

Oil price data (e.g., WTI crude)
Gasoline price data
Time-indexed observations sourced from FRED

## ⚙️ Methods
Time series preprocessing (date alignment, handling frequency differences)
Stationarity testing (ADF test)
Differencing and transformation
Model development:
SARIMA (Seasonal AutoRegressive Integrated Moving Average)
SARIMAX (SARIMA with exogenous variables)
Model evaluation using metrics such as MSE

## 📊 Key Insights
SARIMAX provides improved predictive performance when incorporating related external variables (e.g., oil → gas relationship)
Time step selection and model configuration significantly impact forecasting accuracy
Small differences in error metrics can still indicate meaningful model improvements
🧠 Tools & Technologies
Python
Pandas / NumPy
Matplotlib
Statsmodels

## ⚙️ Model Comparison
- SARIMA: Univariate model using historical data  
- SARIMAX: Incorporates external variables (oil → gas relationship)  
