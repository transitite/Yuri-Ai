# Yuri
Yuri is an AI agent Build with [rig](https://github.com/0xPlaygrounds/rig/)

![banner](https://pbs.twimg.com/media/GgVQsEyWoAAWO7M?format=jpg&name=900x900)

Follow our AI agent: [@Yuri_AI](https://x.com/YuriRig_)

## Added Features

- **Twitter Client Integration**
  - Cookie-based authentication
  - No Twitter API costs
  - Interact with the home timeline (like, retweet, quote)
  - Post tweets with images
  - Reply to mentions
  - Perform random Twitter tasks

- **Telegram Service**
  - Complete Telegram bot integration
  - Real-time messaging capabilities

- **Heuris Image Generator**
  - AI-powered image generation for tweets

- **Enhanced AI Agent Communication**
  - Pre-defined message examples
  - Customizable topics
  - Configurable communication styles

- **Solana Trading**
  - Transfer SOL: Send SOL to a specified wallet address.
  - Token Swaps: Swap SOL for other tokens directly using Jup.ag.
  - Market Analysis: Analyze Solana market trends using GMGN data.
  - Portfolio Insights: Evaluate and analyze current portfolio holdings.

## Prerequisites

- Rust programming language
- Cargo package manager
- Git

## Getting Started

### Environment Variables
To get the cookie string, you need to:
1. Open Chrome DevTools (F12)
2. Go to Network tab
3. Select Fetch/XHR
4. Choose any request that starts with https://x.com/i/api/graphql/
5. In Request Headers, copy the cookie value
6. Paste it in your .env file



```env
# Clients to run
CLIENTS = "discord,twitter,telegram"

# Twitter Configuration
TWITTER_USERNAME=your_username
TWITTER_PASSWORD=your_password
TWITTER_EMAIL=your_email
TWITTER_2FA_SECRET=your_2fa_secret
TWITTER_COOKIE_STRING=your_cookie_string

# Bot Tokens
TELEGRAM_BOT_TOKEN=your_telegram_token
DISCORD_API_TOKEN=your_discord_token

# API Keys
OPENAI_API_KEY=your_openai_key
HEURIST_API_KEY=your_heurist_key

# Solana Configuration
SOLANA_RPC_URL=https://api.mainnet-beta.solana.com
SOLANA_PRIVATE_KEY=your_solana_private_key
SOLANA_WALLET_ADDRESS=your_solana_wallet_address
```
## Usage

Start the service:
```bash
cargo run
```

## Credits

- Original project: [dojoengine/asuka](https://github.com/dojoengine/asuka)
- Additional features and modifications by [Yuri](https://github.com/transitite/YuriRig_)
