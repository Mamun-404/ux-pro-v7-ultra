<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d1a,30:00d4ff,70:8b5cf6,100:0d0d1a&height=220&section=header&text=UX%20PRO%20VIP&fontSize=72&fontColor=ffffff&fontAlignY=40&desc=AI-Powered%20Quotex%20Trading%20Bot%20%E2%80%94%20V7%20Ultra%20Secure&descAlignY=62&descSize=19&animation=twinkling" />

<br/>

[![Python](https://img.shields.io/badge/Python-3.10%2B-00d4ff?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20Windows%20%7C%20VPS-8b5cf6?style=for-the-badge&logo=linux&logoColor=white)](#)
[![Status](https://img.shields.io/badge/Status-Active-10b981?style=for-the-badge&logo=checkmarx&logoColor=white)](#)
[![Telegram](https://img.shields.io/badge/Get%20Access-@U9KNOWN__X-00d4ff?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/U9KNOWN_X)

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=3+AI+Models+%2B+31+Technical+Indicators;Real-Time+Market+Regime+Detection;Session+Token+%E2%80%94+Zero+Key+Exposure;Hardware-Locked+%2B+Server-Side+Core" alt="Typing SVG" />

<br/><br/>

> **⚡ The most advanced AI-powered binary options signal bot for Quotex.**
> Built with a 3-model ensemble, real-time market detection, and a session-token security system that keeps your core logic 100% off-disk.

</div>

---

<div align="center">

## 🧬 How The AI Works

</div>

```
                    ┌─────────────────────────────────────┐
                    │         MARKET DATA (Live)          │
                    └──────────────┬──────────────────────┘
                                   │  31+ Features
                    ┌──────────────▼──────────────────────┐
                    │         FEATURE ENGINEERING         │
                    │  RSI · MACD · BB · CCI · ATR · EMA  │
                    │  Williams %R · Momentum · Stoch ...  │
                    └───┬──────────────┬────────────┬──────┘
                        │              │            │
               ┌────────▼──┐  ┌────────▼──┐  ┌────▼───────┐
               │  XGBoost  │  │ LightGBM  │  │  CatBoost  │
               └────────┬──┘  └────────┬──┘  └────┬───────┘
                        │              │            │
                    ┌───▼──────────────▼────────────▼───┐
                    │        ENSEMBLE VOTE ENGINE        │
                    │   Adaptive Weighting · Confidence  │
                    └──────────────┬─────────────────────┘
                                   │
                    ┌──────────────▼──────────────────────┐
                    │      SIGNAL  ✅  or  ❌ NO TRADE     │
                    └─────────────────────────────────────┘
```

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🤖 AI Engine
- XGBoost + LightGBM + CatBoost ensemble
- Adaptive model weighting (last 50 trades)
- 31+ technical indicators
- Auto-adapts to live market performance

### 📊 Smart Analysis
- Market Regime Engine (Trending / Ranging / Volatile / Calm)
- Multi-Timeframe Confirmation (1m / 5m / 15m)
- Confidence scoring per signal
- Per-asset & per-timeframe analytics

</td>
<td width="50%">

### 🔒 Ultra Security
- Session token system (60s TTL, one-time use)
- Core logic **never stored on disk**
- Hardware-locked device binding
- Server-side encryption (XOR + Fernet)
- Anti-debug self-destruct system

### ⚡ Performance
- Real-time WebSocket market data
- Parallel signal processing
- Sub-second execution
- 24/7 stable on VPS

</td>
</tr>
</table>

---

## ⚙️ Trading Modes

<div align="center">

| Mode | Risk Level | Win Rate Target | Best For |
|:----:|:----------:|:---------------:|:--------:|
| `SAFE` | 🟢 Low | Conservative | Beginners |
| `NORMAL` | 🟡 Medium | Balanced | Daily use |
| `AGGRESSIVE` | 🟠 High | Optimistic | Experienced |
| `ELITE` | 🔴 Maximum | Max Signals | Experts only |

</div>

---

## 📋 Requirements

Before you start, refer to the [SETUP Guide](SETUP.md) for detailed instructions.

- ✅ **Python 3.10+** installed
- ✅ A **Quotex** account (email + password)
- ✅ A **Telegram Bot Token** — get from [@BotFather](https://t.me/BotFather)
- ✅ Your **Telegram Chat ID** — get from [@userinfobot](https://t.me/userinfobot)
- ✅ A valid **UX PRO License Key** — contact [@U9KNOWN_X](https://t.me/U9KNOWN_X)

---

## 📦 Installation

### Step 1 — Clone the Repository
```bash
git clone https://github.com/Mamun-404/ux-pro-v7-ultra.git
cd ux-pro-v7-ultra/uxpro
```

### Step 2 — Setup Environment & Dependencies

<details>
<summary><b>🐧 Linux / VPS / Termux / macOS</b></summary>

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r req.txt
```
</details>

<details>
<summary><b>💻 Windows (CMD)</b></summary>

```cmd
python -m venv .venv
.venv\Scripts\activate
pip install -r req.txt
```
</details>

<details>
<summary><b>💻 Windows (PowerShell)</b></summary>

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r req.txt
```
</details>

### Step 3 — Run

```bash
python ux.py
# or on Linux/macOS:
python3 ux.py
```

---

## 🎮 How to Use

Once started, the bot authenticates with the server and launches:

```
⚡ UX PRO VIP V7 — ULTRA SECURE LOADER
---------------------------------------
🔑 License Key: _______________
🔍 Authenticating...
✅ Core Unlocked. Launching...
```

**You will be prompted for:**

| # | Input | Description |
|:-:|-------|-------------|
| 1 | Quotex Email | Your Quotex account email |
| 2 | Quotex Password | Your Quotex account password |
| 3 | Telegram Bot Token | From [@BotFather](https://t.me/BotFather) |
| 4 | Telegram Chat ID | From [@userinfobot](https://t.me/userinfobot) |
| 5 | Strategy | `Ultra Hybrid` recommended |
| 6 | Timeframe | `1`, `2`, or `5` minutes |
| 7 | Trade Amount | Amount in USD per trade |
| 8 | Mode | `SAFE` recommended for beginners |

> 🔐 Credentials are encrypted with a hardware-derived key and saved locally — you won't need to re-enter them next time.

---

## ⚡ Quick Start Shortcut

<details>
<summary><b>🐧 Linux / VPS / Termux — set up <code>ux</code> command</b></summary>

```bash
echo "alias ux='cd $(pwd) && source .venv/bin/activate && python ux.py'" >> ~/.bashrc && source ~/.bashrc
```
Then just type `ux` to start.
</details>

<details>
<summary><b>💻 Windows (CMD) — create <code>ux.bat</code></b></summary>

Create `ux.bat` in `C:\Windows\`:
```cmd
@echo off
cd /d "C:\path\to\ux-pro-v7-ultra\uxpro"
call .venv\Scripts\activate
python ux.py
```
</details>

> 📖 Full shortcut guide → [QUICK_SETUP.md](QUICK_SETUP.md)

---

## 💎 Pricing & Access

<div align="center">

| Plan | Price | Duration | Best For |
|:----:|:-----:|:--------:|:--------:|
| 🚀 **Starter** | **$2** | 1 Day | Try it out |
| 🔥 **Popular** | **$5** | 3 Days | Weekend trader |
| ⭐ **Weekly** | **$10** | 7 Days | Regular use |
| 💎 **Monthly** | **$30** | 1 Month | Full power |

📌 Full features on all plans &nbsp;|&nbsp; 📌 Instant activation &nbsp;|&nbsp; 📌 Priority support on monthly

<br/>

### **📩 [Get Instant Access → @U9KNOWN_X](https://t.me/U9KNOWN_X)**

</div>

---

## 📁 Project Structure

```
ux-pro-v7-ultra/
│
├── uxpro/
│   ├── ux.py                  # Obfuscated secure loader (entry point)
│   ├── req.txt                # Python dependencies
│   │
│   ├── models/                # Trained AI model files
│   │   ├── xgboost_model.pkl
│   │   ├── lightgbm_model.pkl
│   │   ├── catboost_model.pkl
│   │   ├── scalers.pkl
│   │   └── performance.json
│   │
│   └── pyquotex/              # Enhanced Quotex WebSocket API
│       ├── api.py
│       ├── stable_api.py
│       ├── http/
│       └── ws/
│
├── .gitignore
├── README.md
├── SETUP.md
└── QUICK_SETUP.md
```

> 🔒 The trading core is securely stored on the server. It is fetched at runtime and executed in memory — never written to disk.

---

## 🛠️ Troubleshooting

<details>
<summary><b>❌ "Invalid or Expired License"</b></summary>

Your license has expired or the key is incorrect. Contact [@U9KNOWN_X](https://t.me/U9KNOWN_X) to renew or verify.
</details>

<details>
<summary><b>❌ "Auth Error: device_id mismatch"</b></summary>

Your license is bound to a different machine. Contact the owner to reset your device binding.
</details>

<details>
<summary><b>❌ "Server timeout — try again"</b></summary>

The server may be waking up from sleep (free tier). Wait 30 seconds and try again.
</details>

<details>
<summary><b>❌ Missing packages / pip errors</b></summary>

```bash
pip install -r req.txt --upgrade
python --version  # Must be 3.10+
```
</details>

<details>
<summary><b>❌ Bot keeps disconnecting on VPS</b></summary>

Ensure your VPS allows outbound traffic on ports `80` and `443`. Check logs:
```bash
tail -f bot_activity.log
```
</details>

---

## 📞 Contact & Support

<div align="center">

| | |
|:---:|:---|
| 👨‍💻 **Developer** | Mamun Hasan (Unknown X) |
| 📱 **Telegram** | [@U9KNOWN_X](https://t.me/U9KNOWN_X) |
| 📢 **Channel** | [Unknown X Official](https://t.me/unknown_x_official) |

</div>

---

## ⚠️ Disclaimer

> Trading binary options involves **significant financial risk**. Past performance does not guarantee future results. This software is provided for **educational and research purposes only**. The developer is not responsible for any financial losses. Always trade responsibly.

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d1a,50:8b5cf6,100:00d4ff&height=120&section=footer&animation=twinkling" />

**© 2025 Unknown X — UX PRO VIP Trading Bot · All Rights Reserved.**

</div>
