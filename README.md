# Shensu-AI-Technologies-Pvt-Ltd-Assignment-

__Task 1 Deployed Link : https://assig01.netlify.app__

__Task 2 Deployed Link : https://task02.netlify.app/__

__Assignment 1 :__
We are working as a quant researcher in the Stock Market, based on a certain strategy we have received following trades in historical data(Tradelog on the historical data is attached in the csv format) and we have to calculate the following parameters using Python to identify whether to execute the strategy or not.

Note: For the parameters calculation consider the initial portfolio value of Rs 6500 and the risk-free interest rate of 5%.

Parameters required

Total Trades
Profitable Trades
Loss-Making Trades
Win rate: Win Rate is the ratio of profitable trades to all trades
Average Profit per trade
Average Loss per trade
Risk Reward ratio: Risk Reward Ratio is the ratio of average profit to average loss.
Expectancy : (Win Rate x Average Profit) - (Loss Rate x Average Loss), where Loss Rate = 1 - (Win Rate)
Average ROR per trade: The ratio is the average return earned in excess of the risk-free rate per unit of volatility or total risk. Volatility is a measure of the price fluctuations of an asset or portfolio.
Sharpe Ratio: Sharpe Ratio = (Rate of Return - Risk-Free Rate) / (Standard deviation of the asset or portfolio)
Max Drawdown: A maximum drawdown is the maximum observed loss from the peak of the portfolio in the given duration.
Max Drawdown Percentage
CAGR The CAGR formula is equal to (Ending Value/Beginning Value) ^ (1/No. of Periods) – 1.
Calmar Ratio: Measures the performance of a strategy or fund, compared to its risk

__Assignment 2 :__
Gowtham is an algo trader who wants to perform some stock market analysis on ICICI bank. He wants to store the real-time stock market data of ICICI bank for this week in his database. For each day, he wants to store the data from 11.00 AM to 2.00 PM. However, he cannot afford to pay for a real-time API, so he decides to use the Python Yahoo Finance library which provides real-time data around a 15- minutes delay.

Write a Python program that will store 15-minute candle data of ICICI bank for every 15 minutes from 11.15 AM to 2.15 PM daily for a week. The program should use the Yahoo Finance library to retrieve the real-time data and store it in the database. Due to the 15-minute delay in the Yahoo Finance library, the program should start logging at 11.15 AM to capture data for the 11.00 AM time interval.

Note:

You should use MongoDB as a database and python APS Scheduler library for this task. The ticker for ICICI bank is "ICICIBANK.NS" and you can obtain stock information from Yahoo Finance using the yfinance library
