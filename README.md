
Banking System with C++ STL
This C++ program implements a simple banking system using the Standard Template Library (STL). It allows users to perform various operations such as opening an account, checking balance, depositing, withdrawing, closing an account, and displaying all accounts.

Program Structure
Account Class:

Represents a bank account with attributes such as account number, first name, last name, and balance.
Supports operations like deposit and withdrawal.
Friend functions for overloading stream insertion and extraction operators for file I/O.
Bank Class:

Manages a collection of Account objects using a map.
Provides functions for opening accounts, checking balances, depositing, withdrawing, closing accounts, and displaying all accounts.
Utilizes file I/O to store and retrieve account information.
InsufficientFunds Exception Class:

Exception class thrown when a withdrawal results in insufficient funds.
main Function:

Implements the user interface for interacting with the banking system.
Allows users to select operations through a menu.
