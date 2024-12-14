# Vana Datapig Auto Bot

This repository contains a bot designed to interact with the [Datapig API](https://app.datapig.xyz). The bot can generate random preferences, sign messages, generate analysis, and mint files to the blockchain. It runs every 24 hours to process wallets automatically.

## Register Vana Datapig

- **Join**: https://app.datapig.xyz/?ref=rf6vaj

## Features

- **Automatic Wallet Processing**: It processes each wallet's data, generates preferences, signs messages, and submits them.
- **Retry Mechanism**: The bot retries minting files in case of failure (up to 3 retries).
- **Daily Limit Handling**: Automatically detects and handles the "Daily Limit Reached" response from the Datapig API and moves on to the next wallet.
- **Scheduled Execution**: The bot runs every 24 hours, automatically processing the wallets at the set interval.

---

## Requirements

Before you begin, ensure that you have met the following requirements:

- **Node.js**: Version 16 or higher.
- **npm**: Package manager to install dependencies.
- **Private keys** for the wallets you want to interact with.
- **Reference Codes** (optional but recommended for additional rewards) for your wallets.

---

## Installation

1. **Start quick installation script**
```
git clone https://github.com/airdropinsiders/datapig-bot.git
cd datapig-bot
```

2. **Setup pk.txt**
   
Create a file named pk.txt in the root directory of the project.
```bash
nano pk.txt
```
3. **Install**
   
```bash
npm install
```

4. **Running bot**

Once you've completed the setup, you can run the bot with the following command:

```bash
node main.js
```

This will process each wallet in the pk.txt file, generate random preferences, sign messages, submit them to the Datapig API, and mint files to the blockchain. The bot will repeat this process every 24 hours.

---
