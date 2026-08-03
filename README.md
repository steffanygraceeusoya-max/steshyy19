Iloilo Expense Screening System

A simple Java program that demonstrates core programming fundamentals through a real-world budgeting scenario in Iloilo.

## **📌 Overview**

This project is a lightweight diagnostic application designed to validate foundational Java skills before advancing into more complex data structures.

It processes a list of expenses and filters them based on a defined budget limit, providing a clear breakdown of approved and rejected values.

## **⚙️ Features**
📊 Stores expense data using arrays
🔁 Iterates through data using loops
⚖️ Filters values using conditional statements
🧩 Uses modular programming (separate methods)
📋 Displays:
Approved expenses
Rejected expenses
Total approved amount

##  **Program Structure**
IloiloExpenseSystem.java
│
├── main(String[] args)
│   ├── Initializes data
│   ├── Calls processing method
│   └── Displays results
│
└── calculateApprovedTotal(double[] data, double maxLimit)
    ├── Loops through array
    ├── Applies condition (<= limit)
    ├── Prints results
    └── Returns total
    
##  **How to Run**
Open OnlineGDB Java Compiler
Paste the code into the editor
Click Run
View output in the console

## **🖥️ Sample Output**
=================================
   ILOILO EXPENSE SCREENING
=================================
Budget Limit: 250.0

Approved Expenses:
- 150.0
- 200.0
- 95.0

Rejected Expenses:
- 320.5
- 410.0

---------------------------------
Total Approved Expenses: 445.0
=================================
