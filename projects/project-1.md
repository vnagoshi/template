---
layout: project
type: project
image: images/macd-tracker-square.png
title: MACD Tracker
permalink: projects/macd-tracker
date: 2017
labels:
  - Java
  - Financial Markets
summary: A Java application that calculates the MACD indicator for stocks and recommends buy or sell signals accordingly.
---

<img class="ui image" src="{{ site.baseurl }}/images/macd-tracker.png">

MACD Tracker is a Java Application that calculates the moving average convergence divergence (MACD) indicator for stocks and recommends buy and sell signals accordingly for each tracked stock.

The MACD indicator is formed by two lines, the MACD1 line, which is a 26-day exponential moving average (EMA) minus a 12-day EMA of a stock's price, and the signal line, a 9-day EMA of the MACD 1 line. The MACD indicator tracks the momentum of the market. When the MACD1 line crosses the signal line from below, a buy signal is given. When the MACD1 line crosses the signal line from above, a sell signal is given. 

MACD Tracker will display a stock's open, close, high, and low prices for a given date, the stocks volume, and historical data for the stock for up to a year. It will also show you when a buy or a sell signal was given successfully. When a buy signal occurs, the stock's ticker symbol will appear in the buy color (Defaults to green), and vice versa for a sell signal (defaults to red).

<hr>
Source: <a href="https://github.com/vnagoshi/MACD-Tracker"><i class="large github icon "></i>vnagoshi/MACD-Tracker</a>

