# Bookkeeper

A self-contained bookkeeping app built for locally owned bakeries. Single HTML file, no server needed — just open `index.html` in any browser.

## Features

- **Ledger** — Track income and expenses with bakery-specific categories, search, filter, and CSV export
- **Daily Sales** — Log register totals, card/cash/online/catering breakdowns
- **Recurring** — Set up monthly rent, utilities, subscriptions with auto-generation
- **Invoices** — Track wholesale/catering invoices with paid/pending/overdue status
- **Inventory Tracker** — Monitor ingredient stock levels with low-stock alerts
- **Recipe Costing** — Calculate batch cost, cost per unit, and profit margins for each recipe
- **Staff Hours** — Log employee hours with overtime tracking and weekly/monthly labor cost estimates
- **Waste Log** — Track unsold product and spoilage with day-of-week pattern insights
- **Client Directory** — Wholesale and catering contacts with order preferences, linked to invoice revenue
- **Mileage** — IRS standard mileage rate deduction tracking ($0.70/mi for 2026)
- **Reports** — 6-month income vs. expense chart, P&L statement, profit margins by revenue stream, expense breakdown
- **Tax Prep** — Year-end summary of gross income, deductible expenses by category, and mileage deduction
- **Data Backup/Restore** — Export and import all data as a JSON file

## How to Use

1. Open `index.html` in your browser
2. All data is saved in your browser's localStorage
3. Use the backup button (💾) to save your data as a JSON file
4. Use the restore button (📂) to load a backup

## Tech

- Single self-contained HTML file (no dependencies, no build step)
- Dark mode support (follows system preference)
- Mobile-responsive layout
- Google Fonts: DM Sans + JetBrains Mono
