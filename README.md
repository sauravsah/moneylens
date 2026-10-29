# MoneyLens

A private, single-file personal finance tracker. It turns the transaction alerts your bank already sends (email or SMS) into a live dashboard: balance, income, expenses, budgets, recurring bills and a tagged transaction list.

- One HTML file. No backend, no accounts, no tracking. Your data lives in your browser.
- Money comes in through a **feed you own**: a small Google Apps Script deployed on your own Gmail that reads only bank-alert emails (and can accept SMS text forwarded from your phone). Setup walks you through it in four steps.
- Everything is tagged inline: preset chips or free text per transaction.
- Works fully offline in manual mode too.

## Run it

Open https://sauravsah.github.io/moneylens/ or download `index.html` and open it locally. Nothing leaves your machine except the feed URL you choose to connect.

## Privacy

- The feed URL you paste is stored only in your browser's local storage.
- The feed script runs as your own Google account, on your own Drive file, and filters for bank alerts only (OTPs and marketing are skipped).
- This public copy ships with demo data and no feed URL; your own copy carries nothing until you connect it.
