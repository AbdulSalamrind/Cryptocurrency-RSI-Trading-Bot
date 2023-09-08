# Cryptocurrency-RSI-Trading-Bot
# Cryptocurrency RSI Trading Bot

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

## Overview

This Python script is a cryptocurrency trading bot that monitors Relative Strength Index (RSI) values for selected cryptocurrency pairs on the Binance exchange. The RSI is a widely used technical indicator that helps traders identify potential buying or selling opportunities based on market conditions.

## Features

- Real-time monitoring of RSI values for multiple cryptocurrency pairs.
- Automatic notifications when a cryptocurrency is oversold (RSI <= 30) or overbought (RSI >= 70).
- Customizable list of cryptocurrency pairs to monitor.
- Adjustable time interval for checking RSI values.

## Prerequisites

Before using the bot, make sure you have the following:

- Python 3 installed.
- The CCXT library installed (`pip install ccxt`).
- A Binance API key and secret for fetching cryptocurrency data from the Binance exchange.

## Usage

1. Clone this repository to your local machine.
2. Configure your Binance API key and secret in the script (replace `exchange.apiKey` and `exchange.secret`).
3. Customize the list of cryptocurrency pairs to monitor (`crypto_symbols`) and the time interval (`time.sleep`) in the script.
4. Run the script using `python trading_bot.py`.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- This bot is built using the [CCXT](https://github.com/ccxt/ccxt) library.
- Special thanks to the crypto community for sharing knowledge about trading strategies and technical analysis.

## Disclaimer

This trading bot is for educational and informational purposes only. Cryptocurrency trading involves significant risk, and past performance is not indicative of future results. Use this bot at your own discretion and risk. The authors and contributors are not responsible for any financial losses or gains as a result of using this script.

