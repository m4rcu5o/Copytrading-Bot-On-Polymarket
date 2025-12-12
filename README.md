# ⚡ Polymarket Copytrading Bot – Real-Time Auto Copy Trader for Polymarket

<div align="center">

**High-Performance Polymarket Copytrading Bot**  
*Real-Time Trade Mirroring • Automated Market Replication • Polygon CLOB Integration*

[![Polymarket](https://img.shields.io/badge/Platform-Polymarket-blue.svg)](https://polymarket.com)
[![Copy Trading](https://img.shields.io/badge/Feature-Copy%20Trading-green.svg)]()
[![Polygon](https://img.shields.io/badge/Network-Polygon-purple.svg)](https://polygon.technology)

</div>

---

## 🔍 SEO-Optimized Tags
**Keywords:** polymarket copytrading bot, polymarket copy trading, polymarket trader copier, polymarket auto copy bot, copytrade polymarket, polymarket bot, polymarket automation, polygon copy trading bot.

---

## 📘 Overview

This **Polymarket Copytrading Bot** automatically mirrors trades from any chosen Polymarket trader.  
Optimized for **speed, reliability, and consistent market execution**, it listens to Polymarket's **CLOB (Central Limit Order Book)** feed in real time and reproduces trades on your wallet.

Perfect for users who want to:

- Copy top-performing Polymarket traders  
- Automate market actions  
- Execute synchronized positions on Polygon  
- Build analytics or trading automation systems  

---

## 🚀 Features

- **⚡ Real-Time Auto Copy Trading**  
  Instantly replicates orders from any target Polymarket wallet.

- **📡 Live CLOB WebSocket Monitoring**  
  Detects new orders as soon as they appear on Polymarket.

- **🛡 Configurable Risk Controls**  
  Includes fetch intervals, retry limits, and order age filtering.

- **🗄 MongoDB Logging**  
  Tracks trade history, system events, and debugging logs.

- **🔧 Simple .env Configuration**  
  All behavior and endpoints are customizable.

---

## 📦 Installation

### 1. Install Node.js  
Use latest LTS version.

### 2. Clone the Repository

```bash
git clone https://github.com/m4rcu5o/Copytrading-Bot-On-Polymarket.git
cd Copytrading-Bot-On-Polymarket
```

### 3. Prepare Your `.env` File

```bash
touch .env
```

Add:

```env
# Wallet to copy trades from
USER_ADDRESS="TARGET_WALLET_ADDRESS"

# Your wallet credentials
PROXY_WALLET="YOUR_POLYMARKET_WALLET"
PRIVATE_KEY="YOUR_PRIVATE_KEY"

# Polymarket CLOB Endpoints
CLOB_HTTP_URL="https://clob.polymarket.com/"
CLOB_WS_URL="wss://ws-subscriptions-clob.polymarket.com/ws"

# Bot behavior
FETCH_INTERVAL=1
TOO_OLD_TIMESTAMP=3600
RETRY_LIMIT=3

# MongoDB
MONGO_URI="YOUR_MONGODB_URI"

# Polygon RPC + USDC Contract
RPC_URL="https://polygon-mainnet.infura.io/v3/<YOUR_INFURA_KEY>"
USDC_CONTRACT_ADDRESS="0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174"
```

---

## 🏃 Setup & Run

### Install dependencies

```bash
npm install
```

### Build

```bash
npm run build
```

### Start the bot

```bash
npm run start
```

---

## 🤝 Contributing

Contributions are welcome!  
Submit issues or PRs anytime.  
If this project helps you, please **leave a ⭐**.

---

## 📬 Contact

**Telegram:** [RRR](https://t.me/microRustyme)

---

<div align="center">

🔥 **Optimized for Polymarket Copytrading Automation**  
Built for speed • Built for accuracy • Built for Web3 traders  

</div>
