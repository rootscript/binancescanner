# binancescanner
>Disclaimer:  I am in no way affiliated with Binance, use at your own risk. There are no warranties or guarantees expressed or implied. You assume all responsibility and liability. 

binancescanner is a price and volume scanner with customizable threshold notifications written in Python 3. Eyes everywhere for monitoring fast moving markets! One part of the traderstoolkit coming soon.

### (Optional!) Configuration 

1. Change trading pair (from BTC to USDT, ETH or BNB)
1. Change volume threshold (in BTC)
1. Change price and volume difference thresholds (in percentage)

### Requirements
   
    High-speed Internet connection
    Python 3.6
	
Using pip you will need to run the following:

    $ pip install binance
    $ pip install twisted
    $ pip install colorama
	
### Usage
    python BIscanner.py

### Issues
    Running on Linux or Mac crashes due to colorama

### Support
If you need any help you can find me on:
- Discord: @krishtopher
- Telegram: @krishtopher

### Roadmap
binancescanner is currently in early testing stages but will be expanding soon:
- Add instructions for no0bs
- Improve triggering conditions for notifications
- Requirements file
- Docstrings
- Graceful exception handling
- Command line arguments for TRADING PAIR and THRESHOLDS
- Test colorama on Linux and Mac

### Noob Guide
1. Install python 3 and pip as shown [here](https://matthewhorne.me/how-to-install-python-and-pip-on-windows-10/)
1. Install the required modules listed above using pip 
1. If correctly installed, you should be able to double click BIscanner.py to run it

## traderstoolkit
The traderstoolkit is a collection of scripts and tools to allow easier trading. Each tool will be released standalone as they are completed and the toolkit will be released as a whole at a later date.

> **testing for public release*
> ***in development*

#### BITFINEX ONLY
- BFtrader.py* - multiple trades, single currency trading bot

- BFarbv1.py* - arbitrage calculator for multiple currencies

- BFarbv2.py** - arbitrage calculator for multiple currencies with built-in trader

#### BINANCE ONLY
- BIscanner.py - eyes everywhere! price and volume scanner with customizable threshold notifications

- BIarbv1.py** - arbitrage calculator for multiple currencies

- BIarbv2.py** - arbitrage calculator for multiple currencies with built-in trader

#### BITMEX ONLY
- BMtrader.py** - single trade, single currency (XBTUSD) trading bot

#### GLOBAL
- sentiment.py* - configurable real time sentiment analysis of tweets associated with particular cryptocurrencies (susceptible to spam tweets/bots)

## Donate

If this library helped you out feel free to donate:

- ETH: 0x1f9145dA965506e41924460Dd86E60ce1083be6c
- LTC: MDfztCZvet4jGFFUbi8TwNts3uayZmGebJ
- BCH: 19iLgsCkXQY8wJXqnRVN64kL5pWs2bLqbW
- BTC: 3BZg92TdEW3utKy5ErDtV2kbdGtK33Z9CB