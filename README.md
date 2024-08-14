# Finance Tracker CLI

This is a simple finance tracking project that allows users to record and view financial transactions. The project stores data in a CSV file and provides functionalities to add new transactions and view transaction history within a specific date range.

## Features

- Add new transactions (income or expenses) with date, amount, category, and description.
- View transactions filtered by date range.
- Display a summary of income, expenses, and net savings.
- Generate daily transaction charts for income and expenses.

## Requirements

- Python 3.x
- Python Libraries:
  - `pandas`
  - `matplotlib`

You can install the necessary dependencies using pip:

```bash
pip install pandas matplotlib
```

## Project Structure

- **main.py**: Main file containing functions to add transactions, view transactions, and generate charts.
- **data_entry.py**: File containing helper functions to collect data from the user.
- **finance_data.csv**: CSV file storing the financial transactions.

## How to Use
1. Clone the repository to your local environment:
```commandline
git clone https://github.com/your-username/finance-tracker.git
cd finance-tracker
```
2. Ensure all dependencies are installed:
```commandline
pip install -r requirements.txt
```

3. Run the main.py file to start the program:
```commandline
python main.py
```
4. Follow the menu instructions to add transactions or view transaction history.


## CSV Format
Transactions are stored in the finance_data.csv file in the following format:
```commandline
date,amount,category,description
01-08-2023,1500.00,Income,Salary payment
02-08-2023,200.00,Expense,Monthly rent
...
```

- **date**: Transaction date in DD-MM-YYYY format.
- **amount**: Transaction amount.
- **category**: Transaction category (Income for income, Expense for expenses).
- **description**: Optional transaction description.

## Usage Example
When running the program, you will see a menu with the following options:

1. Add a new transaction
2. View transactions within a specific date range
3. Exit

You can add transactions and view them as needed. 
Additionally, the program allows generating charts of daily transactions.