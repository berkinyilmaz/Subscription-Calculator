# Subscription Calculator

Minimal web app to **track your subscription expenses** instantly.
No signup.
No API.
Just accurate expense tracking.

---

## Live Demo

https://subscription-calculator-silk.vercel.app/

---

## Features

- **20+ popular apps** pre-loaded (Netflix, Spotify, ChatGPT Plus, Claude Pro, Disney+, etc.)
- **Custom subscriptions** – add any service with custom name and color
- **Flexible billing cycles:**
  - Monthly
  - Yearly (auto-converts to monthly)
  - Weekly (auto-converts to monthly)
- **Financial dashboard:**
  - Monthly total
  - Yearly projection
  - Daily average
  - Active subscription count
- **Full CRUD** – add, edit, delete subscriptions
- **Auto-save** – data persists in browser localStorage
- Clean, responsive, Apple-inspired dark UI
- No authentication
- No ads
- No watermarks

---

## Tech Stack

- React (Vite)
- Vanilla CSS (Apple-inspired UI)
- LocalStorage (data persistence)
- Vercel (static deploy)

---

## How It Works

1. **Select a service** from 20+ popular apps or add custom
2. **Enter the price** and billing cycle
3. **View your dashboard** with monthly, yearly, and daily breakdowns
4. **Edit or remove** subscriptions anytime

> Everything is computed client-side. Nothing is uploaded.

---

## Privacy

All processing happens **locally in your browser**.
No data is sent to any server.

---

## Installation

```bash
# Clone the repo
git clone <YOUR_REPO_URL>

# Install dependencies
cd subscription-calculator
npm install

# Run locally
npm run dev
```
