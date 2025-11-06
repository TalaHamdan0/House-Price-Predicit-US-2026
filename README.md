# House Prices Prediction in the USA (2026)
Overview

This project predicts house prices in the United States for the year 2026 using historical Zillow data and Machine Learning techniques.
The main goal is to forecast future prices for different regions based on past trends.

Features

Data cleaning and transformation: Handling missing values, reshaping data to long format.

Feature engineering:

Lags (lag_1, lag_3, lag_6)

Rolling averages (rolling_3)

Year and month columns for time series forecasting

Modeling:

RandomForestRegressor used for prediction

Train/test split based on date (before 2024 → train, 2024–2025 → test)

Evaluation:

Metrics: MAE, RMSE

Example result: MAE ≈ 583$, RMSE ≈ 2233$

Results

Predictions for multiple cities in 2026

Visualizations show predicted price trends over the year for each city

How to Run

Install required packages:

pip install pandas numpy matplotlib scikit-learn


Load the dataset (Zillow historical house prices).

Run the notebook or Python script to clean data, create features, train the model, and generate predictions.

Visualize results using the provided plotting functions.

Example Plot

Skills Learned

Data cleaning and preprocessing

Time series feature engineering

Regression modeling using RandomForest

Data visualization and result interpretation
