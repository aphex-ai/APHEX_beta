<div align="center">

# 🌟 APHEX AI

### Advanced Algorithmic Trading Framework for Cryptocurrency

**Backtest. Optimize. Deploy. Profit.**

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Aphex_AI)

[🚀 Getting Started](#-getting-started) • [📚 Documentation](https://aphex.run/docs.html) • [🎥 Tutorials](https://youtu.be/UpZ7hI2p7Eg?si=xXJuFFfAI9TlyDn_) •

---

</div>

## 🎯 What is APHEX AI?

**APHEX AI** is an advanced cryptocurrency trading framework built to simplify the process of developing, testing, and optimizing your own trading strategies. It allows you to **backtest**, **fine-tune**, and **deploy** your strategies in real or simulated environments—all without unnecessary complexity.

### 🎥 Quick Overview

Get a clear picture of how APHEX AI works and what it can do for you:

[![APHEX AI Overview](https://img.youtube.com/vi/SfyEf9Pcm2I/maxresdefault.jpg)](https://www.youtube.com/watch?v=SfyEf9Pcm2I)

> 👆 *Click to watch the introduction video*

---

## 🤔 Why Choose APHEX AI?

Simply put: APHEX AI is **more accurate**, **faster**, and **much easier to use** than most other trading solutions.

If you already know a bit of Python, you can be up and running in **minutes, not weeks**.

<div align="center">

| Feature | APHEX AI | Others |
|---------|----------|--------|
| **Speed** | ⚡️ Lightning Fast | 🐌 Slow |
| **Accuracy** | 🎯 No Look-Ahead Bias | ⚠️ Potential Issues |
| **Ease of Use** | ✅ Simple Python | ❌ Complex Setup |
| **Privacy** | 🔒 Self-Hosted | ☁️ Cloud-Based |
| **Cost** | 💰 Free & Open Source | 💸 Expensive Subscriptions |

</div>

---

## ⚙️ Key Features

<table>
<tr>
<td width="50%">

### 🧠 **Development**
- 🎨 **Clean, Simple Syntax** – Write complex strategies with minimal code
- 📚 **300+ Technical Indicators** – Easy-to-use API for all major indicators
- 🧩 **Integrated Code Editor** – Write and edit strategies in the platform
- 🤖 **APHEX GPT** – AI assistant for coding, debugging, and optimization
- 📺 **YouTube Tutorials** – Step-by-step video guides

</td>
<td width="50%">

### 📈 **Trading**
- 📊 **Multi-Timeframe & Multi-Symbol** – Trade multiple pairs simultaneously
- 💹 **Leverage & Short Selling** – Full support for advanced positions
- 🔀 **Partial Fills** – Enter/exit across multiple orders
- 📋 **Smart Order System** – Auto-selects best order type
- 🛡️ **Built-in Risk Management** – Helper tools for safe trading

</td>
</tr>
<tr>
<td width="50%">

### 🧪 **Testing & Optimization**
- ⚡️ **Lightning-Fast Backtesting** – No look-ahead bias
- 🔧 **AI-Powered Optimization** – Automatic parameter tuning
- 📊 **Powerful Metrics System** – Detailed performance analytics
- 🔍 **Debug Mode** – Watch every decision your strategy makes
- 📊 **Benchmarking** – Compare multiple strategies at once

</td>
<td width="50%">

### 🚀 **Deployment**
- 💼 **Live & Paper Trading** – Real or simulated environments
- 🔒 **Self-Hosted & Private** – Keep your data secure
- 🔔 **Advanced Alerts** – Telegram, Slack, Discord notifications
- 🌐 **Multiple Exchanges** – Spot, futures, and DEX support
- 📱 **Real-Time Dashboards** – Monitor performance live

</td>
</tr>
</table>

---

## 🧠 Effortless Strategy Creation

With APHEX AI, you can design sophisticated strategies using **clean, readable Python code**. You get instant access to hundreds of indicators, multiple markets, spot and futures trading, risk controls, and more—all in one environment.

### 💡 Example Strategy

```python

class GoldenCross(Strategy):
    def should_long(self):
        # Enter a long position when EMA 8 crosses above EMA 21
        short_ema = ta.ema(self.candles, 8)
        long_ema = ta.ema(self.candles, 21)
        return short_ema > long_ema

    def go_long(self):
        entry_price = self.price - 10       # limit buy $10 below current price
        qty = utils.size_to_qty(self.balance * 0.05, entry_price)  # risk only 5%
        
        self.buy = qty, entry_price
        self.take_profit = qty, entry_price * 1.2   # 20% profit target
        self.stop_loss = qty, entry_price * 0.9     # 10% stop loss
```

> ✨ **That's it!** Simple, clean, and powerful.

---

## 🧪 Backtesting

Run **highly accurate** and **lightning-fast** backtests free from look-ahead bias. Use detailed logs, interactive charts, and comprehensive metrics to validate and refine your strategies with confidence.

<div align="center">

*⚡️ Backtest years of data in seconds*

</div>

### 📊 What You Get

- ✅ **Accurate Simulations** – No look-ahead bias, no cheating
- ⚡️ **Blazing Fast** – Test years of data in seconds
- 📈 **Visual Charts** – Interactive TradingView-style charts
- 📋 **Detailed Metrics** – Sharpe ratio, win rate, drawdown, and more
- 🔍 **Trade-by-Trade Analysis** – See every entry and exit

---

## 💼 Live & Paper Trading

Deploy your strategies in **real markets** or test them in **paper trading mode** before committing capital. Monitor performance in real time with built-in tools.

<div align="center">

![Live Trading Dashboard](https://raw.githubusercontent.com/jesse-ai/storage/refs/heads/master/live.gif)

*📱 Real-time monitoring and control*

</div>

### 🎯 Features

- 📊 **Multiple Trading Accounts** – Manage multiple exchanges
- 🔔 **Real-Time Alerts** – Get notified via Telegram, Slack, or Discord
- 📈 **Interactive Dashboards** – Visual# APHEX_beta
