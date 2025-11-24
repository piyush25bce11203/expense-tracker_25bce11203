**Expense Tracker Python project**

This project is a simple expense tracking application created using Python.
The main idea is to help users record their daily expenses, view them later, and analyze spending habits
All the data is stored in a CSV file so the expenses are saved even after closing the program

The program runs in the terminal and provides easy menu where users can add expenses,view them,delete any entry,search by category,sort by amount,generate a monthly report and calculate the daily average.

Libraries Used are:
I have used only built-in Python libraries 
The libraries used are:

• csv – to handle reading and writing of the expenses file
• os – to check if the file exists and manage file operations

Approach of the code:
I divided the project into smaller parts to make it easier to work on.
First I created a function that checks whether the expenses file existsor not
Then I made separate functions for adding expenses , showing them , deleting entries, searching , sorting , and generating reports
Each feature has its own function which makes the code cleaner and easier to understand.

I followed a simple top-down design approach where the main menu calls each function based on the users choice
Every time a new expense is added or deleted, the program writes the updated data back into the CSV file

Instructions are:

To run the project, Python must be installed.
Download the project folder and then open a terminal or command prompt in that folder.
Run the program using the command: python expensestrackerproject.py
The file expenses.csv will be created automatically if it does not already exist.

Key Learnings:

While working on this project
I learned how to use file handling with CSV files,how to break a problem into smaller functions,how to store and process user data and how to create a simple menu-based application.
It helped me understand programming,data processing and basic analysis like monthly totals and averages.



