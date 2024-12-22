# Stock Forecasting Model using LSTM (Microsoft Stock Data)
This project uses a Long Short-Term Memory (LSTM) model to forecast the price of Microsoft stock (MSFT) using historical data. The model predicts the stock price for the target day based on the last 3 days' price data. The dataset is sourced from Yahoo Finance using the `yfinance` library.

## Project Overview
The goal of this project is to build a machine learning model that predicts the future stock price of Microsoft based on past price trends. The LSTM model leverages a sliding window of the past 3 days to forecast the next day's stock price.

## Model Architecture
The core model architecture is based on LSTM (Long Short-Term Memory), which is a type of Recurrent Neural Network (RNN) designed to handle sequential data. The LSTM model uses a sliding window of 3 days of stock prices to predict the next day's closing price.

## Training and Evaluation
To train the model, the data is split into training and test sets. The LSTM model is trained on the training data, and its performance is evaluated on the test set using Mean Squared Error (MSE) or any other relevant evaluation metric.

## Results
The model’s performance is evaluated based on the prediction accuracy for the test set. Visualizations of the actual vs predicted stock prices are provided to give insight into the model's performance.
