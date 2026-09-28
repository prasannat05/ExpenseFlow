# ExpenseFlow — Personal Finance Tracker

ExpenseFlow is a lightweight, browser-based personal finance tracker built as a self-contained HTML application. It helps you manage income, expenses, transfers, savings, wallets, budgets, analytics, and reports without a backend or installation process.

## Features

### Dashboard

- View total balance, available balance, net worth, and savings rate.
- Track separate **Hand Cash**, **Bank Savings**, and **Savings Vault** wallets.
- Compare today’s and this month’s income and expenses.
- Monitor monthly budget usage with progress indicators and warnings.
- See quick statistics such as largest income, largest expense, average spending, and income/expense streaks.
- Review recent transactions and monthly cash flow at a glance.
- Use quick-add buttons for frequently used expenses.

### Transaction Management

- Add, edit, and delete transactions.
- Record expenses, income, wallet transfers, savings deposits, and savings withdrawals.
- Add transaction amounts, dates, notes, merchants, categories, and income sources.
- Choose the wallet affected by each income or expense.
- Search transactions by category, source, merchant, note, or amount.
- Filter by date range, transaction type, wallet, category/source, and amount range.
- Sort history by newest, oldest, highest amount, or lowest amount.
- Paginate transaction history for easier browsing.

### Wallets and Savings

- Manage balances across cash, bank, and a dedicated Savings Vault.
- Transfer money between Hand Cash and Bank Savings.
- Deposit money into or withdraw money from the Savings Vault.
- Choose whether locked Savings Vault funds are included in the displayed total balance.
- Keep Savings Vault funds included in net worth calculations.
- Recalculate wallet balances from the complete transaction history to prevent inconsistencies.

### Budgets

- Set daily, weekly, and monthly overall budgets.
- Set individual budgets for expense categories.
- Set budgets for specific wallets.
- View spending progress, remaining budget, and exceeded-budget warnings.
- Add custom expense categories and income sources.

### Analytics

- Select analytics ranges including this month, the last 7, 30, 90, or 365 days, or all time.
- Visualize expenses by category.
- Visualize income by source.
- Compare wallet balances and activity.
- Compare monthly income and expenses.
- View cash-flow trends, stacked category spending, and savings trends.
- Identify top spending categories and income sources.

### Reports and Data Export

- Generate daily, weekly, monthly, yearly, custom-range, category, wallet, income, expense, savings, and budget reports.
- Print reports directly from the browser.
- Export transaction and report data as CSV.
- Export a complete application backup as JSON.
- Restore data from ExpenseFlow JSON backup files.
- Migrate older backup formats without discarding existing transactions.

### Personalization and Usability

- Switch between dark and light themes.
- Customize the currency symbol.
- Configure starting cash, bank, and savings balances.
- Use responsive layouts on desktop, tablet, and mobile screens.
- Use the floating add button or `Alt+N` keyboard shortcut to add a transaction.
- Receive toast notifications and confirmation dialogs for important actions.
- Use the application offline after loading its local assets, with data stored in browser `localStorage`.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/prasannat05/tracker.git
   ```

2. Open `index.html` in a modern web browser.
3. Add your starting balances and begin recording transactions.

No server, package manager, build step, or database is required.

## Project Structure

- `index.html` — Contains the application interface, styles, charts, storage logic, transaction management, analytics, reports, and settings.

## Data and Privacy

ExpenseFlow stores application data locally in your browser using `localStorage`. No account or backend service is required. Use the built-in JSON backup option regularly if you need to preserve or move your data between browsers or devices.

The analytics charts are powered by [Chart.js](https://www.chartjs.org/) loaded from the jsDelivr CDN.

## Contributing

Contributions and improvements are welcome. Fork the repository, make your changes, and submit a pull request with a clear description of the improvement.

## License

This project is open source and available under the MIT License.
