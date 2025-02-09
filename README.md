# Personal Finance Tracker

## Overview
The Personal Finance Tracker is a Python-based application that helps users manage their finances by tracking income and expenses. It stores transactions in an SQLite database and provides monthly summaries.

## Features
- **Add Transactions**: Users can log income and expenses with categories.
- **View Transactions**: Displays all recorded transactions.
- **Monthly Summary**: Aggregates income and expenses per month.
- **SQLite Database**: Stores all financial data securely.
- **User-friendly Console Interface**: Simple menu-driven interaction.

## Installation
1. Ensure you have Python installed on your system.
2. Install SQLite (optional, as Python comes with SQLite support by default).
3. Download the script and save it as `finance_tracker.py`.
4. Run the script using:
   ```sh
   python finance_tracker.py
   ```

## Usage
1. Choose an option from the main menu:
   - `1` to Add Income
   - `2` to Add Expense
   - `3` to View Transactions
   - `4` to View Monthly Summary
   - `5` to Exit the application
2. Follow the prompts to enter transaction details.
3. View your transaction history and summary as needed.

## Database Structure
The application uses an SQLite database (`finance_tracker.db`) with a table named `transactions` having the following fields:
- `id` (INTEGER, Primary Key)
- `date` (TEXT, Transaction Date)
- `type` (TEXT, "Income" or "Expense")
- `category` (TEXT, Category of transaction)
- `amount` (REAL, Transaction amount)

## Future Enhancements
- Implement a graphical user interface (GUI) using Tkinter.
- Add filtering and searching for transactions.
- Export reports as CSV or PDF files.


