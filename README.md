# 📈 Google Stock Price Prediction using LSTM

This project demonstrates how to predict Google stock prices using a Long Short-Term Memory (LSTM) neural network implemented with Keras and TensorFlow. The model is trained on historical stock price data and used to forecast future stock prices, showing both real and predicted values for comparison.

## 🧠 Model Summary

- **Type**: Recurrent Neural Network (RNN)
- **Architecture**: 4 stacked LSTM layers with Dropout to prevent overfitting
- **Input**: Previous 60 days of stock prices
- **Output**: Predicted stock price for the next day

## 🔧 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn
- Keras (with TensorFlow backend)

## 📁 Dataset

- `Google_Stock_Price_Train.csv` – Historical stock price data for training (2012–2016)
- `Google_Stock_Price_Test.csv` – Stock price data for testing (2017)

