# CryptoForesight

## Overview

CryptoForesight is a time series forecasting project focused on predicting cryptocurrency prices using historical data. It leverages machine learning models, including XGBoost, to analyze trends, detect anomalies, and make future price predictions.

## Features

- Time series analysis of major cryptocurrencies (BTC, ETH, ADA, DOGE).
- Moving average and trend analysis.
- Anomaly detection for price fluctuations.
- Machine learning-based forecasting using XGBoost.

## Dataset

The project uses historical price data from 2017 to December 2024 for ADA, DOGE, and ETH, and from 2014 for BTC. The dataset includes:

- **Date**: Trading date
- **Open, High, Low, Close**: Price data
- **Volume**: Trading volume
- **Coin**: Cryptocurrency type
- **Moving\_Avg**: Computed moving average

### Dataset Files:

- `ADA-USD From 2017 To Dec-2024.csv`
- `DOGE-USD From 2017 To Dec-2024.csv`
- `ETH-USD From 2017 To Dec-2024.csv`
- `BTC-USD From 2014 To Dec-2024.csv`

## Installation

### Prerequisites

Ensure you have Python installed.

### Steps

```sh
# Clone the repository
git clone https://github.com/sanikajhanwar/CryptoForesight.git
cd CryptoForesight

# Install dependencies
pip install -r requirements.txt
```


## Usage

Run the main script to train and evaluate the model:

```sh
python main.py
```

Modify parameters in `config.py` for different forecasting approaches.

## Visualization

The project includes Google Colab visualization. You can open and run the code in Colab notebook.

Alternatively, use Jupyter notebooks for local visualization:

```sh
jupyter notebook
```

The project includes Jupyter notebooks for visualization:

```sh
jupyter notebook
```

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any queries, reach out to **Sanika** via GitHub or email(sanikajhanwar@gmail.com).

---

🚀 **CryptoForesight: Unlocking the Future of Cryptocurrency Trends!**

