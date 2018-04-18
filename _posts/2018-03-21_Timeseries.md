---
title: "Time Series Notes & Resources"
tags: [Data science, Resources]
---

Time series notes & resources I found useful during my time series final project at Metis.

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

## Links
### Stochastic vs ML approach
* [University of Brussels Lecture notes (thorough!)](http://www.ulb.ac.be/di/map/gbonte/ftp/time_ser.pdf)
* [Overview of ML vs Statistical time series forecasting](https://www.xenonstack.com/blog/data-science/time-series-analysis-forecasting-using-machine-learning-deep-learning)
* [Another take on ML vs Statistical approaches](https://www.quora.com/What-are-the-big-differences-between-machine-learning-techniques-e-g-SVM-vs-time-series-analysis-techniques-e-g-ARIMA-GARCH-when-looking-to-make-forecasts-of-time-series)
* [Quora on ML approaches to time series](https://www.quora.com/Data-Science-Can-machine-learning-be-used-for-time-series-analysis)

### Examples
* [4 Time series models with epidemiology data](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3914930/)
* [ARIMA prediction / simulation](https://stats.stackexchange.com/questions/132635/arima-equation-interpretation)
* [ARIMA vs Linear regression](https://stats.stackexchange.com/questions/188821/what-is-are-the-mechanical-difference-between-multiple-linear-regression-with)
* [Another take on ARIMA vs Linear regression](https://jalobe.com/blog/the-role-of-exogenous-and-lagged-variables-in-arima-and-linear-regression-models/)
* [Example using ACF / PACF to determine ARIMA order](https://www.economicsnetwork.ac.uk/showcase/cook_arima)
* [GARCH with Apple stock data](https://rstudio-pubs-static.s3.amazonaws.com/258811_b43d4c7bb2c74851b5b95f29a09c5b30.html)
