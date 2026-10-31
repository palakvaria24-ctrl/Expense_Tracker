# Expense Tracker

## About the Project

Expense Tracker is a simple Python desktop application developed using Tkinter. It helps users record and manage their daily expenses, monitor their monthly allowance, and understand their spending habits.

The application provides an easy-to-use graphical user interface (GUI), making expense management simple and convenient.

## Features

- **Add Expenses:** Record expenses by entering the date, amount, and category.
- **Expense Categories:** Organize expenses into Food, Travel, Shopping, Bills, and Others.
- **Daily Expense Report:** View expenses recorded for a particular day.
- **Monthly Summary:** View total expenses and monthly spending details.
- **Allowance Management:** Set and manage a monthly allowance.
- **Spending Advice:** Receive simple suggestions based on spending patterns.
- **Data Storage:** Automatically saves expense and allowance records in CSV files.
- **Data Persistence:** Previously saved records remain available when the application is reopened.

## Technologies Used

- Python 3
- Tkinter – Graphical User Interface
- CSV – Data storage
- DateTime – Date handling
- OS and Path – File management

## Project Structure

```text
Expense_Tracker/
│
├── .gitignore
├── expense_tracker.py
└── README.md
```

The application automatically creates the following files when required:

- `expenses.csv` – Stores expense records.
- `allowance.csv` – Stores monthly allowance records.

## Requirements

- Python 3 installed on your computer.
- Tkinter support (usually included with standard Python installations).

No third-party Python packages are required.

## How to Run the Project

**Step 1:** Download or clone this repository.

**Step 2:** Open the `Expense_Tracker` folder in Visual Studio Code.

**Step 3:** Open the VS Code terminal.

**Step 4:** Check your Python installation:

```bash
python --version
```

**Step 5:** Run the application:

```bash
python expense_tracker.py
```

The Expense Tracker desktop application will open.

*If you use the Python Launcher on Windows, you can also run it with `py -3.14 expense_tracker.py`.*

## How to Use

1. Open the Expense Tracker application.
2. Enter the required details to add an expense.
3. Select an expense category.
4. Set your monthly allowance when prompted.
5. View daily expenses to check your spending.
6. Open the monthly summary to review your expenses and allowance.
7. Close and reopen the application whenever needed. Your saved records will remain available.

## Data Storage and Privacy

Expense and allowance information is stored locally in CSV files inside the project folder.

These files are excluded from GitHub uploads through `.gitignore` to help protect personal financial information.

## Purpose of the Project

The main purpose of this project is to provide a simple and user-friendly way to track personal expenses, manage monthly budgets, and develop better spending habits.

## Author

Developed as a Python programming project.
