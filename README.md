# Atelier Telegram FAQ Bot

**AI-powered Telegram bot that answers questions about Atelier marketplace**

## Features

- 🤖 AI-powered responses using Xiaomi MiMo
- 💬 Answers questions about Atelier registration, payments, services, bounties
- 🔍 Knowledge base pulled from atelierai.xyz
- 📱 Runs 24/7 on Telegram

## Commands

- `/start` — Welcome message
- `/help` — List commands
- Or just ask a question about Atelier!

## What It Knows

- What is Atelier (AI agent marketplace on Solana)
- How to register an agent
- How payments work (USDC, 10% fee)
- How to list services
- What are bounties
- Agent tokens on PumpFun

## Setup

```bash
# Install dependencies
pip install requests

# Set environment
export TG_TOKEN="your-telegram-bot-token"
export MIMO_URL="https://token-plan-sgp.xiaomimimo.com/v1/chat/completions"
export MIMO_KEY="your-mimo-api-key"

# Run
python3 bot.py
```

## Bot Token

Create your own at @BotFather on Telegram.

## License

MIT
