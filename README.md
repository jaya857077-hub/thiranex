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


  # Library Management System (C++)

A console-based **Library Management System** developed in C++ using Object-Oriented Programming (OOP) principles and file handling. Created as part of the **Thiranex C++ Programming Internship**.

## Features
- **Object-Oriented Design:** Uses dedicated `Book`, `Member`, and `Library` classes to manage records cleanly.
- **Book & Member Management:** Add new books and register library members with unique IDs.
- **Issue & Return Tracking:** Issue available books to registered members and process returns.
- **Search Functionality:** Case-insensitive search for books by **Title** or **Author**.
- **Persistent Storage:** Automatically saves and loads book and member records using local text files (`books.txt` and `members.txt`).

## How to Compile and Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Library-Management-System
   ```

2. **Compile the code using g++:**
   ```bash
   g++ library_management.cpp -o library_management
   ```

3. **Run the executable:**
   - **Windows:** `library_management.exe`
   - **Linux/macOS:** `./library_management`




### 2. Tic Tac Toe Mini Game (`tic_tac_toe.cpp`)
- **Concepts Used:** 2D Arrays, Nested Loops, Conditional Logic.
- **Features:**
  - Dynamic console board updates after every move.
  - Input validation and win/draw detection.
  - Replay loop for continuous gameplay.

## How to Run
Compile and run using any standard C++ compiler (such as `g++`):
```bash
g++ library_management.cpp -o library
./library
```
