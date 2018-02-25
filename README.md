# Time-Series-Demand-Forecasting
- This problem was an interview challenge
- Problem: Solve the Time Series forecasting problem to forecast demand of multiple time series
- Ipython notebook is self explanatory to explain the problem
- Highlights of the problem:
  - Ensemble Time series approach
  - Used lags as features to implement time series algorithms
  
  Issues: Later on I found out that I did not scale the Arima prediction back to its original scale. Once, you difference the series in ARIMA, you have to de-differnce the series back to get accurate predictions.
