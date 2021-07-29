# ATM_ForecastML
Machine Learning model for ATM forecasting. This short project tries to expand what are known to be good estimators for highly stochastic processes, in this case ATM Cash Demand.

First approach is LSTM Recurrent Neural Net. Here it was discovered to be a highly precise estimator but expensive (GPU usage). Second approach is ARIMA method. Less expensive method with great precision on short forecasts (1 to 3-day forecast).
