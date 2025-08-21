# ML_Project


# 📈 Stock Market Forecasting using LSTM

This project demonstrates **stock price prediction and forecasting** using a Stacked LSTM (Long Short-Term Memory) neural network.
The model is trained on historical stock data (Apple Inc. - AAPL) and attempts to forecast future closing prices.

---

## 🚀 Features

* Collects stock price data using `pandas_datareader`
* Preprocesses and visualizes the data
* Implements a **Stacked LSTM model** using TensorFlow/Keras
* Predicts and compares future stock prices against actual values

---

## 📂 Project Structure

```
├── AAPL.csv                # Apple stock price dataset (downloaded using Tiingo API)
├── Untitled.ipynb           # Jupyter Notebook with full workflow
├── README.md                # Project documentation
```

**requirements.txt** (create this file if not present):

```
numpy
pandas
matplotlib
tensorflow>=2.0
scikit-learn
pandas_datareader
```
---

## 📊 Usage

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Untitled.ipynb
   ```
2. Run the cells step by step:

   * Data collection from Tiingo (requires API key)
   * Preprocessing (scaling, training/testing split)
   * Model building with stacked LSTMs
   * Predictions & visualization

---

## 📈 Results

* The model learns historical trends and produces stock price forecasts.
* Example visualization: predicted vs actual closing prices.

---

## 🔮 Future Improvements

* Extend to multiple stocks or indices (e.g., S\&P 500, NASDAQ).
* Hyperparameter tuning for better accuracy.
* Deploy as a web app with **Flask/Streamlit** for real-time predictions.

---

## 🙌 Acknowledgements

* [TensorFlow Documentation](https://www.tensorflow.org/)
* [pandas\_datareader](https://pandas-datareader.readthedocs.io/)
* Stock data powered by [Tiingo API](https://www.tiingo.com/)

---
