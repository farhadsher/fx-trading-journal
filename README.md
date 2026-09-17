# FX Trading Journal

A free, private trading journal that helps you see whether your trading actually has an edge — win rate, profit factor, average R multiple, and an equity curve, updated the moment you log a trade.

**[Live tool →](index.html)** (open in any browser, no signup, no server)

Built and maintained by [FXMARE](https://fxmare.com) — forex news, market analysis, and free trading tools. FXMARE also runs a full-featured trading journal (equity curve, P&L calendar, setup/session breakdowns, CSV import) at [fxmare.com/journal](https://fxmare.com/journal) — this repo is a lightweight, offline-first companion for anyone who just wants the core numbers without an account.

## Why this exists

Most traders *feel* like they know if they're profitable. Few can actually show it. Journaling every trade — even just the result and the risk taken — turns "I think I'm doing okay" into a real, provable track record. This tool removes every excuse not to: no signup, no install, and your data never leaves your browser.

## Features

- Log trades with date, pair, direction, risk ($), result ($), and an optional setup/tag
- Auto-calculated stats: total P&L, win rate, profit factor, average win/loss, average R multiple
- Equity curve chart, live-updating as you add trades
- CSV export and import (back up your data, or bring in trades from your broker/spreadsheet)
- Everything is stored in your browser's `localStorage` — nothing is sent to any server

## Usage

This is a single self-contained HTML file — no dependencies, no build tools, no tracking, no backend.

- Open `index.html` directly in a browser, or
- Serve it with any static file host.

Because storage is per-browser, use **Export CSV** regularly if you want a portable backup or plan to switch devices/browsers.

## Formulas

```
Win rate       = winning trades / total trades
Profit factor  = gross profit / gross loss
R multiple     = trade P&L / amount risked on that trade
```

## Disclaimer

This tool is for educational and record-keeping purposes only and does not constitute financial advice. Past results logged here do not guarantee future performance.

## License

MIT — see [LICENSE](LICENSE).
