# SP500-Forecasting-SARIMA-CNN-LSTM

## Predicting S&P 500: A Hybrid Approach with SARIMA and LSTM

This repository explores the prediction of S&P 500 index using a hybrid approach combining SARIMA and LSTM models. It aims to provide insights into the application of time series analysis and machine learning for financial forecasting.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Models](#models)
    - [SARIMA](#sarima)
    - [CNN-LSTM](#cnn-lstm)
- [Contributing](#contributing)

## Introduction

Predicting stock market movements is a complex and challenging task with significant implications for investors and financial institutions. This project investigates the effectiveness of two distinct modeling approaches: SARIMA, a traditional statistical model, and LSTM, a deep learning approach. By combining these models, we aim to leverage their strengths and potentially achieve better predictive performance.

## Data

The project utilizes historical data of the S&P 500 index obtained using the `yfinance` library. The data includes daily closing prices, as well as other relevant features such as volume, high/low prices, and moving averages. The data is preprocessed, scaled, and split into training and testing sets.

## Models

### SARIMA

SARIMA (Seasonal Autoregressive Integrated Moving Average) is a statistical model commonly used for time series forecasting. It captures autocorrelations, seasonality, and trends in the data to make predictions.

### LSTM

LSTM Long Short-Term Memory (LSTM) networks. LSTMs capture temporal dependencies, making them suitable for time series data.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
