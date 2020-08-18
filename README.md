# Time Series Assignment - CAD-JPY

## Background

The financial departments of large companies often have to make foreign currency transactions when doing international business, while hedge funds are also interested in anything that will provide an edge in predicting currency movements. Hence, both are always eager to gain a better understanding of the future direction and risk of various currencies. 

In this assignment, you will test the many time series tools that you have learned in order to predict future movements in the value of the Canadian dollar versus the Japanese yen.

You will gain proficiency in the following tasks:

1. Time series forecasting
2. Linear regression modelling

- - -

### Files

[Time-Series Starter Notebook](time_series_analysis.ipynb)

[Linear Regression Starter Notebook](regression_analysis.ipynb)

- - -

### ARMA Model

The coefficient of the constant and AR2 term is close to zero and the P-Value in ‘P>|z|’ column is highly insignificant. It should ideally be less than 0.05 for the respective X to be significant. Apart from that AIC and BIC value can be improved.

Overall, ARMA model can be improved using different order.

- - -

### ARIMA Model

The coefficient of the constant and AR2, AR3, AR4 term is close to zero and the P-Value in ‘P>|z|’ columns are highly insignificant. It should ideally be less than 0.05 for the respective X to be significant. AIC and BIC values are slightly improved compared to ARMA model.

Overall, ARIMA model can be improved using different order.

- - -

### GARCH Model

P-values for GARCH and volatility forecasts tend to be much lower than our ARMA/ARIMA return and price forecasts. In particular, here we have all p-values of less than 0.05, except for alpha(2), indicating overall a much better model performance.

- - -

### Linear Regression Model

- In-sample Root Mean Squared Error (RMSE): 0.841994632894117

- Out-of-Sample Root Mean Squared Error (RMSE): 0.6445805658569028

The out-of-sample RMSE is lower than the in-sample RMSE. RMSE is typically lower for training data, but is higher in this case.



