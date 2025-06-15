# CrossBot
simples algorithmic trading for study

# 🤖 CrossBot

**CrossBot** is a simple algorithmic trading bot that uses the **Moving Average Crossover** strategy to generate buy/sell signals on stocks or cryptocurrencies. It's built with Python and designed for learning, backtesting, and experimenting with algorithmic trading.

---

## 📈 Strategy

CrossBot uses two moving averages:

- **Short-Term MA** (e.g., 50-day)
- **Long-Term MA** (e.g., 200-day)

### 🔁 Logic:
- **BUY** when short MA crosses **above** long MA (bullish crossover)
- **SELL** when short MA crosses **below** long MA (bearish crossover)

---

## 🧰 Tech Stack

- Python 🐍
- [pandas](https://pandas.pydata.org/) for data manipulation
- [yfinance](https://github.com/ranaroussi/yfinance) or [ccxt](https://github.com/ccxt/ccxt) for data
- [matplotlib](https://matplotlib.org/) for visualization
- (Optional) Alpaca or Binance API for paper/live trading

---

## 🚀 Getting Started

### 📦 Install dependencies

```bash
pip install pandas yfinance matplotlib
# Optional (for crypto)
pip install ccxt
