# Binance_Trading_Bot
# 🚀 Binance Futures Trading Bot (Testnet)

This is a **Binance Futures Trading Bot** built with **Python** and **Streamlit**. It allows users to place test trades on the **Binance Futures Testnet** using a clean and interactive web interface. Perfect for practicing and learning algorithmic trading without risking real money.

---

## 📦 Features

- ✅ Trade on the **Binance Futures Testnet**
- ✅ Easy-to-use **Streamlit interface**
- ✅ Supports **MARKET** and **LIMIT** order types
- ✅ Real-time API response and error handling
- ✅ Works using your own API key & secret (Testnet only)

---

## 📸 UI Preview

![App Screenshot](https://via.placeholder.com/800x400.png?text=Binance+Trading+Bot+UI)

---

## 🧰 Tech Stack

- Python 🐍
- Streamlit 📊
- Binance API (`python-binance`)

---

## 🛠️ Installation

1. **Clone the repository**:
git clone https://github.com/bhaskar-it/binance-trading-bot.git
cd binance-trading-bot

2. **Create a virtual environment (optional but recommended):**
python -m venv venv
source venv/bin/activate

3.**Install the required packages:**
pip install -r requirements.txt

4.**Run the application:**
streamlit run app.py


#**How to Use**
Get your Binance Futures Testnet API key and secret from testnet.binancefuture.com

Launch the app (streamlit run app.py)

Enter your API credentials

Select:

Trading pair (e.g., BTCUSDT)

Order side (BUY/SELL)

Order type (MARKET/LIMIT)

Quantity

Limit price (only for LIMIT orders)

Click “Place Order” — and you're good to go!


#**Security Notice**
⚠️ Never use real API keys on the Testnet app
⚠️ This is for educational and testing purposes only.
⚠️ Do not commit your API keys to public repositories.


#**Project Structure**
binance_trading_bot/
├── app.py                  # Main Streamlit app
├── requirements.txt        # Python dependencies
├── README.md               # This file
├── venv/                   # Virtual environment (optional)
└── any supporting modules




