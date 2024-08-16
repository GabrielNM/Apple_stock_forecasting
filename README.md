# Apple Stock Price Prediction using LSTM

This repository contains a Python notebook that uses a Long Short-Term Memory (LSTM) network to predict the closing prices of the Apple stock prices. The model is built using TensorFlow and Keras, with historical stock data fetched using the `yfinance` library.

## Features

- **Data Acquisition**: Retrieves historical S&P 500 stock data from Yahoo Finance.
- **Data Preprocessing**: Normalizes and prepares data for time series forecasting.
- **LSTM Model**: A sequential LSTM model with dropout layers to prevent overfitting.
- **Training and Testing**: Splits the data into training and testing sets and trains the model on past 60-day stock prices.
- **Prediction**: Generates and visualizes predictions against actual stock prices.
- **Evaluation**: Computes the Root Mean Square Error (RMSE) to evaluate model performance.

## Installation

To run this project, you'll need to install the following dependencies:

```bash
pip install tensorflow yfinance numpy pandas scikit-learn matplotlib
```

## Contributing
Feel free to fork this repository, create a feature branch, and submit a pull request with your improvements or additional features.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
