# Polymarket Copy Trading Bot

A high-performance Polymarket Copy Trading Bot that automatically
mirrors trades from any selected Polymarket trader in real time.
Designed for reliability, speed, and configurable risk management.

## Features

-   **Auto Copy Trading** -- Automatically replicates trades from a
    target Polymarket trader.
-   **Real-Time Monitoring** -- Detects and mirrors new orders instantly
    using Polymarket CLOB feeds.
-   **Risk Controls** -- Adjustable fetch interval, retry limits, and
    timestamp filtering.
-   **MongoDB Logging** -- Saves trade and system events for debugging
    or analytics.
-   **Simple Configuration** -- All settings controlled through a `.env`
    file.

## Installation

### 1. Install Node.js (latest LTS recommended)

### 2. Clone the repository

``` bash
git clone https://github.com/ivorn42/polymarket-copy-trading-bot.git
cd polymarket-copy-trading-bot
```

### 3. Create your `.env` file

``` bash
touch .env
```

Add the following:

``` env
# Wallet to copy trades from
USER_ADDRESS="TARGET_WALLET_ADDRESS"

# Your wallet
PROXY_WALLET="YOUR_POLYMARKET_WALLET"
PRIVATE_KEY="YOUR_PRIVATE_KEY"

# Polymarket CLOB Endpoints
CLOB_HTTP_URL="https://clob.polymarket.com/"
CLOB_WS_URL="wss://ws-subscriptions-clob.polymarket.com/ws"

# Bot behavior
FETCH_INTERVAL=1        # check target trader every 1 second
TOO_OLD_TIMESTAMP=3600  # ignore trades older than 1 hour (3600 seconds)
RETRY_LIMIT=3           # retry failed operations up to 3 times

# MongoDB
MONGO_URI="YOUR_MONGODB_URI"

# Polygon RPC + USDC Contract
RPC_URL="https://polygon-mainnet.infura.io/v3/<YOUR_INFURA_KEY>"
USDC_CONTRACT_ADDRESS="0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174"
```

## Setup & Run

### Install dependencies

``` bash
npm install
```

### Build

``` bash
npm run build
```

### Start the bot

``` bash
npm run start
```

## Contributing

Contributions are welcome!\
Feel free to open an issue or submit a pull request.\
If this project helps you, please consider giving it a ⭐️.

## Contact

**Telegram:** https://t.me/ivorn42
