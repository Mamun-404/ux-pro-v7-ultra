<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d0d1a,100:8b5cf6&height=80&text=UX%20PRO%20VIP%20%E2%80%94%20Quick%20Setup&fontSize=28&fontColor=ffffff" />

</div>

# ⚡ UX PRO VIP — Quick Start Guide

Already installed? Get the bot running in **under 60 seconds.**

---

## 🚀 One-Command Start

Navigate to the `uxpro` folder and run:

```bash
# Linux / VPS / Termux / macOS
source .venv/bin/activate && python3 ux.py

# Windows (CMD)
.venv\Scripts\activate && python ux.py
```

---

## ⌨️ Set Up the `ux` Shortcut

Run the bot from anywhere with just `ux`.

<details>
<summary><b>🐧 Linux / VPS / Termux</b></summary>

Run this once from inside the `uxpro/` folder:
```bash
echo "alias ux='cd $(pwd) && source .venv/bin/activate && python3 ux.py'" >> ~/.bashrc && source ~/.bashrc
```

Now just type `ux` from anywhere.
</details>

<details>
<summary><b>🪟 Windows (CMD) — create ux.bat</b></summary>

Create a file named `ux.bat` in `C:\Windows\` with:
```cmd
@echo off
cd /d "C:\path\to\ux-pro-v7-ultra\uxpro"
call .venv\Scripts\activate
python ux.py
```

Now open any CMD window and type `ux`.
</details>

<details>
<summary><b>🪟 Windows (PowerShell)</b></summary>

Add this to your PowerShell profile (`$PROFILE`):
```powershell
function ux {
    Set-Location "C:\path\to\ux-pro-v7-ultra\uxpro"
    .\.venv\Scripts\Activate.ps1
    python ux.py
}
```

Then type `ux` in any PowerShell window.
</details>

---

## 🔄 Update the Bot

When a new version is released:

```bash
cd ux-pro-v7-ultra
git pull
pip install -r uxpro/req.txt --upgrade
```

---

## 🧯 Quick Troubleshooting

| Error | Fix |
|-------|-----|
| `command not found: python3` | Use `python` instead, or reinstall Python |
| `No module named X` | Run `pip install -r req.txt` again |
| `Invalid License Key` | Check key spelling or contact [@U9KNOWN_X](https://t.me/U9KNOWN_X) |
| `Server timeout` | Wait 30 seconds — server waking up — try again |
| `device_id mismatch` | Contact [@U9KNOWN_X](https://t.me/U9KNOWN_X) to reset device |

---

<div align="center">

📖 Need full instructions? → [SETUP.md](SETUP.md)

**© 2025 Unknown X — UX PRO VIP · All Rights Reserved.**

[📩 @U9KNOWN_X](https://t.me/U9KNOWN_X)

</div>
