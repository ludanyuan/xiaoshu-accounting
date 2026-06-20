# 🌙 月亮灯记账

A single-file personal accounting app — all CSS and JavaScript are inline, no external dependencies.  
Data lives entirely in your browser's `localStorage`; nothing is sent anywhere.

**[Open the app](https://ludanyuan.github.io/xiaoshu-accounting/)**

## Features

| Tab | What it does |
|-----|-------------|
| 📒 收支记录 | Add / edit / delete transactions; each entry carries its own CNY or USD currency |
| 📅 本月分析 | Monthly calendar heatmap + income/expense pie charts, split by ¥ / $ |
| 📊 年度分析 | Annual totals, donut charts, grouped bar chart — ¥ and $ shown separately |
| 🏦 资产盘点 | Balance sheet per currency: current assets, investments, fixed assets, liabilities, net worth |
| 💰 预算管理 | Per sub-category budgets with paired ¥ / $ rows and progress bars |
| ⚙️ 自定义分类 | Fully customisable income / expense / transfer categories, accounts, members, tags |

- **Per-transaction CNY / USD** — each entry carries its own currency; all views split ¥ and $ automatically
- **「↩ 本月」/「↩ 本年」** quick-jump buttons when browsing historical data
- Export / import data as JSON for manual backup

## Usage

Open `index.html` directly in any modern browser — no server required.  
All changes auto-save to `localStorage`.

**Backup tip:** use the ⬇ Export button to download a `.json` snapshot.

## Changelog

### v1.0 — 2026-06-20

- Initial release
- 6 tabs: ledger, monthly analysis, annual analysis, assets, budget, category config
- Dual-currency (CNY / USD) support throughout — per transaction, per asset row, per budget line
- SVG charts (donut pie + grouped bar) with no external libraries
- Budget redesigned as paired ¥/$ rows per sub-category
- Fixed timezone bug in date filtering (`getFullYear` → string slice)
- Monthly/annual views always open on current period; 「↩ 本月」/「↩ 本年」 buttons for history navigation
- 🌙 emoji favicon
