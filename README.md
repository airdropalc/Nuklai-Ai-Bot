# 🤖 Nuklai Automation Bot

Streamline your faucet claims and validator interactions on the Nuklai network. This bot is designed to automate repetitive tasks, saving you time and ensuring consistent activity for multiple accounts.

[![Telegram](https://img.shields.io/badge/Community-Airdrop_ALC-26A5E4?style=for-the-badge&logo=telegram)](https://t.me/airdropalc/1737)


---

## ✨ Key Features

* **💧 Automated Faucet Claims:** Automatically requests tokens from the Nuklai faucet to keep your wallets funded for ongoing activities.
* **👥 Multi-Account Support:** Seamlessly manage and run tasks for an unlimited number of wallets. Simply add your mnemonics, and the bot handles the rest.
* **🌐 Flexible Proxy Integration:** Route your traffic through proxies to avoid IP-based rate limits and enhance operational security. This feature is completely optional.

---

## ⚠️ Important Prerequisite: Manual Validator Setup

Before using this bot, you **must** perform the initial validator interactions **manually** for each wallet. The bot is designed to maintain activity, not to perform the very first setup.

**Failure to do this first will result in the bot not working correctly.**

---

## 🛠️ Setup and Installation Guide

Follow these steps carefully to get the bot up and running.

### 1. Clone the Repository

First, clone the project files to your local machine and navigate into the directory.

```bash
git clone [https://github.com/NoInternetSecured/Nuklai-Auto-Bot.git](https://github.com/NoInternetSecured/Nuklai-Auto-Bot.git)
cd Nuklai-Auto-Bot
```

### 2. Install Dependencies

Install the required Node.js packages using `npm`.

```bash
npm install
```

### 3. Configure Your Wallets

Add your wallet mnemonics to the `mnemonics.txt` file. **Each mnemonic must be on a new line.**

```bash
# Use your preferred text editor, like nano or vscode
nano mnemonics.txt
```

**Example `mnemonics.txt`:**
```
word ski amazing pulp vague vibrant silly rural velvet frost aspect junk
estate december barrel onion vibrant silly rural velvet frost amazing pulp junk
```

### 4. Configure Proxies (Optional)

If you wish to use proxies, add them to the `proxy.txt` file. Each proxy should be on a new line in the format `ip:port:user:pass`. If your proxies don't require authentication, use `ip:port`.

```bash
nano proxy.txt
```

### 5. Run the Bot

Once the configuration is complete, start the bot with the following command:

```bash
node main.js
```

The bot will now begin executing tasks for the wallets you provided.

---

## 🚨 Disclaimer & Security Warning

**This project is provided for educational purposes only. Use it wisely and at your own risk.**

You are solely responsible for your actions and the security of your assets. Storing mnemonics in plain text files is risky. Please understand the security implications before using this tool.

The authors and contributors of this project are **not responsible for any form of financial loss** or other damages.

---
> From the [Airdrop ALC](https://t.me/airdropalc) community.

## License

![Version](https://img.shields.io/badge/version-1.0.0-blue)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]()

---
