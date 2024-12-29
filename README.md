# Microsoft Stock Price Prediction Using Stacked LSTM

## Overview
This project predicts Microsoft's stock prices using historical data from **1986 to 2024**. The dataset includes daily adjusted closing prices and was preprocessed to create sequences suitable for time-series modeling. A **Stacked LSTM (Long Short-Term Memory)** model was used to capture long-term dependencies and trends in the stock data.

---

## Features
- **Data Source**: Historical stock price data for Microsoft, spanning nearly four decades.
- **Scaling**: Data normalized using MinMaxScaler for faster and stable training.
- **Windowed Dataset**: The dataset is preprocessed into sequences (sliding windows) of 10 days for model training, allowing temporal patterns to be captured effectively.  The window size (number of days) can be adjusted based on experimentation or specific requirements.
- **Model**: Stacked LSTM architecture for improved temporal feature extraction.
- **Output**: Predicts daily closing prices based on past trends.

---


## How to Run
1. Install dependencies from `requirements.txt`:
   ```bash
   pip install -r requirements.txt

2.	Open the Jupyter Notebook and run all cells to generate the predictions for the next 10 days starting from the last date in the dataset. You can predict for any number of days by modifying the value in the code. 
