
# Freqtrade

![freqtrade](https://raw.githubusercontent.com/freqtrade/freqtrade/develop/docs/assets/freqtrade_poweredby.svg)

Freqtrade is a free and open source crypto trading bot written in Python. It is designed to support all major exchanges and be controlled via Telegram or webUI. It contains backtesting, plotting and money management tools as well as strategy optimization by machine learning.

![freqtrade](https://raw.githubusercontent.com/freqtrade/freqtrade/develop/docs/assets/freqtrade-screenshot.png)

[![Freqtrade CI](https://github.com/freqtrade/freqtrade/workflows/Freqtrade%20CI/badge.svg)](https://github.com/freqtrade/freqtrade/actions/)
[![DOI](https://joss.theoj.org/papers/10.21105/joss.04864/status.svg)](https://doi.org/10.21105/joss.04864)
[![Coverage Status](https://coveralls.io/repos/github/freqtrade/freqtrade/badge.svg?branch=develop&service=github)](https://coveralls.io/github/freqtrade/freqtrade?branch=develop)
[![Documentation](https://readthedocs.org/projects/freqtrade/badge/)](https://www.freqtrade.io)
[![Maintainability](https://api.codeclimate.com/v1/badges/5737e6d668200b7518ff/maintainability)](https://codeclimate.com/github/freqtrade/freqtrade/maintainability)

## Features

- Based on Python 3.9+: For botting on any operating system - Windows, macOS, and Linux.
- Persistence: Persistence is achieved through SQLite.
- Dry-run: Run the bot without playing money.
- Backtesting: Run a simulation of your buy/sell strategy.
- Strategy Optimization by machine learning: Use machine learning to optimize your buy/sell strategy parameters with real exchange data.
- Adaptive prediction modeling: Build a smart strategy with FreqAI that self-trains to the market via adaptive machine learning methods.
- Edge position sizing: Calculate your win rate, risk reward ratio, the best stoploss, and adjust your position size before taking a position for each specific market.
- Whitelist crypto-currencies: Select which cryptocurrency you want to trade or use dynamic whitelists.
- Blacklist crypto-currencies: Select which cryptocurrency you want to avoid.
- Builtin WebUI: Builtin web UI to manage your bot.
- Manageable via Telegram: Manage the bot with Telegram.
- Display profit/loss in fiat: Display your profit/loss in fiat currency.
- Performance status report: Provide a performance status of your current trades.

## Disclaimer

This software is for educational purposes only. Do not risk money which you are afraid to lose. USE THE SOFTWARE AT YOUR OWN RISK. THE AUTHORS AND ALL AFFILIATES ASSUME NO RESPONSIBILITY FOR YOUR TRADING RESULTS.

Always start by running a trading bot in Dry-run and do not engage money before you understand how it works and what profit/loss you should expect.

We strongly recommend you to have coding and Python knowledge. Do not hesitate to read the source code and understand the mechanism of this bot.

## Supported Exchange Marketplaces

Please read the [exchange specific notes](docs/exchanges.md) to learn about eventual, special configurations needed for each exchange.

- [X] [Binance](https://www.binance.com/)
- [X] [Bittrex](https://bittrex.com/)
- [X] [Gate.io](https://www.gate.io/ref/6266643)
- [X] [Huobi](http://huobi.com/)
- [X] [Kraken](https://kraken.com/)
- [X] [OKX](https://okx.com/) (Former OKEX)
- [ ] [potentially many others](https://github.com/ccxt/ccxt/) _(We cannot guarantee they will work)_.

### Supported Futures Exchanges (experimental)

- [X] [Binance](https://www.binance.com/)
- [X] [Gate.io](https://www.gate.io/ref/6266643)
- [X] [OKX](https://okx.com/)
- [X] [Bybit](https://bybit.com/)

### Community Tested

Exchanges confirmed working by the community:

- [X] [Bitvavo](https://bitvavo.com/)
- [X] [Kucoin](https://www.kucoin.com/)

## Documentation

We invite you to read the bot documentation to ensure you understand how the bot is working.

Please find the complete documentation on the [freqtrade website](https://www.freqtrade.io).

## Quick Start

Please refer to the [Docker Quickstart documentation]