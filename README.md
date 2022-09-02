
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


