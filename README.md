# Week 1 Exercise - Personal Expense Tracker

## Overview

Congratulations! 🎉

You have completed the first week of the Python for AI Engineering course.

Now it's time to apply everything you've learned by building a simple command-line application called **Personal Expense Tracker**.

This project is designed to help you practice the fundamental Python concepts covered in Week 1.

---

## Learning Objectives

By completing this project, you should be able to:

- Use variables and basic data types
- Store data using Python collections
- Write reusable functions
- Use conditional statements
- Use loops to create interactive programs
- Read and write files
- Use Git to track your development progress

---

## Project Description

Create a command-line application that allows users to manage their daily expenses.

Example menu:

```

========== Personal Expense Tracker ==========

1. Add Expense
2. View Expenses
3. Calculate Total Expense
4. Search Expense
5. Save Expenses
6. Load Expenses
7. Exit

Choose:

```

---

## Requirements

### 1. Add Expense

Allow users to enter:

- Expense category
- Expense amount

The expense category **must be one of the following**:

- Food and Beverage
- Transportation
- Payment and Installation
- Entertainment
- Others

If the user enters an invalid category, the program should display an error message and ask the user to enter a valid category again.

Example:

```
Category : Food and Beverage
Amount   : 50000
```

Example of invalid input:

```
Category : Shopping

Invalid category!

Please choose one of the following categories:
- Food and Beverage
- Transportation
- Payment and Installation
- Entertainment
- Others
```

---

### 2. View Expenses

Display all saved expenses.

Example:

```

No Category Amount

1 Food 50000
2 Transport 20000
3 Shopping 150000

```

---

### 3. Calculate Total Expense

Display:

- Total expense

Example:

```

Total Expense: Rp220000

```

---

### 4. Search Expense

Search expenses by category.

Example:

```

Enter category:

Food

```

Output:

```

Food Rp50000
Food Rp25000

```

---

### 5. Save Expenses

Save all expense data into a file.

You may choose any text-based format, such as:

- TXT
- CSV

---

### 6. Load Expenses

Load previously saved expenses from the file.

---

### 7. Exit

Terminate the application.

---

## Suggested Data Structure

You are free to design your own solution.

One possible structure is:

```python
expenses = [
    {
        "category": "Food",
        "amount": 50000
    },
    {
        "category": "Transport",
        "amount": 20000
    }
]
```

---

## Project Rules

- Only use Python standard libraries.
- Do not use external packages.
- Do not use databases.
- Do not use GUI frameworks.
- Build a command-line (CLI) application.

---

## Concepts You Must Use

Your solution should demonstrate your understanding of the following topics:

- Variables
- Data Types
- List
- Dictionary
- Conditional Statements
- Loops
- Functions
- File Handling

---

## Git Requirements

Use Git throughout your development.

Make **at least five meaningful commits**.

Example commit history:

```

Initialize project
Implement add expense feature
Implement search feature
Implement save & load feature
Complete expense tracker

```

Avoid making only one commit after finishing the entire project.

---

## Bonus Challenges (Optional)

Complete one or more of the following features:

- Edit an expense
- Delete an expense
- Display the average expense
- Display the highest expense
- Display the lowest expense
- Sort expenses by amount
- Sort expenses alphabetically by category
- Validate user input
- Automatically save data before exiting

---

## Submission

1. Push your project to your own GitHub repository.
2. Ensure your repository is public.
3. Submit your GitHub repository link.

Good luck, and have fun building your first Python project! 🚀
