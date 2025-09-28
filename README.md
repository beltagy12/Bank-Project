# Bank Management System (C++)

A simple program for managing customer accounts in a bank, written in C++.

## Features
- Add a new client with their details (Account Number, PIN, Name, Phone, Balance).
- Update client information.
- Delete a client from the system.
- Search for a client by account number.
- Display all clients in the system.
- Financial operations:
  - Deposit money into a client’s account.
  - Withdraw money from a client’s account (with balance validation).
  - Show the total balance of all clients.

## Files
- main.cpp : The main source code of the project.
- Clients.txt : A text file used to store client data.

## How to Run
1. Open the project in any C++ IDE or compiler (e.g., Code::Blocks, Visual Studio, or g++).
2. Make sure the file Clients.txt exists in the same folder as the project (it can be empty at the start).
3. Compile and run the program.

## Example Usage
- When you run the program, a main menu is displayed.
- You can choose:
  - (1) to view the list of clients.
  - (2) to add a new client.
  - (3) to delete a client.
  - (4) to update client information.
  - (5) to search for a client.
  - (6) to access financial operations.
  - (7) to exit.

## Notes
- All data is stored in the Clients.txt file.
- The code can be extended with new features such as login functionality or encryption.