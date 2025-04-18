Bank Management System in C++

A simple console-based Bank Account Management System built using Object-Oriented Programming (OOP) in C++. This project is ideal for beginners learning classes, constructors, encapsulation, and input validation.

Features

- Create a bank account  
- Deposit money  
- Withdraw money  
- Check current balance  
- Display account information  
- Menu runs continuously until the user chooses to exit  
- Handles invalid inputs gracefully

OOP Concepts Used

Encapsulation
All account-related data (accountHolder, accountNumber, balance) is kept private, and public methods like deposit(), withdraw(), and displayAccountInfo() provide controlled access. This ensures that internal data is safe and only accessible through proper functions.

Constructor
A parameterized constructor is used to initialize account details at the time of object creation.

Sample Output

1. Deposit
2. Withdraw
3. Check Balance
4. Display Account Info
5. Exit
Enter your choice: abc
Invalid input! Please enter a number from 1 to 5.

Enter your choice: 1
Enter amount to deposit: 500
Amount deposited successfully!
