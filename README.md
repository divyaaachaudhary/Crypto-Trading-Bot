# Crypto-Trading-Bot #

# Binance Futures Testnet Trading Terminal #

A full-stack web trading terminal for Binance USDT-M Futures Testnet built with Python & Flask.
Place real futures orders, test strategies, and build automated trading systems in a safe sandbox environment.

# Overview #

This project is a browser-based futures trading cockpit that connects directly to Binance Futures Testnet using the official API.

It allows traders, students, and developers to:

• Learn futures trading safely
• Test order execution logic
• Build & plug automated strategies
• Understand exchange APIs
• Create personal trading dashboards

All without risking real money.

# What This Project Has #
- Feature	Description
- Market Orders	Buy / Sell instantly
- Limit Orders	Place GTC limit orders
- Wallet Balance Panel	Shows USDT Futures wallet
- Strategy Engine	Grid & TWAP trading backend
- Secure API Handling	Keys never exposed to frontend
- Web UI	Clean trading dashboard
- Logging	Structured API & error logs
- Testnet Safe	100% fake funds environment
  
# Architecture #

Browser UI (HTML/CSS)
        ↓
Flask Web Server
        ↓
Trading Engine (BasicBot)
        ↓
Binance Futures Testnet API

# Installation #
git clone 
cd binance-futures-testnet-bot
pip install flask python-binance python-dotenv
python webapp.py
Open:

http://127.0.0.1:5000

# Test Funds #

- Get free futures test funds at:
- Wallet → Get Test Funds on Binance Testnet.

# Use Cases #

• Practice futures trading
• Build bots & strategies
• Demo trading dashboards
• College / hackathon projects
• API experimentation

# Safety #

Uses Binance Futures Testnet only.
No real money access.
Keys never reach the frontend.
