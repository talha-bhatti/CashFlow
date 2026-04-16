# 💸 CashFlow

A personal finance tracker PWA — no account, no server, everything stays on your device.

---

## Features

- **Add Income & Expenses** — title, amount, category, date, time, and description
- **Backdate entries** — log transactions from any date in the past
- **Smart suggestions** — titles and categories auto-suggest from your history as you type
- **Search** — filter all transactions instantly from the home screen
- **History view** — browse by month with income/expense summary and category breakdown per month
- **Light / Dark mode** — toggle in Settings
- **PIN lock** — protect the app with a 4-digit PIN
- **Export JSON** — full data backup you can restore later
- **Export CSV** — spreadsheet-friendly export
- **Import & Merge / Replace** — restore from a backup file
- **Custom categories** — type any category, it gets saved for next time
- **Fully offline** — works with no internet after first load

---

## Install on Android (Chrome)

1. Open Chrome and go to your CashFlow URL
2. Tap the **⋮ menu** → **Add to Home screen** (or tap the install banner if it appears)
3. Tap **Add** to confirm
4. Open the app once while online — it caches everything for offline use

> Also works in Samsung Internet and Firefox for Android via their respective menus.

---

## Install on iPhone / iPad (Safari)

> ⚠️ Must use **Safari** — Chrome and Firefox on iOS cannot install PWAs.

1. Open **Safari** and go to your CashFlow URL
2. Tap the **Share button** (square with arrow) — bottom of screen on iPhone, top-right on iPad
3. Tap **Add to Home Screen**
4. Tap **Add**
5. Open the app once while online to cache it for offline use

> Data in the installed app is separate from Safari browser tabs — always use the home screen icon.

---

## Backup & Transfer to a New Phone

1. Go to **Settings → Export JSON** on your old phone
2. Save or send the file to your new phone (email, AirDrop, etc.)
3. Open CashFlow on the new phone
4. Go to **Settings → Import & Replace** and select the file

Use **Import & Merge** instead if you want to combine data from both phones without overwriting.

---

## PIN Lock

- Go to **Settings → Security → Set PIN**
- Enter and confirm a 4-digit PIN
- The PIN screen appears every time the app opens

To change or remove: tap **Change** or **Remove** in the Security section — you'll need to enter the current PIN first.

> ⚠️ There is no PIN recovery. If you forget it, you'll need to clear the site's browser data, which also deletes your transactions. Export a backup regularly.

---

## Data & Privacy

- No account, no server, no analytics
- All data is stored in your browser's `localStorage`
- The only external request is loading fonts from Google Fonts on first visit
- Clearing browser/site data will erase your transactions — keep regular JSON backups

---

## Tech

Plain HTML, CSS, and JavaScript — no frameworks, no build step, no dependencies.
