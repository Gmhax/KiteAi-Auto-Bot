# Kite AI Auto-Bot

An automated interaction bot for Kite AI platform with multi-wallet and proxy support.

## Register (If you don't have an account yet)

- https://testnet.gokite.ai?r=nEynYxrR

## 🌟 Features

- Multiple wallet support (manual input or file-based)
- Proxy support (HTTP/HTTPS/SOCKS)
- Rate limiting and retry mechanisms
- Multiple AI agents interaction
- Automatic question selection
- Usage reporting
- Graceful error handling

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm (Node Package Manager)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/Gmhax/KiteAi-Auto-Bot.git
cd KiteAi-Auto-Bot
```

2. Install dependencies:
```bash
npm install
```

3. Create a `wallets.txt` file for multiple wallets:
```
Ex.
0x1234567890abcdef1234567890abcdef12345678
0xabcdef1234567890abcdef1234567890abcdef12
```
4. Create a session:
```
screen -S gokite
```

Run the bot:
```bash
npm run start
```

5.Detach session:
## Click: CTRL A+D






The bot will prompt you to:
1. Choose connection mode (Direct/Proxy)
2. Choose wallet input mode (Manual/File)
3. Enter wallet address (if manual mode)

## ⚙️ Configuration Options

You can modify the following settings in `index.js`:

- `rateLimitConfig`: Adjust rate limiting parameters
- `agents`: Modify available AI agents
- `intervalBetweenCycles`: Change delay between interaction cycles

## 📢 Support



## ⚠️ Disclaimer

This bot is for educational purposes only. Use at your own risk and ensure compliance with Kite AI's terms of service.

## 📜 License

MIT License - feel free to use and modify for your own purposes.
