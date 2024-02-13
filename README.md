# AutoTraderBot
AutoTraderBot is a Python-based automated trading bot designed to execute trades in the financial markets using machine learning sentiment analysis. It utilizes Alpaca as the brokerage platform for executing trades and Yahoo Finance data for backtesting.

### Features

- **Sentiment Analysis:** The bot incorporates sentiment analysis of news headlines using machine learning techniques to make trading decisions.
- **Automated Trading:** Trades are automatically executed based on predefined sentiment thresholds and probability criteria.
- **Risk Management:** The bot implements risk management strategies by adjusting position sizes according to available cash and sets take-profit and stop-loss prices for each trade.
- **Backtesting:** Utilizes Yahoo Finance historical data for backtesting the trading strategy over a specified time period.
- **Easy Configuration:** Easily configure the trading symbol and cash-at-risk parameters to tailor the bot to your trading preferences.

### Install Dependencies
pip install -r requirements.txt

### Setup Alpaca API credentials in the AutoTraderBot.py
- **API_KEY** = "your_api_key"
- **API_SECRET** = "your_api_secret"

### Contributing
Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes

### Disclaimer
Trading in financial markets involves risk. The information provided by this bot is for educational and informational purposes only and should not be considered financial advice. Use at your own risk.

