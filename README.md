Expense Tracker Python Project

This project is a simple console-based Expense Tracker built using Python. It helps a user record daily expenses, view them, delete entries, search by category, sort them by amount, and also see monthly totals and daily average spending. All the data is saved in a CSV file so the information stays safe even after the program is closed.

Purpose of the Project
The main idea behind this project is to make it easier to keep track of day-to-day spending. Many people struggle to remember where their money goes, so this program gives a simple and organized way to store expense details like date, amount, category, and notes.

How the Program Works
When the program starts, it checks whether the expenses file exists. If not, it creates one automatically.
The user gets a menu where they can choose different options like adding an expense or viewing all expenses.
Every operation reads or writes data to the CSV file so nothing is lost.

Features Included
Adding a new expense entry
Viewing all saved expenses
Deleting any entry by choosing its number
Searching records based on category
Sorting expenses by amount
Getting a monthly report for a chosen month
Finding the daily average spending

Libraries and Concepts Used
The csv library is used to read and write the expenses into the CSV file.
The os library is used to check whether the data file exists.
The datetime library is used for handling dates.
Basic Python concepts like functions, loops, conditional statements, lists, and modular programming have been applied.

Why This Project Is Useful
It gives a simple way to organize daily spending without needing any advanced tools.
It also teaches how to use file handling in Python and how to break a program into small, manageable functions.

How to Run
Make sure Python is installed on your system.
Run the Python script named expenses.py.
The menu will appear and you can choose any option by entering the number.

Future Enhancements
The program can be improved later by adding a graphical interface, exporting reports in PDF or Excel, and showing charts for better analysis.
