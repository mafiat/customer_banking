# Customer Banking System

## Description
This project is a customer banking system that allows users to calculate and track interest earned on savings and CD (Certificate of Deposit) accounts. Users can enter their account information, see the interest earned, and view the updated balances after a specified number of months.

## File Descriptions

The project consists of the following files:
- `Accounts.py`: Contains the `Account` class with methods to set the balance and interest.
- `savings_account.py`: Contains the `create_savings_account` function to manage savings accounts.
- `cd_account.py`: Contains the `create_cd_account` function to manage CD accounts.
- `customer_banking.py`: The main script that interacts with the user and displays results.


## How to Use

### Launch the Script 

### Follow the prompts to enter your savings and CD account details:

1. Enter the savings account balance.
2. Enter the savings account interest rate.
3. Enter the number of months for the savings account.
4. Enter the CD account balance.
5. Enter the CD account interest rate.
6. Enter the number of months for the CD account.

### View the results:
The script will display the interest earned and updated balances for both the savings and CD accounts.

## Functions

### Create Savings Account
```bash
create_savings_account(balance, interest_rate, months)
```
#### Description: 
Creates a savings account instance, calculates the interest earned, updates the account balance, and returns the updated balance and interest earned.

#### Parameters:

```balance```: Initial balance of the savings account.

```interest_rate```: Interest rate of the savings account.

```months```: Number of months to calculate interest for.

#### Returns: 
Updated balance and interest earned.

### Create CD Account
```bash
create_cd_account(balance, interest_rate, months)
```
#### Description: 
Creates a CD account instance, calculates the interest earned, updates the account balance, and returns the updated balance and interest earned.

#### Parameters:

```balance```: Initial balance of the CD account.

```interest_rate```: Interest rate of the CD account.

```months```: Number of months to calculate interest for.

#### Returns: 
Updated balance and interest earned.

### Main

```bash
main()
```
#### Description: 
Prompts the user to enter account details, calls the appropriate functions to calculate interest and update balances, and displays the results.


## Features

1. Account Management

    - **Account Class**: The `Account` class provides methods to set and update the balance and interest for both savings and CD accounts.

2. Savings Account Functionality
    - **Create Savings Account**: The `create_savings_account` function allows users to create a savings account instance, calculate the interest earned based on user input, update the account balance with the earned interest, and return the updated balance and interest earned.

3. CD Account Functionality
    - **Create CD Account**: The `create_cd_account` function allows users to create a CD account instance, calculate the interest earned based on user input, update the account balance with the earned interest, and return the updated balance and interest earned.

4. User Interaction
    - **Main Function**: The `main` function prompts the user to enter their savings and CD account details, calls the corresponding functions to calculate the interest earned and update the balances, and displays the results.

5. Interest Calculation
    - **Interest Calculation**: Both the savings and CD account functions calculate the interest earned over a specified number of months, allowing users to see how their investments grow over time.

6. Updated Balances
    - **Balance Updates**: The program updates the account balances with the interest earned, providing users with the most current account information.

7. User Prompts
    - **Interactive Prompts**: The program includes user prompts to gather necessary information such as account balances, interest rates, and the number of months for interest calculation.


## Requirements

- Python 3.x

## Running the Script

To run the script, simply execute it in a Python environment:

```bash
python customer_banking.py
```