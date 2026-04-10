Title:Stock Price Prediction and Forecasting Using
Stacked LSTM Deep Learning

Abstract : Forecasting equity prices from historical market
data remains a deeply complex task owing to the stochastic,
non-stationary, and non-linear character of financial time-series.
Conventional statistical forecasters — including ARIMA and
ordinary least-squares regression — lack the representational
power required to model such dynamics. This work addresses the
limitation by constructing a multivariate deep-learning forecaster
for Apple Inc. (AAPL) built on a two-layer stacked Long ShortTerm Memory (LSTM) network trained on six years of OpenHigh-Low-Close-Volume (OHLCV) data downloaded from Yahoo
Finance (January 2018 to January 2024, totalling 1 509 daily
records). Before modelling, an exploratory phase quantifies longterm price trends through moving-average overlays and interfeature dependencies through a Pearson correlation matrix.
Dropout regularisation is applied at each recurrent layer to
suppress overfitting. On a held-out test window of 302 trading
days the model records an RMSE of 2.53 USD, MAE of 2.02 USD,
and an R
2
coefficient of 0.9737, equivalent to a mean absolute percentage error below 1.5%. Residual analysis reveals a near-zero
mean bias and approximately Gaussian error spread. The paper
also demonstrates 30-day forward extrapolation, confirming the
framework’s suitability for short-horizon investment planning.
Index Terms—stacked LSTM, stock price forecasting, OHLCV,
deep learning, time-series, residual analysis, AAPL


Team Members
- Padamati Hemasri  
- M Sai Dheeraj  
- M Mounish  
- M Rakshith Reddy
