# Mean Reversion Trading &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ianjure/mean-reversion-trading/blob/main/Mean_Reversion_Notebook.ipynb) &nbsp; [![Static Badge](https://img.shields.io/badge/Visit%20the%20Website-red?style=flat&logo=streamlit&logoSize=auto&labelColor=%23ffffff&color=%23ff4b4c)](https://tradestrats.streamlit.app/meanreversion)

Mean reversion is a financial theory that suggests asset prices tend to return to their average levels after an extreme price movement. The goal of this project is to develop an algorithm that replicates this strategy and simulates its returns using historical stock data.

## Data Overview
We will retrieve historical price data for the stock from Yahoo Finance using the [yfinance](https://pypi.org/project/yfinance/) library. This dataset will include the closing prices, which are crucial for simulating the trading strategy. Additionally, we will use [pandas-ta](https://pypi.org/project/pandas-ta/), a technical analysis library, to calculate two key indicators: the Relative Strength Index (RSI) and the Simple Moving Average (SMA).

## Project Method
1. **Collect the Data:** Retrieve stock price data from Yahoo Finance.
2. **Clean the Data:** Remove irrelevant features and standardize the index format.
3. **Create New Features:** Use pandas-ta to calculate the 10-period RSI and 200-period SMA.
4. **Simulate the Strategy:** Apply the entry and exit conditions to execute the strategy and calculate the expected returns.
5. **Deploy the Model:** Develop a web application that allows users to test the model.

## Next Steps
* **Explore** and evaluate additional trading strategies.
* **Experiment** with different combinations of RSI and SMA periods.

<br>

**This project is inspired by:** [Mean Reversion Trading Strategy Using Python](https://eodhd.medium.com/testing-a-powerful-mean-reversion-trading-strategy-using-python-4eb5eed60857)
