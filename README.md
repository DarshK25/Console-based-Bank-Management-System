# Console-based-Bank-Management-System

## Overview
This Bank Management System is a console-based Java application that simulates essential banking functionalities, allowing users to create and manage bank accounts across different branches. It provides operations for account creation, balance inquiries, deposits, withdrawals, and transaction history, all secured with PIN authentication.

## Features
- **Account Creation**: Supports account creation with branch selection, account holder's details, and an initial deposit.
- **Deposit and Withdrawal**: Allows users to securely deposit and withdraw funds with PIN-based authentication.
- **Balance Inquiry**: Provides balance checks for individual accounts.
- **Transaction History**: Tracks and displays the transaction history for each account.
- **Multi-Branch Management**: Supports multiple branches with unique branch codes for account segmentation.
- **PIN Verification**: Ensures security by requiring a PIN to access account operations.

## Classes and Structure

- **`BankAcc`**: Represents a bank account with fields for account number, holder name, balance, PIN, and transaction history.
- **`BankBranch`**: Represents a bank branch, manages a list of accounts associated with the branch, and allows retrieval of accounts by account number.
- **`BranchManager`**: Manages multiple branches, each identified by a unique branch code, and facilitates the addition of new branches.
- **`BankApp`**: Contains the main method, a text-based user interface for interaction, and helper methods for core banking operations.

## Getting Started

1. Clone or download the repository.
2. Open the project in your preferred Java IDE (e.g., Eclipse, IntelliJ).
3. Run `BankApp` to start the console-based application.

## Usage

- Choose an option from the main menu to perform banking operations:
  - **1. Create Account**: Creates a new account with a branch code and an initial deposit.
  - **2. Deposit**: Adds funds to an existing account.
  - **3. Withdraw**: Withdraws funds from an account.
  - **4. Check Balance**: Shows the balance of an account.
  - **5. Transaction History**: Displays a detailed transaction history.
  - **6. Exit**: Closes the application.

## Example
To create an account:
1. Choose option 1 from the main menu.
2. Enter the branch code and account holder's name.
3. Provide an initial deposit and a 4-digit PIN.
4. Your account is created, and your account number is displayed.

## Technologies Used
- **Language**: Java
- **Tools**: Scanner for input handling, ArrayList, HashMap

---

### Author
Developed by [Darsh Kalathiya]
