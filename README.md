# Steppe

**Always know where you stand. No accounts, no servers, no subscriptions.**

Steppe is a free, completely private budget tracker that runs entirely in your browser. Your financial data never leaves your device.

Netlify link:
https://steppeapp.netlify.app

## Features

- **Budget tracking** — Set monthly budgets across custom categories with the 50/30/20 rule as a starting point
- **CSV import** — Import bank statements from SoFi, Chase, and Bank of America with automatic merchant detection and categorization
- **Pending transactions** — Log upcoming expenses before they hit your bank
- **Spending insights** — Cumulative spending charts, cash flow breakdowns, category rankings, and over-budget alerts
- **Auto-categorization** — The app learns your merchant-to-category mappings over time
- **Backup & restore** — Export your data as JSON anytime, restore on another device
- **Installable PWA** — Works offline as a native-like app on phone or desktop

## Getting Started

No build tools or dependencies required. Steppe is pure HTML, CSS, and JavaScript.

1. Open `index.html` in a browser (or serve with any static file server)
2. Click **Open App** to launch the budget tracker
3. Complete the setup wizard to configure your income and budget categories
4. Start adding transactions or import a bank statement

### Install as an App

- **iPhone**: Safari → Share → Add to Home Screen
- **Android**: Chrome → Menu → Add to Home Screen
- **Desktop**: Chrome/Edge → Install icon in address bar

## Privacy

- All data is stored locally in your browser using LocalStorage
- No backend servers, no accounts, no tracking, no analytics
- You own your data — export it anytime

## Tech Stack

- Vanilla JavaScript (ES6+)
- HTML5 & CSS3
- Canvas API for charts
- Service Worker for offline support
- No frameworks, no build step

## License

Open source — see the repository for details.
