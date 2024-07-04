### Outline

1. Use the yfinance library to fetch historical price data for the specified stocks from 2013-01-01 to 2023-12-31.

2. Create functions to calculate the Double Bollinger Bands and generate buy/sell signals based on the strategy.

3. Design a custom backtesting loop to simulate trading with the generated signals, starting with an initial capital of $10,000 and a minimum transaction size of 1 share per trade.

4. Implement functions to calculate the required performance metrics.


### Conclusion

I looked at price data from 2013 to 2023 for the Magnificent 7 on Yahoo Finance. I backtested a simple momentum and mean-reversion strategy using double Bolinger bands. Backtests were done with initial capital of 10,000 and a minimum of 1 trade per share.

An overview of the trading metrics shows that TSLA works well with a momentum strategy while MSFT, NVDA, GOOG and META works well with a mean-reversion strategy. Both strategies do not work well for AAPL and AMZN.
