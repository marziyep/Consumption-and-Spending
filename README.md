# Consumption-and-Spending
Here I had different approaches to the same dataset,It appears that VARMA and ARIMA did poor job compared to the simpler alternativeVAR,It leads to the fact of interdependency between Money Stock and Personal Consumption in this dataset.
I applied augmented dicky-fuller test and found that a second-order difference achieved stationarity, and auto-arima helps us to find the optimal p and q!
During this journey I profoundly realized that AIC punishes model for being too complex,even if they perform slightly better on some other metrics.
