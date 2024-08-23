# Expense Tracker and Budget Planner

## Overview

This Expense Tracker and Budget Planner is a simple, user-friendly Python application built with Tkinter. It helps users manage their monthly expenses, set budgets, and keep track of their spending across various categories.

## Features

- Set a monthly budget at startup
- Add expenses with date, category, and amount
- View expenses in a scrollable list
- See total expenses and remaining budget in real-time
- Manage expense categories (add new categories)
- Save monthly expense data to a JSON file

## Requirements

- Python 3.6 or higher
- Tkinter (usually comes pre-installed with Python)

## Installation

1. Clone this repository or download the source code.
2. Ensure you have Python installed on your system.
3. No additional libraries are required as the application uses only built-in Python modules.

## Usage

1. Run the script:
   ```
   python expense_tracker.py
   ```
2. When prompted, enter your monthly budget.
3. Use the interface to add expenses, manage categories, and view your spending.
4. Click the "Save Data" button to save your monthly expense data to a JSON file.

## How to Use

1. **Adding an Expense**:
   - Enter the date (YYYY-MM-DD format), select or type a category, and enter the amount.
   - Click "Add Expense" to record it.

2. **Adding a New Category**:
   - Type the new category name in the "Manage Categories" section.
   - Click "Add Category" to add it to the list of available categories.

3. **Viewing Expenses and Budget**:
   - The right panel shows all recorded expenses, total spent, and remaining budget.

4. **Saving Data**:
   - Click "Save Data" to save your current month's data to a JSON file.
   - Choose a location and filename in the file dialog that appears.

## Future Enhancements

- Load previously saved data
- Generate expense reports and charts
- Set category-specific budget limits
- Multi-month view and comparison

## Contributing

Contributions to improve the Expense Tracker are welcome. Please feel free to fork the repository, make changes, and submit pull requests.

## License

This project is open source and available under the [MIT License](LICENSE).
