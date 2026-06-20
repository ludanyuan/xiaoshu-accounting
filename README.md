# 🌙 月亮灯记账

A single-file personal accounting app — all CSS and JavaScript are inline, no external dependencies.  
Data lives entirely in your browser's `localStorage`; nothing is sent anywhere.

**[Open the app](https://ludanyuan.github.io/xiaoshu-accounting/)**

## Features

| Tab | What it does |
|-----|-------------|
| 📒 收支记录 | Add / edit / delete transactions with type, category, sub-category, account, member, tag |
| 📅 本月分析 | Monthly calendar heatmap + income/expense pie charts |
| 📊 年度分析 | Annual totals, donut charts, grouped bar chart by month |
| 🏦 资产盘点 | Balance sheet: current assets, investments, fixed assets, liabilities, net worth |
| 💰 预算管理 | Set period budgets per sub-category with progress bars |
| ⚙️ 自定义分类 | Fully customisable income / expense / transfer categories, accounts, members, tags |

- **CNY / USD** currency toggle in the header
- Export / import data as JSON for manual backup

## Usage

Open `index.html` directly in any modern browser — no server required.  
All changes auto-save to `localStorage`.

**Backup tip:** use the ⬇ Export button to download a `.json` snapshot.
