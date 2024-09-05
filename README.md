# Mean-Reversion Trading &nbsp; [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ianjure/mean-reversion-trading/blob/main/Mean_Reversion_Notebook.ipynb) &nbsp; [![Static Badge](https://img.shields.io/badge/Visit%20Website-red?style=flat&logo=streamlit&logoSize=auto&labelColor=%23ffffff&color=%23ff4b4c)](https://tradestrats.streamlit.app/)

Mean reversion is a financial theory which suggests that, after an extreme price move, asset prices tend to return back to normal or average levels.

## Data Overview
We will obtain historical price data for the stock from **Yahoo Finance** using the [yfinance](https://pypi.org/project/yfinance/) library. This dataset will include columns such as opening and closing prices, which are essential for simulating the trading strategy.

## Project Method
1. **Collect the Data:** Retrieve stock price data from Yahoo Finance.
2. **Clean the Data:** Remove irrelevant features and standardize the index format.
3. **Create New Features:** Compute daily returns and classify the data into distinct states.
4. **Build the Model:** Estimate state probabilities for the transition matrix.
5. **Simulate the Strategy:** Execute simulated trades and calculate the expected returns.
6. **Deploy the Model:** Create a web application enabling users to test the model.

## Next Steps
* **Identify** methods to improve the strategy's win rate.
* **Explore** and evaluate additional trading strategies.

<br>

**This project is inspired by:** [Mean Reversion Trading Strategy Using Python](https://eodhd.medium.com/testing-a-powerful-mean-reversion-trading-strategy-using-python-4eb5eed60857)
