# Daily-Expense-Tracker
💰 Daily Expense Tracker
A simple Python-based command-line application that helps you track daily expenses, calculate statistics, and monitor your spending habits using NumPy.

FEATURES

Input daily expenses interactively for any number of days
Calculate total expenses
Calculate average daily expense
Identify the day with the highest spending
Built-in budget warning system (alerts when average exceeds ₹1000/day)


TECH STACK
Language: Python 3
Library: NumPy

INSTALLATION

Clone the repository
git clone https://github.com/your-username/daily-expense-tracker.git
cd daily-expense-tracker
Install dependencies
pip install numpy


USAGE
Run the notebook in Google Colab or Jupyter Notebook:
jupyter notebook project3.ipynb
Or run as a plain Python script:
python expense_tracker.py
Example Interaction:
Enter number of days: 5
Enter the daily expenses(in Rupee): 500
Enter the daily expenses(in Rupee): 600
Enter the daily expenses(in Rupee): 200
Enter the daily expenses(in Rupee): 320
Enter the daily expenses(in Rupee): 50
Total expense is given as: 1670 Rupee
Average expense is given as: 334.0 Rupee
Highest expense was on day 2
Average expense is within the limit.

PROJECT STRUCTURE
daily-expense-tracker/
├── project3.ipynb   -> Main Jupyter Notebook
└── README.md        -> Project documentation

HOW IT WORKS
Daily_expense(days)   -> Collects daily expense inputs and returns a NumPy array
Expenses_stats(arr)   -> Computes total, average, and highest-expense day
display(...)          -> Prints the results and triggers a warning if average > ₹1000

CUSTOMIZATION
You can change the daily spending limit by modifying the limit variable inside the display() function:
limit = 1000  # Change this value to your preferred daily budget (in Rupees)

Author

Created by Abhishek Suman

License

This project is open-source and free to use for learning purposes.
