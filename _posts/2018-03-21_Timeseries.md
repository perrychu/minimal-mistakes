## Some notes on workflow for time-series:

### Typical steps:
1) Visualize time series
2) Stationarize time series
3) Plot ACF / PACF
4) Build ARIMA model
5) Predict

### What makes a stationary TS? (2)
1) Mean is constant (required)
2) Variance is constant (required)
3) Frequency is constant (sometimes)
  - Implies seasonality
  - Not applicable for non-repeating patterns
  
### What are ACF / PACF? (3)
1) ACF = correlation with time lag (t-i), used to describe MA
2) PACF = correlation with time lag (t-i) with effect of (t-1)...(t-i+1) removed, used to describe AR

##### Steps:
1) Plot
2) Look at the CF(s) which decrease to zero
3) Take # lags above X away from zero (x is threshold parameter)

### ARIMA (4)
- AR: X(t) = a(X(t-1)) + err(t)
- MA: X(t) = b(err(t-1)) + err(t)
