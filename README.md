# Autonomous AI Advertising Agent with Crypto Payments

An AI agent that creates complete advertising campaigns while autonomously paying for premium services using cryptocurrency via the X402 payment protocol.

## ⚠️ **SAFETY NOTICE**
**TESTNET ONLY - DO NOT USE REAL FUNDS**
- Uses Base Sepolia testnet exclusively
- Only use test credentials and testnet tokens
- Never run with production wallets or mainnet

## Prerequisites

- Python 3.10+
- Coinbase Developer Platform account (for testnet API keys)
- OpenWeather API key
- Base Sepolia testnet wallet with test USDC

## Installation

```bash
git clone https://github.com/ucegbe/ai-advertising-agent-with-crypto-payments.git
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in the project root:

```env
# Coinbase Developer Platform (Base Sepolia Testnet)
CDP_API_KEY_ID=your_cdp_api_key_id
CDP_API_KEY_SECRET=your_cdp_api_key_secret
CDP_WALLET_SECRET=your_cdp_wallet_secret

# Payment receiving address (Base Sepolia testnet address)
ADDRESS=0xYourTestnetAddressHere

# OpenWeather API
OPENWEATHER_API_KEY=your_openweather_api_key

# Server configuration (optional)
BASE_URL=http://0.0.0.0:4021
```

## Quick Start

1. **Start the payment server:**
   ```bash
   python paid_server.py
   ```

2. **Run the notebook:**
   Open `agentkit-x402-strands.ipynb` and execute cells sequentially

3. **Generate ads:**
   The agent will automatically discover services, make payments, and create complete ad campaigns with visuals.

## Key Features

- 🤖 Autonomous AI agent using Strands + Claude Sonnet 4
- 💳 Cryptocurrency micropayments via X402 protocol  
- 🎨 AI image generation for ad visuals
- 🌤️ Real-time weather data integration
- 📱 Multi-platform ad creation (social, display, email)
- 📄 Complete HTML campaign output

## Architecture

- **Agent**: Strands AI framework + Coinbase AgentKit
- **Payments**: X402 protocol on Base Sepolia testnet
- **Services**: Payment-gated image generation and weather APIs
- **Output**: Production-ready HTML ad campaigns

## Safety Reminders

- ✅ Base Sepolia testnet only
- ✅ Test credentials and tokens only  
- ❌ Never use real funds or mainnet
- ❌ Never expose production keys

---

**See the notebook for detailed explanations and step-by-step execution.**
