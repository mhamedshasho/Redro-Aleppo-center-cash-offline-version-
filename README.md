# Redro Aleppo Center Cash — Offline

A standalone, offline-first accounting notebook. No sign-in, Supabase, remote database, API, or backend.

## Features

- Multiple customer accounts
- Account balances and transaction history
- Add, edit, and delete accounts and transactions
- Local persistence using IndexedDB
- JSON backup export and restore
- Light and dark themes
- Responsive Arabic interface
- PWA shell caching for offline use after the first successful visit

## Run

Open `index.html` in a modern browser. For installable PWA and service-worker offline caching, publish through GitHub Pages or another HTTPS static host.

## Data

All account and payment records remain in this browser profile on this device. Clearing browser site data can erase them. Export backups regularly and store copies safely. Importing a backup replaces the current local data.
