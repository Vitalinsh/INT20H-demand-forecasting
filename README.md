# INT20H-demand-forecasting

Area of the city was divided into 61 districts, 44 of them are used for demand forecasting (others are dropped because of absence of orders).

In this project two main models are implemented to predict demand for 24 hours and 7 days:
- ARIMA model
- Holt-Winters model

Both models show good result, but Holt-Winters model have smaller MAE (mean absolute error).

Apart from this, several models for prediction demand for 1 hour are implemented:
- dense neural network
- gradient boosting regressor

They are simpler then Holt-Winters and use window of size 168 hours (only one last week) to make prediction.



