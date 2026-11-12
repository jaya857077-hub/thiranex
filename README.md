# Bank Management Application (C++)

A console-based banking simulation developed in C++ using Object-Oriented Programming (OOP) principles and binary file handling.

## Features
- **Account Creation:** Register new customers with an account number, name, 4-digit security PIN, and initial balance.
- **Deposit & Withdrawal:** Securely update customer balances with PIN authentication and overdraft checks.
- **Balance Inquiry:** View real-time account details after PIN verification.
- **Persistent Storage:** All records are saved locally in `bank_records.dat` using `fstream` binary file operations.

## How to Run
1. Compile the code using a C++ compiler:
   ```bash
   g++ main.cpp -o bank_app
   ```
2. Run the executable:
   ```bash
   ./bank_app
   ```
