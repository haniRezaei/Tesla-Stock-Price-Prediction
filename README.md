# Tesla-Stock-Price-Prediction
Tesla Stock Price Forecasting Using LSTM
This project demonstrates how to predict Tesla's stock prices using an LSTM (Long Short-Term Memory) neural network model.

Forecast the closing price of Tesla stocks using past values. The dataset includes Tesla’s historical stock prices from 2010 to 2020. The goal is to build a model that learns from past price behavior and generalizes well to unseen future prices.

We use an LSTM-based neural network trained on the last 20 days (lookback = 20) of normalized closing prices.

Input: Sequences of 20 historical stock prices

Output: Forecast of the next day's price

Loss Function: Mean Squared Error (MSE)

Optimizer: Adam

Model Evaluation: Root Mean Squared Error (RMSE) and loss curves

Training RMSE: ~13.12 USD

Test RMSE: ~29.85 USD


While the model performs well on the training set, it starts to diverge slightly during high-volatility periods (late 2019), which is expected in time series forecasting.


