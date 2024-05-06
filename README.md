# customer_banking
Module 3 Challenge: Customer Banking

This repository contains Python files implementing a basic banking system with classes for managing accounts and functions for creating CD (Certificate of Deposit) and savings accounts.

## File Structure

1. `Account.py`: Defines the `Account` class for managing account balance and interest.
2. `cd_account.py`: Imports the `Account` class and provides a function to create a CD account with interest calculation.
3. `savings_account.py`: Imports the `Account` class and provides a function to create a savings account with interest calculation.
4. `customer_banking.py`: Imports functions from `cd_account.py` and `savings_account.py` to prompt users for account details and calculate interest earned.

## Usage

To use the banking system, follow these steps:

1. **Set Up Accounts**: Ensure all Python files are in the same directory.
2. **Run `customer_banking.py`**: Execute this file to interact with the banking system.
3. **Follow Prompts**: Enter the required details such as account balances, interest rates, and maturity periods as prompted.
4. **View Results**: The program will display the interest earned and updated account balances for both savings and CD accounts.

## Functionality

- **Account Class**: The `Account` class in `Account.py` manages account balances and interest.
- **CD Account Creation**: `create_cd_account()` in `cd_account.py` creates a CD account with interest calculation based on balance, interest rate, and maturity period.
- **Savings Account Creation**: `create_savings_account()` in `savings_account.py` creates a savings account with interest calculation based on balance, interest rate, and duration.
- **Main Functionality**: `customer_banking.py` contains the main function that prompts users for account details, calculates interest, and displays results.

## Notes

- Ensure Python 3.x is installed on your system.
- Input amounts should be in decimal format (e.g., 1000.00).
- Interest rates should be provided as percentages (e.g., 5 for 5%).
- Maturity periods are expected in months.

