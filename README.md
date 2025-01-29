# ARIMA-Based Stock Price Forecasting for JPMorgan

## Project Overview
This project applies the ARIMA forecasting model to predict the stock prices of JPMorgan Chase & Co. (JPM-PD). We analyze the stock's historical data from October 2018 to June 2023 to identify trends, seasonal patterns, and potential future movements.

## Data Source
The stock price data used in this project is pulled from Yahoo Finance. It includes monthly observations of opening, closing, high, and low prices, along with the volume of stocks traded.

## Methodology
- **Data Preprocessing:** Handling missing values, transforming data, and conducting exploratory data analysis.
- **Stationarity Tests:** Using the Augmented Dickey-Fuller (ADF) test to confirm the time series stationarity.
- **Model Building:** Developing ARIMA models to best fit our time series data.
- **Diagnostics:** Checking residuals to ensure model adequacy.
- **Forecasting:** Predicting future stock prices and validating the model's effectiveness.
