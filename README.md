# Altschool-exam-project
## Introduction

The objective of this project is to apply the principles of object-oriented programming (OOP) in Python to create the Expense and ExpenseDatabase classes for modeling and overseeing financial expenses.

This Python project offers users a straightforward way to oversee and monitor individual financial expenses. It comprises two primary classes: Expense, designed to represent a single expense, and ExpenseDB, intended for the management of a collection of expenses.

### Expense Class:
The Expense class represents a single expense and has the following characteristics:

- id: A unique identifier generated as a special string.
- title: A word or phrase describing the expense.
- amount: A number indicating the cost of the expense.
- created_at: A time stamp showing when the expense was created (in Coordinated Universal Time - UTC).
- updated_at: A time stamp indicating the last time the expense was changed (in UTC).

Additionally, the Expense class provides the following actions:

- init: Sets up the details of the expense.
- update: Allows changing the title and/or amount, and automatically updates the last modification time.
- to_dict: Creates a dictionary with the details of the expense.

### ExpenseDB Class:
The ExpenseDB class organizes a group of Expense objects and acts as a central place for expense-related tasks. Its main features include:

- init: Starts the list of expenses.
- add_expense: Adds an expense to the group.
- remove_expense: Deletes an expense from the group based on its ID.
- get_expense_by_id: Retrieves an expense from the group based on its ID.
- get_expenses_by_title: Gathers a list of expenses from the group based on their titles.
- to_dict: Generates a list of dictionaries representing all expenses in the group.

## How to clone
I cloned the repository by first opening the command prompt. Then, I navigated to the desired folder where I wanted to clone the repository using the 'cd' command:

cd C:\Users\S3 Audio Visual\OneDrive\Documents\Alt Exam Project\Altschool-exam-project
After that, I used the 'git clone' command along with the HTTPS URL of the repository:

git clone https://github.com/example/repository.git
This successfully cloned the repository to my local machine.

## How to run the code
