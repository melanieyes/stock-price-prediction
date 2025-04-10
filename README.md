# 📈 Stock Price Prediction 🚀

## 🧐 What's This About?
Welcome to the **ultimate** deep-learning-powered stock market crystal ball (well, almost). This project dives into the thrilling world of **time-series forecasting** to predict stock prices, spot those golden trading signals, and optimize a portfolio like a Wall Street pro. Whether you're looking to outsmart the Nasdaq or navigate the Vietnam stock market, we’ve got you covered!

## 🔥 Features That Make You Go "Whoa!"
- **Stock Price Prediction, But Smarter**: Uses multiple financial indicators (Open, High, Low, Close, Adjusted Close, Volume) instead of just one lonely feature.
- **Future-Gazing Abilities**:
  - Predicts stock prices for specific future days (3-day, 7-day forecasts, you name it!).
  - Can forecast multiple consecutive days ahead like a true market oracle.
- **Trading Signal Wizardry**:
  - Detects **when to buy** and **when to sell** (because FOMO is real).
  - Leverages legendary indicators like SMA, MACD, and RSI.
- **Portfolio Optimization Like a Hedge Fund Boss**:
  - Picks **winning** stocks.
  - Avoids **risky** ones.
  - Allocates funds like a pro (maximize gains, minimize sleepless nights).
- **For further development**:
  - Turns models into API services.
  - Builds a sleek web-based SaaS for stock market insights.
  - Automates everything with fancy AI workflows.

## 📊 Data Sources – The Fuel for Our AI Engine
### 1. Nasdaq Dataset
- Historical stock price data (csv format)
- Packed with multiple financial indicators

### 2. Vietnam Stock Market Dataset
- Stock historical data (yes, even for emerging markets!)
- Dividend history
- Financial ratios
- Industry analysis
- Company overviews

## 🛠️ Tech Stack – Tools of the Trade
- **Python** (because who doesn’t love Python?)
- **TensorFlow/Keras** (for that deep learning magic ✨)
- **Scikit-learn** (for when classic ML still does the trick)
- **Pandas & NumPy** (because data doesn’t wrangle itself)
- **Matplotlib & Seaborn** (for making things look pretty)
- **(Extra Credit)** TensorFlow Serving, REST APIs, gRPC, Airflow, Superset (for the hardcore devs out there)

## 📁 Project Layout – Where Stuff Lives
```
├── data/
│   ├── nasdaq/
│   ├── vietnam/
│
├── notebooks/
│   ├──nasdaq_ipynb
│   ├── hose.ipynb
│  
│
├── src/
│   ├── models/
│   ├── preprocessing/
│   ├── utils/
│
├── reports/
│   ├── project_report.pdf
│
├── README.md
├── requirements.txt
```

## ⚡ How to Get Started
1. Clone the repo like you mean it:
   ```bash
   git clone https://github.com/melanieyes/stock-price-prediction.git
   cd stock-price-prediction
   ```
2. Set up your virtual playground:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

## 🏎️ Running the Show
### Train the Model Like a Champ
```bash
python src/train.py --dataset nasdaq --features "Open,High,Low,Close,Volume"
```

### Make Some Predictions
```bash
python src/predict.py --dataset nasdaq --future_days 7
```

### Spot Those Trading Signals
```bash
python src/trading_signal.py --dataset vietnam --strategy "MACD"
```

## 📊 Performance Metrics – Because Accuracy Matters
- RMSE, MAE, and MAPE for model performance.
- Backtesting for trading signals (no hindsight bias here!).
- Risk-adjusted return calculations for portfolio optimization.

## 🚀 What’s Next?
- Experiment with transformer-based models.
- Integrate **real-time** stock market data.
- Deploy the whole thing to the cloud (because local machines get tired T_T).


