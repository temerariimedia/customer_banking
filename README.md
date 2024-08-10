# Customer Banking System

## Overview

The Customer Banking System is a Python-based application designed to help users calculate and track interest earned on their savings and Certificate of Deposit (CD) accounts. Users can enter account details, calculate the interest earned over a specified period, and view the updated balances.

## Features

- **User Input:** Prompts users to input initial balances, interest rates, and the duration (in months) for both savings and CD accounts.
- **Interest Calculation:** Automatically calculates the interest earned on both savings and CD accounts, based on the user's input.
- **Balance Updates:** Updates account balances by adding the calculated interest and provides the updated balances.
- **Formatted Output:** Displays the interest earned and updated balances, formatted to two decimal places.

## File Structure

- **Accounts.py:** Contains the `Account` class, which provides methods to set and retrieve the account balance and interest.
- **savings_account.py:** Implements the `create_savings_account` function, which handles the creation of savings accounts, interest calculation, and balance updates.
- **cd_account.py:** Implements the `create_cd_account` function, which handles the creation of CD accounts, interest calculation, and balance updates.
- **customer_banking.py:** The main entry point for the application. It prompts the user for input, processes the savings and CD accounts, and displays the results.

## How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/customer-banking-system.git
   cd customer-banking-system

2. **Run the Application:**
python customer_banking.py

**Example Output:**
Enter the savings account balance: 1000
Enter the annual interest rate (APR) for the savings account: 5
Enter the number of months for the savings account: 12
Savings Account - Interest Earned: $50.00, Updated Balance: $1050.00

Enter the CD account balance: 2000
Enter the annual interest rate (APR) for the CD account: 3
Enter the number of months for the CD account: 6
CD Account - Interest Earned: $30.00, Updated Balance: $2030.00
