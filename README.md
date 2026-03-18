# Steppe

**Track your monthly spending. Budget your needs. No accounts no subscriptions.**

Any feedback is welcomed! Please don't hesitate to contact to add any features or report bugs. 
Always happy to help and make this tool as useful as it can be for everyone!
You can either report an issue through github to let me know of anything you would like to add
or contact me through reddit my username is u/nanoMiniPump 

Steppe is a free, completely private budget tracker that runs entirely in your browser. Your financial data never leaves your device.

Netlify link:
https://steppeapp.netlify.app

Disclaimer: The app itself is fully open source and runs entirely in your browser, Netlify only serves the HTML file, it never sees your data. 
If you don't trust Netlify, you can download the HTML file directly from GitHub and open it locally on your computer with no hosting involved at all.
I will show steps on how to use it on your phone (if you are iPhone user, because I beleive Android users are lucky where they can just tap on the donwloaded file) 

## Offline Instalation for iPhone

You will need Edge (crazy I know)

download the app.html from GitHub on your phone (save it to the Files app)
In the Files app fine the app.html
hold and tap the share button 
It will ask which app to open with, if you click "more" you can then choose Edge
It will open the Steppe app through Edge and you can just use Edge to use it
Do remember to make backups (in setting you can export your data) in case Edge clears you cache


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
