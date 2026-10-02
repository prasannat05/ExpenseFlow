# ExpenseFlow

A lightweight, browser-based personal finance tracker built as a self-contained HTML application. Manage your income, expenses, transfers, savings, wallets, budgets, analytics, and reports without any server or installation.

## Overview

ExpenseFlow is designed primarily for personal use but can be customized by anyone. It comes with a comprehensive set of predefined income and expense categories suitable for most users. If you need different categories, you can easily add custom ones. All your data is stored locally in your browser and can be backed up as JSON files, making it easy to switch devices or devices, or restore your data anytime.

## Key Features

### Dashboard & Overview
- Monitor total balance, available balance, and net worth at a glance
- Track three separate wallets: Hand Cash, Bank Savings, and Savings Vault
- Compare today's and this month's income vs expenses
- View monthly budget progress with visual indicators
- Quick statistics including largest income, largest expense, average spending, and streaks
- Recent transactions and monthly cash flow summary

### Transaction Management
- Add, edit, and delete transactions with full details (amount, date, note, merchant, category)
- Support for expenses, income, wallet transfers, savings deposits, and withdrawals
- Assign transactions to specific wallets
- Search transactions by category, source, merchant, note, or amount
- Filter by date range, transaction type, wallet, category, and amount
- Sort by newest, oldest, highest, or lowest amount
- Paginated transaction history for easy browsing

### Wallets & Savings
- Manage multiple wallet types with individual balances
- Transfer money between Hand Cash and Bank Savings
- Deposit and withdraw from Savings Vault with lock options
- Choose whether locked savings are included in displayed balance
- Recalculate balances from full transaction history to maintain consistency

### Custom Categories & Customization
- Create custom income sources and expense categories tailored to your needs
- Set daily, weekly, and monthly overall budgets
- Create individual budgets for specific expense categories
- Set budget limits per wallet
- Track budget spending with visual progress and warnings

### Analytics & Reporting
- Select time ranges (this month, last 7/30/90/365 days, all time)
- Visualize expenses by category and income by source
- Compare wallet balances and activity
- Analyze monthly trends and cash-flow patterns
- Identify top spending categories and income sources
- Generate detailed reports (daily, weekly, monthly, yearly, custom range)
- Export reports as printable PDFs

### Data Backup & Export
- Export transactions and reports as CSV
- Complete application backup as JSON
- Restore from backup files anytime
- Migrate data from older backup formats
- Full control over your data

### Personalization
- Dark and light theme toggle
- Customize currency symbol
- Configure starting balances
- Responsive design for desktop, tablet, and mobile
- Keyboard shortcut (Alt+N) for quick transaction entry
- Toast notifications and confirmation dialogs
- Works offline after initial load

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/prasannat05/ExpenseFlow.git
   ```

2. Open `index.html` in a modern web browser.

3. Configure your starting balances and add custom categories if needed.

4. Start tracking your transactions.

No server, package manager, build tools, or database required. Everything runs directly in your browser.

## Project Structure

- `index.html` — Complete, self-contained application with interface, styles, charts, storage, transaction management, analytics, reports, and settings.

## Data & Privacy

All data is stored locally in your browser using `localStorage`. No account creation, backend service, or internet connection required. Use the built-in JSON backup feature to export your data for safekeeping or migration between devices.

Charts are powered by [Chart.js](https://www.chartjs.org/) via jsDelivr CDN.

## Contributing

Contributions are welcome. Fork the repository, make your changes, and submit a pull request with a description of your improvements.

## License

This project is open source and available under the MIT License.
