# 🌙 月亮灯记账 · Moonlamp Accounting

> 专为留学生设计的双币种记账工具 — 人民币和美元独立并存，互不干扰。
>
> *A dual-currency personal finance tracker built for international students — CNY and USD coexist independently, never mixed.*

**[→ 打开网页版 · Open App](https://ludanyuan.github.io/xiaoshu-accounting/)**

---

## 为什么需要它 · Why This Exists

留学生的账本天然是双轨的：国内转来的生活费、回国消费是人民币；这边的学费、房租、日常开销、兼职收入是美元。大多数记账软件只能设一个主货币，混在一起既不直观也容易出错。

*International students live on two financial tracks at once: RMB wired from home, spending during visits back; USD for tuition, rent, daily life, and part-time work. Most budgeting apps force a single base currency, making cross-currency tracking clunky and error-prone.*

**月亮灯记账的解法：每一笔记录都独立携带自己的货币。所有分析视图自动按 ¥ / $ 分开展示，不换算、不合并、不折算汇率。**

*The fix: every transaction carries its own currency. All dashboards automatically split ¥ and $ — no conversion, no merging, no exchange rate guessing.*

---

## 功能一览 · Features

| 模块 · Tab | 说明 · Description |
|---|---|
| 📒 收支记录 | 每笔支出/收入独立选 ¥ 或 $ · Each transaction independently tagged CNY or USD |
| 📅 本月分析 | 日历热图 + 饼图，双币种各自统计 · Monthly heatmap + pie charts, split by currency |
| 📊 年度分析 | 年度汇总、环形图、柱状图，¥ 和 $ 并排 · Annual charts with ¥ / $ side by side |
| 🏦 资产盘点 | 流动/投资/固定资产/负债，每行独立选币种 · Balance sheet with per-row currency |
| 💰 预算管理 | 每个子分类设 ¥ 和 $ 双预算 · Paired ¥ / $ budget per sub-category |
| ⚙️ 自定义分类 | 分类、账户、成员、标签全部自定义 · Fully customisable categories, accounts, members, tags |

---

## 技术特点 · Technical

- **零依赖 · Zero dependencies** — 单个 HTML 文件，CSS 和 JS 全部内联 · Single HTML file, all CSS and JS inline
- **数据本地 · Privacy-first** — 全部存在浏览器 `localStorage`，不上传不注册 · All data stays in your browser's `localStorage`, nothing is sent anywhere
- **即开即用 · No install** — 下载后双击打开，或直接访问网页版 · Download and open, or use the hosted version
- **JSON 备份 · Backup** — 内置导出 / 导入 · Built-in export / import

---

## 快速开始 · Getting Started

1. 访问 **[网页版 · Hosted version](https://ludanyuan.github.io/xiaoshu-accounting/)** 直接使用
2. 或下载 `index.html`，在任意现代浏览器中双击打开 · Or download `index.html` and open it in any modern browser

数据自动保存。点击 ⬇ 导出可下载 `.json` 快照。
*Data saves automatically. Use the ⬇ Export button to download a `.json` snapshot.*

---

## Changelog

### v1.1.0 — 2026-06-20
- 资产盘点样式优化：类别可命名，输入框 ghost 样式，¥/$ 汇总分两行
- 删除键统一为空心图标 🗑️
- *Assets tab: editable category labels, ghost-style inputs, ¥/$ totals on separate rows, outline delete buttons*

### v1.0.0 — 2026-06-20
- 初始发布：6 大模块，全双币种支持，SVG 图表（无外部库）
- *Initial release: 6 tabs, full dual-currency support, SVG charts with no external libraries*
