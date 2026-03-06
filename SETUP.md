<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d0d1a,100:00d4ff&height=80&text=UX%20PRO%20VIP%20%E2%80%94%20Setup%20Guide&fontSize=28&fontColor=ffffff" />

</div>

# 🚀 UX PRO VIP — Full Setup Guide

Complete installation guide for all platforms: Windows, Linux, VPS, macOS, and Termux.

---

## 📋 Table of Contents

1. [Python Installation](#1-python-installation)
2. [Quotex Account](#2-quotex-account)
3. [Telegram Setup](#3-telegram-setup)
4. [Git Installation](#4-git-installation)
5. [Virtual Environment](#5-virtual-environment)
6. [Install Dependencies](#6-install-dependencies)
7. [Run the Bot](#7-run-the-bot)

---

## 1. Python Installation

UX PRO VIP requires **Python 3.10 or newer**.

<details>
<summary><b>🪟 Windows</b></summary>

1. Go to [python.org/downloads/windows](https://www.python.org/downloads/windows/)
2. Download the latest **Python 3.10+** installer (64-bit)
3. Run the installer — **check "Add Python to PATH"** on the first screen
4. Verify:
```cmd
python --version
pip --version
```
</details>

<details>
<summary><b>🐧 Linux (Ubuntu/Debian)</b></summary>

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install software-properties-common -y
sudo add-apt-repository ppa:deadsnakes/ppa -y
sudo apt update
sudo apt install python3.11 python3.11-venv python3.11-dev -y

# Set as default (optional)
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.11 1

# Verify
python3 --version
```
</details>

<details>
<summary><b>📱 Termux (Android)</b></summary>

```bash
pkg update && pkg upgrade -y
pkg install python -y

# Verify
python --version
```
</details>

<details>
<summary><b>🍎 macOS</b></summary>

```bash
# Install Homebrew if not present
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install Python
brew install python@3.11

# Verify
python3 --version
```
</details>

---

## 2. Quotex Account

UX PRO VIP trades on the Quotex platform.

1. Register at [quotex.com](https://quotex.com)
2. Verify your email
3. Note your **email** and **password** — you'll enter them when the bot starts
4. For testing, the **Demo account** works perfectly — no real money needed

---

## 3. Telegram Setup

The bot sends signals and notifications to your Telegram.

### 🤖 Get a Bot Token

1. Open Telegram → search **@BotFather** → `/start`
2. Send `/newbot`
3. Choose a name and username (must end in `bot`)
4. Copy the **API Token** — looks like `123456:ABC-DEF...`

### 🆔 Get Your Chat ID

1. Open Telegram → search **@userinfobot** → `/start`
2. The bot replies with your **Chat ID** (a number like `987654321`)

---

## 4. Git Installation

<details>
<summary><b>🪟 Windows</b></summary>

1. Download from [git-scm.com/download/win](https://git-scm.com/download/win)
2. Run installer with default options
3. Verify:
```cmd
git --version
```
</details>

<details>
<summary><b>🐧 Linux</b></summary>

```bash
sudo apt install git -y
git --version
```
</details>

<details>
<summary><b>📱 Termux</b></summary>

```bash
pkg install git -y
```
</details>

<details>
<summary><b>🍎 macOS</b></summary>

```bash
brew install git
```
</details>

### Clone the Repository

```bash
git clone https://github.com/Mamun-404/ux-pro-v7-ultra.git
cd ux-pro-v7-ultra/uxpro
```

---

## 5. Virtual Environment

A virtual environment keeps dependencies isolated.

<details>
<summary><b>🐧 Linux / macOS / VPS / Termux</b></summary>

```bash
python3 -m venv .venv
source .venv/bin/activate
```
</details>

<details>
<summary><b>🪟 Windows (CMD)</b></summary>

```cmd
python -m venv .venv
.venv\Scripts\activate
```
</details>

<details>
<summary><b>🪟 Windows (PowerShell)</b></summary>

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```
</details>

You'll see `(.venv)` in your terminal — that means it's active.

---

## 6. Install Dependencies

With the virtual environment active:

```bash
pip install -r req.txt
```

This installs all required packages: XGBoost, LightGBM, CatBoost, pyquotex, cryptography, and more.

---

## 7. Run the Bot

```bash
# Linux / macOS / VPS / Termux
python3 ux.py

# Windows
python ux.py
```

**What happens:**

```
⚡ UX PRO VIP V7 — ULTRA SECURE LOADER
---------------------------------------
🔑 License Key: _______________
🔍 Authenticating...
✅ Core Unlocked. Launching...
```

The bot contacts the server, verifies your license, downloads the encrypted core to memory, and launches — nothing sensitive is stored on your device.

---

## 💡 VPS Tips

**Keep the bot running after disconnect:**
```bash
# Using screen
screen -S uxpro
python3 ux.py
# Detach: Ctrl+A then D
# Reattach: screen -r uxpro

# Or using nohup
nohup python3 ux.py > bot_activity.log 2>&1 &
```

**Auto-restart on reboot:**
```bash
# Add to crontab
crontab -e
# Add this line:
@reboot cd /path/to/ux-pro-v7-ultra/uxpro && source .venv/bin/activate && python3 ux.py
```

---

<div align="center">

**© 2025 Unknown X — UX PRO VIP · All Rights Reserved.**

[📩 Get License → @U9KNOWN_X](https://t.me/U9KNOWN_X)

</div>
