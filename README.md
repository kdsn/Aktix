# 📌 Aktix

🔹 **Short description:**  

Aktix is a private algorithm-assisted trading system designed to analyze the S&P 500 in real time, identify profitable candlestick patterns, and assist in execution via a manual decision layer.

The platform consists of:

A Python backend that scans for candlestick patterns using volume and context filters

A PWA frontend for viewing signals, approving trades, and monitoring statistics

A MetaTrader 5 execution engine that handles validated orders and performance logging

Aktix includes live scanning, rolling backtests, and a modular strategy architecture. It is built for private use and is not intended for public or commercial use.

> ## ⚠️ This is a private research and development project. ##
> Not for financial advisory or resale use.

## Features
  ✅ Scans the entire S&P 500 every minute for predefined candlestick patterns <br/>
  ✅ Supports modular strategy plugins <br/>
  ✅ Filters signals using context-aware criteria like volume and RSI <br/>
  ✅ Condenses real-time news and headlines related to each signal <br/>
  ✅ Sends actionable trading signals to a Progressive Web App (PWA) <br/>
  ✅ Manual signal approval system with optional MT5 execution <br/>
  ✅ Tracks performance statistics, win rate, risk/reward, and drawdown <br/>
  ✅ Weekly rolling backtests for monitoring, and for strategy selection <br/>
  ✅ Strategy qualification based on historical backtests <br/>
  ✅ Real-time push notifications for high-confidence signals <br/>
  ✅ Fully self-hosted and designed for private use <br/>

## Tech Stack & Dependencies
| Technology                 | Version          |
|----------------------------|------------------|
| Python                     | 3.11             |
| SQLite or PostgreSQL       | TBA              |
| Pandas / NumPy             | latest           |
| yFinance / Finnhub API     | External APIs    |
| MetaTrader 5               | Python API       |
| HTML/CSS + Vanilla JS      | Custom PWA       |
| Tailwind CSS               | 3.x              |
| GitHub Actions             | CI/CD            |

## License
This code is visible to showcase the structure and purpose of the Aktix system.  
All rights reserved. Redistribution, modification, or usage of this code is strictly prohibited without explicit permission.
