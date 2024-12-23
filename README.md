# MSFT Stock Price Prediction Using LSTM and GRU

This repository contains code and results for predicting Microsoft (MSFT) stock prices using Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) neural networks built with PyTorch.

## Project Overview

The project evaluates the effectiveness of LSTM and GRU models in predicting the stock market by training the models on historical MSFT stock data. Various hyperparameters and model configurations were explored, and the results are summarized in the text files.

## Motivation

The project that I developed was the part of my Microsoft Turkey FY 24 Summer Internship program. The aim of the project was to apply and develop machine learning techniques in real-life financial data.

### Models Implemented:
- **LSTM (Long Short-Term Memory)**
- **GRU (Gated Recurrent Unit)**

## Dataset

The historical stock prices for MSFT were sourced from publicly available data. The data includes features like:
- Opening price
- Closing price
- Highest price
- Lowest price
- Volume

The models were trained on historical closing prices to predict future stock movements.

## Results

### LSTM Model Performance

**Best LSTM Configuration**
- **Train MSE**: 0.77
- **Test MSE**: 0.77
- **Test RMSE**: 0.52
- **Test MAPE**: 1.05%

### GRU Model Performance

**Best GRU Configuration:**
- **Train MSE**: 0.10
- **Test MSE**: 0.28
- **Test RMSE**: 0.53
- **Test MAPE**: 0.66

## File Structure

- `MSFT_2006-01-01_to_2018-01-01.csv`: The dataset of Microsoft stock prices.
- `lstm.ipynb`: Jupyter Notebook implementing the LSTM model.
- `gru.ipynb`: Jupyter Notebook implementing the GRU model.
- `LSTM_scores_smalldataset.txt`: LSTM model performance history.
- `GRU_scores_smalldataset.txt`: GRU model performance history.

## Requirements

- Python 3.8+
- PyTorch
- NumPy
- Pandas
- Matplotlib


