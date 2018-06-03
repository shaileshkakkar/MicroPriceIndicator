# MicroPriceIndicator
This repository serves to replicate the results listed in the paper by Sasha Stoikov - The Micro-Price. As opposed to data used in the paper for US equities BAC and CVX, I am using the data for the Crypto pair TRXBTC. The data was pulled by me from Binance by subscribing to three different streams - Market Trades, Partial Depth and OrderbookSnapshot. Then these were combined to form the order-book and analysis done on the same.

It is interesting to note that the micro price adjustment of the mid price in orderbook shares the same dynamics with orderImbalance and Spread metrics in Crypto space as has been shown by Sasha Stoikov in Equity space.

A practical utilization of the approach is to use this enhanced model for fair-price calculation and then to quote around it when making markets.
