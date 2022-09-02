
# 🤖BinanceRSIBot

This bot uses Binance Web Socket and user's API to fetch streaming data the desired crypto from Binance. We can also place Buy, Sell and check history of our orders placed. 



## 🪛Installation

How to run project:

```
git clone https://github.com/vishalsingh17/BinanceRSIBot.git
```
```
cd BinanceRSIBot
```
```
cd coinview
```
```
conda create -p venv python==3.7
```
```
conda activate ./venv
```
```
pip install -r requirements.txt
*NOTE* - Use "conda install -c conda-forge ta-lib" to install TA-LIB
```
```
python app.py
```
## 👨‍💻Tech Stack

**Client:** HTML, CSS, JavaScript

**Server:** Python, Binance Web Socket, Binance user API


## 🕵️‍♂️Environment Variables

To run this project, you will need to add the following environment variables to your config.py file

`BINANCE_API_KEY` = "YOUR API KEY"

`BINANCE_SECRET_KEY`= "YOUR SECRET KEY"

NOTE - Store your API key and SECRET key in your environment variable for eshtablishing secure connections.

## ✍🏻Acknowledgements

 - [Get Binance API](https://www.binance.com/en/support/faq/360002502072)
 - [TA-LIB Github](https://github.com/mrjbq7/ta-lib)
 - [KLine Github](https://github.com/binance/binance-spot-api-docs/blob/master/rest-api.md#klinecandlestick-data)

## 🎯App Screenshots

![Main Page](https://user-images.githubusercontent.com/55878408/188097160-90de3b7a-64ae-4953-8bef-cf9dd703f969.png)

![Buy Zone](https://user-images.githubusercontent.com/55878408/188097150-5a326880-7edd-4447-98d0-934abed8234e.png)

![Balances](https://user-images.githubusercontent.com/55878408/188096984-f2a87ce8-89a0-4bf4-9d8b-9fa5a60