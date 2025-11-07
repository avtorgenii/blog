---
title: Trading Buddy 2.0 — my personal helper web app for trading.
date: 2025-11-07
tags: 
    - django
    - sveltekit
    - postgresql
    - docker
    - backups
    - trading
---

## What is it?
Trading Buddy 2.0 is a web app which serves as an interface between trader and exchange and automates numerous repetitive tasks trader does every trading day. It delivers seamless experience between trader and exchange where trader doesn't have to trade in one place, calculate position size in another one and lead and analyze his trades journal somewhere else.




## What can it do?
Among those automated tasks are:
- Position size calculation based on specified risk and deposit, entry price and stop-loss price
- Specifying more than take-profit before order is placed and filled — Binance, ByBit, BingX allow for specification of only one take-profit before the position is filled
- Removement of the open order when price has reached certain level - useful when you place limit orders and cancel this order if the price goes to far in direction of your take-profit without otder being filled
- Moving stop-loss to entry level after certain take-profit is filled - so you don't have to track your position and manually move the stop-loss
- Tracking all your trades in trading Jounal which automatically fills a bunch of data about your trade for you

Besides features above webapp also has statistics module which shows your trading statistics in clear and useful way.


## How to use it?
### Settings


### Trade


### Positions


### Journal


### Stats


Source code is available here --> [source](https://github.com/avtorgenii/trading-buddy-2.0)


