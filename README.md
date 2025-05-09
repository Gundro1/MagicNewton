# 🚀 Bot Setup Instructions

Welcome to the bot setup guide! Follow the steps below to install and configure the bot correctly. This guide is designed to be beginner-friendly, with clear explanations for each step.

🔹 Method 1: Install via Git (Recommended)
1️⃣ Clone the bot repository:

```bash
git clone https://github.com/Gundro1/MagicNewton.git
cd MagicNewton/MagicNewton
```

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation Steps](#installation-steps)
3. [Configuration Files](#configuration-files)
   - [`configs.json`](#1-configsjson)
   - [`datas.txt`](#2-datastxt)
   - [`wallets.txt`](#3-walletstxt)
   - [`proxies.txt`](#4-proxiestxt)
4. [Running the Bot](#running-the-bot)
5. [Contact and Support](#contact-and-support)

---

## Prerequisites

Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here:  
```bash
sudo apt update
  sudo apt install nodejs npm
```

---

## Installation Steps

1. **Download and Extract the Bot Files:**

   - Extract the bot package into a folder on your computer.

2. **Install Dependencies:**
   Open your terminal or command prompt, navigate to the folder where the bot files are located, and run:

   ```bash
   npm install --force user-agents axios colors https-proxy-agent socks-proxy-agent 
   ```

   If you encounter an Execution Policy error on Windows, run:

   ```bash
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
   ```

   Then, run the npm install command again.

3. **Prepare Configuration Files:**
   - Ensure all configuration files are set up correctly before running the bot (see [Configuration Files](#configuration-files) section).

---

## Configuration Files

### 1. `configs.json` - 📜 Adjust Bot Settings

This file controls the bot’s behavior. Below is an example configuration:

```json
{
  "timeZone": "en-US",
  "rotateProxy": false,
  "skipInvalidProxy": false,
  "proxyRotationInterval": 2,
  "delayEachAccount": [5, 8],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 100,
  "doTasks": false
}
```

- **Fields Explained:**
  - `timeZone`: Time zone setting (e.g., "en-US").
  - `rotateProxy`: Enable or disable proxy rotation.
  - `skipInvalidProxy`: Skip invalid proxies if `true`.
  - `proxyRotationInterval`: Time interval (in minutes) for rotating proxies.
  - `delayEachAccount`: Random delay range (in seconds) between accounts.
  - `timeToRestartAllAccounts`: Time (in seconds) to restart all accounts.
  - `howManyAccountsRunInOneTime`: Number of accounts to run simultaneously.
  - `doTasks`: Enable task completion.

### 2. `datas.txt` - 🗂️ User Data

- Fill the data for `datas.txt` file, get data from [here](https://t.me/KeoAirDropFreeNee/1418). This file contains user data in the following format:

```txt
cookie
cookie
cookie
```

_Note: Each row for each account_

### 3. `wallets.txt` - 💼 Wallet Addresses
- Add your wallet addresses in the following format:

```txt
abc...xyz
abc...xyz
```

_Note: Wallet updates are currently not supported._

### 4. `proxies.txt` - 🌐 Proxy List (Optional)

If you are using proxies, add them here. Leave the file blank if you are not using proxies. Supported formats:
- [Get it from here](https://www.webshare.io/?referral_code=4l5kb3glsce7)

```txt
http://host:port
http://user:pass@host:port
https://user:pass@host:port
socks4://user:pass@host:port
socks5://user:pass@host:port
```

_Note: each row for each account_

---

## Running the Bot

1. Navigate to the folder containing the bot files:

   ```bash
   cd MagicNewton
   ```

2. Run the bot using the following command:
   ```bash
   node meomundep.js
   ```

---

## All thanks to the rightful owner [MewMunDep](https://github.com/MeoMunDep/MeoMunDep)

- **Help me with your referral** [Referral Link](https://magicnewton.com/portal?referral=drhlwdfq5hlxsdzu)

If you encounter any issues or have questions, feel free to reach out:

- **Contact for work:** [Telegram](https://t.me/gictdao)

Your support is greatly appreciated! 🐱

---

Enjoy using the bot! 🚀
