A simple command-line Expense Tracker built in Python to help you record, categorize, and summarize your monthly expenses.

The app allows you to:

Enter expenses interactively

Categorize them (Food, Home, Work, Fun, Misc)

Save them automatically to a CSV file

Get a summary of total spending, category breakdown, and remaining daily budget for the month

This project demonstrates file handling, data structures, and user interaction in Python — ideal for beginners learning practical programming concepts.

Tech Stack

Python 3

Built-in libraries: datetime, calendar, typing

Features

Add new expenses with name, amount, and category

Save all entries to a local CSV file (expenses.csv)

Display a summary with total spending and budget remaining

Automatically calculate your daily spending limit based on the remaining days of the month

Colored text output for better readability

How to Run

Clone this repository or copy the script files

Make sure you have Python 3 installed

Run the program in your terminal:

python main.py


Follow the on-screen prompts to add and view your expenses

Project Structure
expense-tracker/
│
├── main.py           # Main application logic
├── expense.py        # Expense class (data structure for name, amount, category)
├── expenses.csv      # Saved expense records

Concepts Used

Object-Oriented Programming (Expense class)

File I/O (writing and reading from CSV)

Data aggregation (sum by category)

Basic math and date calculations

Terminal user input and output

Future Improvements

Add monthly report generation

Include data visualization with Matplotlib

Support deleting or editing expenses

Turn it into a web or GUI app using Flask or Tkinter
