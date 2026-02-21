# ATM Console Application (C++)

A professional C++ console-based ATM system that simulates real-world Automated Teller Machine (ATM) operations.  
This application allows users to securely login to their accounts using an account number and PIN code, perform deposits, withdrawals, quick withdrawals, and check their balance. It is designed with a clear menu-driven interface to ensure ease of use and safety during all banking operations.

---

## Overview

The ATM Console Application is a fully functional banking simulation for educational purposes. It provides a realistic experience of interacting with an ATM machine, while demonstrating C++ programming concepts such as file handling, structures, enums, input validation, and menu-driven interfaces.

The application stores all client data in a text file (`Clients.txt`), including account numbers, PIN codes, names, phone numbers, and account balances. Users can perform transactions while ensuring that invalid operations (such as withdrawing more than the balance or entering invalid amounts) are prevented.

---

## ✨ Features

- **User Authentication:** Login securely using an account number and PIN code. Only valid accounts can access the system.  
- **Quick Withdraw:** Withdraw predefined amounts (20, 50, 100, 200, 400, 600, 800, 1000) quickly with one selection.  
- **Normal Withdraw:** Withdraw a custom amount, must be a multiple of 5, with balance validation.  
- **Deposit:** Deposit a positive amount to the account with confirmation before processing.  
- **Check Balance:** View the current account balance at any time.  
- **Transaction Confirmation:** Every deposit or withdrawal requires confirmation to prevent mistakes.  
- **Data Storage:** All client information is stored persistently in `Clients.txt`.  
- **Menu-driven Console UI:** Interactive screens for Quick Withdraw, Normal Withdraw, Deposit, Check Balance, and Logout.  
- **Input Validation:** Ensures correct numeric input for all operations, preventing negative or invalid values.  
- **User-friendly Navigation:** Return to the main menu after each operation for smooth workflow.  

---

## Files in the Project

- `ATM.cpp` → Main source code implementing all functionality  
- `Clients.txt` → Data file storing all client accounts, PINs, names, phones, and balances  
- Optional files (if using Visual Studio):  
  - `.sln` → Solution file  
  - `.vcxproj` & `.vcxproj.filters` → Visual Studio project files  

---
## Author

Abd EL Rahman Elsaeedy
