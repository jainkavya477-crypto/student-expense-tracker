Studentt Expense Tracker

A simple Python console application designed to help users track their daily expenses and manage their monthly budget effectively.

Overview

The Smart Expense Tracker is a beginner-friendly Python program that allows users to record expenses along with notes, automatically timestamps each entry, and stores the data in a text file for future use. The application provides a clear summary of total spending and remaining budget, making it easier for users to monitor their financial habits.

Features

Add expenses with amount and descriptive notes

Automatically records date and time of each entry

Saves all expenses in a persistent text file (expenses.txt)

Displays total spending and remaining budget

Provides suggestions based on spending patterns

Simple, menu-driven interface suitable for beginners

Technologies Used

Python 3

datetime module

File handling (read and write operations)

Installation and Setup

Ensure that Python 3 is installed on your system.

Download or clone this repository:

git clone https://github.com/your-username/smart-expense-tracker.git


Make sure the script file (expense_tracker.py) is located in the folder where you want expenses.txt to be generated.

The program will automatically create expenses.txt if it does not exist.

How to Run

Use the terminal or command prompt to execute the program:

python expense_tracker.py

Testing Instructions

To test the project, you may follow these steps:

Start the program and enter a sample monthly budget such as 90000.

Choose the option to add expenses and input sample values (for example, 100, 2000, 3000).

Add a short note for each expense.

Select the summary option to view:

Total expenses

Remaining budget

Suggestions based on your spending

Flowchart
               ┌────────────────────────┐
               │      Start Program     │
               └────────────┬───────────┘
                            │
                            ▼
               ┌────────────────────────┐
               │ Ask user for monthly   │
               │        budget          │
               └────────────┬───────────┘
                            │
                            ▼
               ┌────────────────────────┐
               │   Display Main Menu:   │
               │ 1. Add Expense         │
               │ 2. View Summary        │
               │ 3. Exit                │
               └────────────┬───────────┘
                            │
                  ┌─────────┼─────────┐
                  │         │         │
                  ▼         ▼         ▼
     ┌────────────────┐   ┌──────────────────┐   ┌────────────────────┐
     │ 1. Add Expense │   │ 2. View Summary  │   │ 3. Exit Program    │
     └───────┬────────┘   └──────────┬──────┘   └──────────┬─────────┘
             │                       │                     │
             ▼                       ▼                     ▼
┌──────────────────────┐   ┌───────────────────────┐   ┌────────────────────────┐
│ Ask amount spent     │   │ Read all expenses      │   │ Display exit message   │
│ Ask note             │   │ from expenses.txt       │   └────────────────────────┘
│ Get current time     │   └──────────┬─────────────┘
└──────────┬───────────┘              │
           │                           ▼
           ▼               ┌──────────────────────────┐
┌──────────────────────┐   │ Calculate total expenses │
│ Write expense data    │   │ Calculate remaining     │
│ into expenses.txt     │   │ budget                  │
└──────────┬───────────┘   └──────────┬──────────────┘
           │                           │
           ▼                           ▼
┌────────────────────────┐ ┌──────────────────────────────┐
│ Print success message  │ │ Show suggestions              │
└──────────┬────────────┘ └──────────┬─────────────────────┘
           │                           │
           ▼                           ▼
   ┌────────────────┐        ┌───────────────────┐
   │ Return to Menu │◄───────│ Return to Menu    │
   └────────────────┘        └───────────────────┘

Author

Kavya Jain
