# GDAX_Trader
**Note that the GDAX api used in this repo is no longer functioning.**

[Full article detailing this project on *Towards Data Science*](https://towardsdatascience.com/build-a-cryptocurrency-trading-bot-with-r-1445c429e1b1)

This script interfaces with the GDAX api to make trades on the same exchange. Currently in ETHUSD pairs. The "buy" signal initiates a limit order at te current bid, and iterates until the order is filled. The buy signal is a combination of EMA and RSI indicators which signal that ETH is oversold. The sell signal is the opposite with overbought being the prime mover. This script is scheduled to run every 5-10 minutes using a tool such as Windows Task Scheduler.

Special Thanks To owner PR.
