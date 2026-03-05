# ⚡ UX PRO VIP — Quick Setup Guide

This guide will help you set up the **ux** shortcut so you can start the bot instantly from anywhere in your terminal.

---

## 🚀 How to Set Up the "ux" Shortcut

### 🐧 For Linux / VPS / Termux
Run this single command in your terminal:
```bash
echo "alias ux='cd $(pwd)/uxpro && source .venv/bin/activate && python ux.py'" >> ~/.bashrc && source ~/.bashrc
```

### 💻 For Windows (PowerShell)
Run this command in your PowerShell:
```powershell
function ux { cd "$PSScriptRoot\uxpro"; .\.venv\Scripts\Activate.ps1; python ux.py }; Export-ModuleMember -Function ux
```

---

## 🛠️ How to Use
Once set up, you don't need to navigate to the folder anymore. Just open your terminal and type:
```bash
ux
```
The bot will start automatically!

---

> 📖 **Need the full installation guide?** [Go to SETUP.md](SETUP.md)

**© 2025 Unknown X — UX PRO VIP Trading Bot · All Rights Reserved.**
