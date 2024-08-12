# EU-ETS-Spot-Volume-Modeling-and-Forecasting

The aim of this project is to model and predict the daily trading volumes of
carbon emission allowances in the context of EU ETS (European Union Emission Trading System). The analysis is performed by considering different autoregressive models,
eventually with ARCH/GARCH structure since there is evidence of volatility clustering. After selecting the model with the best information criteria, we use it to predict
out-of-sample data obtaining an error of 3% in terms of magnitude of the volumes with
respect to the real data. Finally, we find that adding the prices of coal as exogenous
variable, is statistically significant for EU ETS volume prediction.
