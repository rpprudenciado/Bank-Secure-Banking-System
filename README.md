# 🏦 Bank-Secure-Banking-System

## 📌 Overview
The **NCTN Bank Secure Banking System** is a Java-based desktop application that simulates real-world banking operations.

Developed as a final project for *Introduction to Programming Language*, this system integrates secure authentication, transaction management, fund transfers, and administrative recovery features into a single modular application.

The project demonstrates how fundamental programming concepts can be applied to build a functional and interactive banking system.


## 👥 Developers
Rhona-Mae Prudenciado
Evan Exanes
**NCTN**


## 🎯 Project Goals
* Apply core Java programming concepts in a practical system
* Demonstrate Object-Oriented Programming principles
* Implement secure login with account locking mechanism
* Develop a user-friendly interface using `JOptionPane`
* Manage account data using `ArrayList`


## ✨ Features
### 👤 User Functionalities
* 🆕 Create new bank accounts
* 🔐 Secure login authentication
* 🚫 Automatic account locking after 3 failed attempts
* 💰 Check account balance
* ➕ Deposit funds
* ➖ Withdraw funds with balance validation
* 🔄 Transfer funds between accounts
* 📜 View complete transaction history
* 🚪 Logout securely

### 🔑 Admin Functionalities
* 🔐 Admin authentication
* 📋 View all registered accounts
* 🔓 Unlock locked accounts
* 🔁 Reset user passwords


## 🧠 Programming Concepts Used
* Variables and Named Constants
* Primitive Data Types (`int`, `double`, `boolean`, `char`)
* Conditional Statements (`if-else`, `switch`)
* Loops (`while`, `for`)
* Arrays and `ArrayList`
* Object-Oriented Programming
  * Classes
  * Constructors
  * Methods
  * Encapsulation
* Exception Handling
* GUI Development using `JOptionPane`


## 🏗️ System Architecture
The application is structured into three main classes:

### 1️⃣ BankAccount
Handles:
* Account details
* Balance updates
* Transaction history
* Login attempt tracking
* Account locking mechanism

### 2️⃣ Bank
Handles:
* Account storage
* Account searching
* Fund transfers
* Account validation

### 3️⃣ BankingAppGUI
Handles:
* User interaction
* Menu display
* Input validation
* Admin operations
* Program execution flow
  

## 🔢 Account Numbering System
Account numbers start at **1001** to simulate realistic banking standards and maintain a professional numbering structure instead of starting from 1.

## 🚀 How to Run the Project
1. Open the project in any Java IDE (NetBeans, IntelliJ, Eclipse).
2. Compile all three classes.
3. Run the `BankingAppGUI` class.
4. Follow the dialog prompts to interact with the system.


## 📸 Sample Functional Flow
* Create 5 accounts (1001–1005)
* Test invalid account number handling
* Trigger account locking with wrong passwords
* Use admin to unlock and reset password
* Perform deposits and withdrawals
* Transfer funds between accounts
* Verify updated balances
* View transaction history


## 📚 References
* Deitel, P. & Deitel, H. (2018). *Java How to Program* (11th ed.). Pearson Education.
* Farrell, J. (9th Edition). *Java Programming*. C&E Publishing.
* Oracle Corporation. (2024). *Java SE Documentation*.
* Oracle Corporation. (2024). *JOptionPane Class Documentation*.
* Programiz. (2024). *Java Programming Tutorial*.
* *Introduction to Programming Language PPT Lessons*.


## 📖 Academic Note
This project was developed for educational purposes to demonstrate mastery of foundational Java programming concepts, secure system design, and GUI application development.
