# Week 1 Exercise - Expense Tracker

## Overview

Congratulations! 🎉

You have completed the first week of the Python for AI Engineering course.

In this exercise, you will build a simple **Expense Tracker** step by step.

Each task builds upon the previous one, so **do not create separate programs**. Continue developing your solution in `main.py`.

---

## Learning Objectives

This exercise covers:

- Variables
- Data Types
- Collections (List & Dictionary)
- Conditional Statements
- Loops
- Functions
- File Handling
- Git

---

# Task 1 — Expense Category Validation

Create a list containing the following valid expense categories.

- Food and Beverage
- Transportation
- Payment and Installation
- Entertainment
- Others

Ask the user to enter an expense category.

If the category is invalid, display:

```

Invalid category!

```

Otherwise display:

```

Category accepted.

```

---

# Task 2 — Record Expenses

Ask the user to input **5 expenses**.

Each expense consists of:

- Category
- Amount

Store all expenses inside a list.

Example:

```python
expenses = [
    {
        "category": "Food and Beverage",
        "amount": 50000
    }
]
```

---

# Task 3 — Display Expenses

Display all recorded expenses.

Example

```

No Category Amount

1 Food and Beverage 50000
2 Transportation 20000

```

---

# Task 4 — Calculate Total Expense

Display the total expense.

Example

```

Total Expense: Rp70000

```

---

# Task 5 — Find the Highest Expense

Display the expense with the highest amount.

Example

```

Highest Expense

Category : Entertainment
Amount : Rp250000

```

---

# Task 6 — Search Expenses

Ask the user to enter a category.

Display all expenses with that category.

If none are found, display

```

Expense not found.

```

---

# Task 7 — Refactor Using Functions

Refactor your program.

Your program should contain at least these functions.

```python
add_expense()
show_expenses()
calculate_total()
highest_expense()
search_expense()
```

---

# Task 8 — Save Expenses

Save all expense data into

```
data/expenses.txt
```

You may choose any text format.

---

## Git Requirements

Use Git during development.

Make at least **5 meaningful commits**.

Example

```

Initialize project
Complete Task 1
Complete Task 2-4
Complete Task 5-7
Complete Task 8

```

---

## Bonus

If you finish early, implement one or more of the following:

- Load expenses from file
- Delete an expense
- Display average expense
- Sort expenses by amount
- Validate that the amount is greater than zero

---

## Submission

Push your project to your own GitHub repository and submit the repository URL.
