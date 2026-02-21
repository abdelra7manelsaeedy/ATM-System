# ATM Console Application (C++)

A professional C++ console-based ATM system that simulates real-world Automated Teller Machine operations.  
This application allows clients to securely login using their Account Number and PIN, perform deposits, withdrawals (quick or normal), and check their account balance, all via a simple and interactive console interface.

---

## Overview

This C++ Console Application simulates a simple ATM system.  
It provides clients with the ability to manage their accounts, perform financial transactions, and monitor balances in a realistic menu-driven environment.  
All client data is stored in `Clients.txt` for persistence.

---

## ✨ Features

- **User Authentication:** Login system for clients using Account Number and PIN.  
- **Quick Withdraw:** Select predefined amounts for fast transactions.  
- **Normal Withdraw:** Withdraw a custom amount (must be a multiple of 5).  
- **Deposit:** Deposit money into client accounts with confirmation.  
- **Check Balance:** View current account balance instantly.  
- **Data Storage:** Client data stored persistently in `Clients.txt`.  
- **Console UI:** Interactive menu-driven screens for easy navigation.  
- **Input Validation:** Prevents invalid amounts or incorrect choices.  

---

## Files in the Project

- `ATM System.cpp` → Main source code  
- `Clients.txt` → Stores all client information  
- Optional (for Visual Studio):  
  - `ATM System.sln` → Solution file  
  - `ATM System.vcxproj` & `ATM System.vcxproj.filters` → Project files  
  - `ATM System.rc`, `resource.h` → Resource files  

---

## ▶️ How To Run

1. Open the project in Visual Studio or compile with a C++ compiler.  
2. Build the project (Ctrl + Shift + B in Visual Studio).  
3. Run the executable (`F5` in Visual Studio or `./ATM` in terminal).  
4. Login using a valid client account from `Clients.txt`.  
5. Navigate the menu to perform Quick Withdraw, Normal Withdraw, Deposit, or Check Balance.  

> **Note:** Ensure `Clients.txt` is in the same folder as the executable for proper operation.


## 👤Author

**Abd EL Rahman Elsaeedy**  

---

This project demonstrates practical C++ skills, including file handling, menu-driven programming, input validation, and structured programming. It is ideal as an educational simulation and portfolio showcase for console-based banking applications.
