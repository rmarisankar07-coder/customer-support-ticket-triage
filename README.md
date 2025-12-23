# Customer Support Ticket Triage System

Week-1 Internship Project

## Description
This project processes customer support tickets, cleans the text, classifies each ticket into an issue type, assigns a priority, and calculates SLA-based due times. It also generates a simple support manager report.

## Dataset
- Kaggle Customer Support Ticket dataset
- Main text column: `Ticket Description`
- Date column: `Date of Purchase`

## Steps Performed
1. Load and explore the dataset (rows, columns, missing values)
2. Clean ticket messages (lowercase, remove special characters, extra spaces)
3. Classify issues into: PAYMENT, LOGIN, DELIVERY, REFUND, BUG, GENERAL
4. Assign rule-based priorities: P0, P1, P2, P3 (`auto_priority`)
5. Map priorities to SLA hours and calculate `due_time`
6. Generate a support manager report (Issue Type vs Priority)
7. Export final outputs as CSV

## Tools Used
- Python
- Google Colab
- Pandas
- NumPy
- GitHub
