# DCAVG---Binance-Bitcoin-Daily-Dollar-Cost-Averaging
**Tool that allows you to buy Bitcoin with your Binance account automatically every day (or almost every day)**

With this tool you will never forget to buy your daily bitcoins. In fact, everything will be done automatically using the Binance API of your account. 
The bot will buy daily the correspondent in Bitcoin of an amount in euro defined by the user, through a "MARKET" trade for BTCUSDT. 

If the USD value of the Bitcoins to buy is lower than 10USD, which is the minimum value to trade on Binance, then the bot will postpone the purchase to the next day until the value reaches at least 10USD. 
All the information collected daily is saved on a csv `./src/data.csv`, so you can have the information available for possible analysis for your portfolio.   

You can set this tool by simply adding your Binance API key to the `./src/secrets.py` file and configure the purchase settings to `./src/config.py`. 
If you need help, do not hesitate to contact me. 

---

### I developed this tool out of personal need, I gladly accept external help to develop it further.

---


## Upcoming developments

 - Add Telegram message notification system to alert you when your USDT balance on your account at Binance is about to run out
 - Add an automatic USDT recharge system to your account directly from FIAT and/or ERC-20 wallets. 
 - Allow you to manage the purchase of Bitcoin for multiple users with centralized funds management
 - Allows you to manage the purchase of Bitcoin for multiple users with decentralized fund management
