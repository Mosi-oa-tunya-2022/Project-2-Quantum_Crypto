# Project 2: Cryptalgo
## (Quantum Crypto)

![](https://www.bitcoinmarketjournal.com/wp-content/uploads/2019/10/algorithmic-trading-strategies.jpg)


## Summary

The overall goal of Quantum Crypto is to develop and continue to develop an automated algorithmic trading strategy with technical indicators and buy/sell signals for various cryptocurrencies. Our focus in this particular project was to create and streamline a block of code to accurately predict the price of bitcoin.

## Datasets

Our data implemented imports from FreqTrade for data and strategy and TALIB for technical analysis.
Our implied strategy uses several technical indicators needed in order to accurately predict the price of Bitcoin.
 ### RSI
 ### SMA 21
 ### SMA 50
 ### H Line
 ### MACD
  
## Backtesting
In essence, backtesting is a way of training our model for accuracy based on realised data. Our dataframe was iloc’d from March 18, 2020 through March 18, 2022. Backtesting is one the most important aspects in developing a trading model because it allows model creators to optimize and improve on strategy.

## Regression (Training and Testing)

A good model strategy needs to measure results. For this purpose we used the Bayesian Ridge model to perform the function. Cryptocurrency by nature is exponentially growing and changing. Due to this fact, strategies will need constant adjustments for optimization. A regression model allows us measure the respective model each time an adjustment is made.

## Questions to answer

### What technical indicators provided the best model feedback?
RSI, MACD, SMA 21, SMA 50

### Which regression model provided the best accuracy?
The Bayesian Ridge model provided the best accuracy score as viewed in our notebook as oppose to some of the regession models which did not coorelate at all with actual returns
