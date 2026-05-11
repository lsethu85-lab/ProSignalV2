# 📈 ProSignalv2 – Stock Signal Dashboard (Fixed & Stable)

A **fully client‑side, key‑free stock analysis dashboard** that combines **fundamentals, technicals, news, risk scoring, and AI‑assisted signals** in a modern, professional UI.

✅ This repository contains the **latest fixed `index.html`** where **Add Stock** and **Quick Picks BUY signals** are fully working and the **original full UI is preserved**.

---

## ✨ Features

### 📁 My Portfolio
- Add any stock ticker (e.g. `AAPL`, `MSFT`, `NVDA`)
- Live price, daily change & volume
- Clear **BUY / HOLD / TRIM / SELL** signal badges
- Automatic refresh based on market hours

### ⚡ Quick Picks
- Curated **BUY‑signal stocks** (S&P 500 & Nasdaq 100)
- Sector‑based grouping
- One‑click **Add to Portfolio**
- Bulk **Add All to Portfolio**
- Automatically runs full analysis after adding

### 📊 Deep Analysis (per stock)
- Overall score (0–100)
- Fundamentals grade (A–D)
- Technical indicators:
  - RSI, MACD, Bollinger Bands
  - MA20 / MA50 / MA200
- Risk score & risk label
- ATR‑based stop‑loss suggestion
- Position sizing suggestion
- Chart pattern detection
- Latest news with sentiment scoring

### 🤖 AI‑Enhanced Signals (Safe Fallback)
- Uses Pollinations (Mistral) for reasoning & explanation
- Automatically falls back to rule‑based engine if AI is unavailable
- **No API key required**

---

## ✅ What Was Fixed in This Version

This version resolves a critical JavaScript issue that previously broke functionality:

- ✅ Fixed a broken toast notification block that stopped JS execution
- ✅ Restored **Add Stock** fetching & rendering
- ✅ Restored **Quick Picks → Add → Analyze** flow
- ✅ No UI was removed or simplified

This is the **full dashboard**, not a demo or reduced build.

---

## 🚀 Getting Started

### Option 1: Run Locally (Recommended)
Browsers block API calls if opened directly from the file system.

```bash
python -m http.server 8080