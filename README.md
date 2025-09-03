# 🏦 Python Bank Account Management System
# 📌 Project Overview

This project is a Python-based Bank Account Management System that simulates core banking operations such as account creation, deposits, withdrawals, transfers, and transaction history management.

The system is designed with Python fundamentals like variables, functions, data structures, file handling, error handling, and modular programming. It demonstrates how banking operations can be automated in a simple yet effective way.

# 🎯 Objectives

Create and manage bank accounts with auto-generated account numbers

Perform secure deposits, withdrawals, and fund transfers

Maintain transaction history with timestamps

Store and retrieve account details using file handling (pickle)

Provide an interactive menu-driven interface for users

Implement input validation and error handling for reliable operations

# 🛠️ Features

## 1️⃣ Account Management

- Create new accounts with:

- Account holder’s name

- Auto-generated account number

- Account type (savings/current)

- Initial balance

- Retrieve account details (name, account number, account type, balance).

## 2️⃣ Transactions

- Deposit → Add money to an account.

- Withdraw → Deduct money ensuring balance doesn’t go negative.

- Transfer → Move funds between two accounts securely.

## 3️⃣ File Handling

- Store account details and transaction history in files.

- Load account data at program start & save updates at exit.

- Append transactions without overwriting existing records.

## 4️⃣ Reports

- View transaction history (date, type, amount).

**Generate statistics for each account using NumPy**:

- Total deposits

- Total withdrawals

Average transaction amount

## 5️⃣ User Interaction

**Menu-driven interface with options to**:

- Open new account

- View account details

- Deposit / Withdraw / Transfer funds

- View transaction history

- Exit program

## 6️⃣ Error Handling

- Validate positive deposit/withdrawal amounts.

- Prevent overdrafts (withdrawal > balance).

- Handle transfers between non-existent accounts.

## 7️⃣ Bonus (Optional Enhancements)

- Login system with username/password.

- Use lambda functions for quick calculations.

- Extend for multiple user access.

# 🛠️ Tech Stack

- Python 3.x

- pickle → For persistent storage of account & transaction data

- datetime → To timestamp transactions

- NumPy → For summary statistics
