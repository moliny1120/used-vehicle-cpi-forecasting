# STAT 429 Final Project – Used Vehicle CPI Forecasting

This project studies the dynamics of the U.S. Used Vehicle Consumer Price Index (CPI) and compares multiple modeling approaches for short-term forecasting.

## Data
Monthly data from January 2000 to April 2025 were obtained from FRED, including:
- Used Vehicle CPI
- New Vehicle CPI
- Motor Fuel CPI
- Federal Funds Effective Rate
- COVID-19 dummy variable

## Methods
We compared four models:
1. Multiple Linear Regression (OLS)
2. Weighted Least Squares (WLS)
3. Regression with lagged predictors based on CCF analysis
4. SARIMA time series model

Stationarity was assessed using the Augmented Dickey-Fuller test, and model selection was guided by AIC and BIC.

## Results
Among all models, ARIMA(0,1,2) achieved the best forecasting performance, with:
- Lowest AIC and BIC
- Stable residuals
- Out-of-sample MAPE below 1%

## Files
- `report/STAT429_Final_Project.pdf`: Final report
- `code/`: R scripts for data cleaning, modeling, and visualization
- `data/`: Raw and test datasets from FRED

## Authors
Samuel Wu, Molin Yang, Rongsheng Zhang
