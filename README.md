# Stock Price Prediction with LSTM

This project demonstrates how to use an LSTM model to predict stock prices based on historical data. The model learns temporal dependencies in the data and predicts future stock prices.

## Features
- **Dataset**: Supports any stock price dataset with a `Close` column (e.g., data from Yahoo Finance).
- **LSTM Model**: A 2-layer LSTM with a fully connected output layer.
- **Evaluation**: Visualizes predicted vs. actual stock prices and calculates RMSE.

## How to Run
1. Prepare your dataset:
   - Download stock price data from Yahoo Finance or a similar source.
   - Ensure the file contains a `Close` column for the stock prices.
