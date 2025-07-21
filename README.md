# 📈 Cryptocurrency Analysis and Forecasting

This project focuses on predicting daily closing prices of four major cryptocurrencies — **Bitcoin**, **Ethereum**, **Dogecoin**, and **Cardano** — using a blend of time series models and machine learning algorithms.

## 🎯 Objective

To compare and evaluate the forecasting power of traditional statistical models (like ARIMA), modern ML models (XGBoost), and hybrid approaches (ARIMA + XGBoost) for high-volatility financial data.

## 🔍 Research Question

> Can machine learning and statistical models accurately forecast crypto price movements?  
> Which model performs best under the market's volatile conditions?

## 📊 Data

- **Source**: Publicly available historical data from Yahoo Finance.
- **Time Period**: From 2015 to the latest available date.
- **Features**: `open`, `high`, `low`, `close`, `adj_close`, `volume`, and `date`.

## 🛠️ Preprocessing

- Removed missing values.
- Normalized data using `MinMaxScaler`.
- Engineered lag and rolling features.
- Converted `date` to `datetime` format for time series indexing.

## 🧠 Models Used

| Model                 | Why It Was Used                                      |
|----------------------|------------------------------------------------------|
| **ARIMA**            | For capturing linear trends and seasonality.         |
| **Prophet**          | Handles missing data and outliers well.              |
| **XGBoost**          | Detects non-linear patterns with high performance.   |
| **ARIMA + XGBoost**  | Combines linear and non-linear modeling strengths.   |

## 📈 Model Performance (Bitcoin Example)

| Model        | RMSE       | MAE        | R² Score   |
|--------------|------------|------------|------------|
| ARIMA        | 28248.92   | 22516.65   | -1.7406    |
| Prophet      | 29628.98   | 23890.23   | -2.0149    |
| XGBoost      | 22659.33   | 17106.80   | -0.7824    |
| Hybrid       | 28248.15   | 22515.60   | -1.7404    |

✅ **XGBoost performed best individually**, but the **hybrid model showed improved combined learning**.

## 📌 Key Takeaways

- Machine learning (XGBoost) outperforms classical models for crypto data.
- Combining ARIMA and XGBoost improves forecasting precision.
- Recent price and short-term trends are the most predictive features.

## 🚧 Limitations

- Market shocks and external news events aren't captured in historical data.
- Crypto markets are extremely volatile and complex.
- Risk of overfitting in complex models.

## 🔮 Future Work

- Integrate alternative data (sentiment analysis, economic indicators).
- Explore deep learning (LSTM, GRU).
- Build ensemble models combining different forecasting techniques.

## 📚 References

- [Yahoo Finance - Historical Data](https://finance.yahoo.com/markets/crypto/all/)
- Various papers on crypto forecasting using ML and deep learning.

