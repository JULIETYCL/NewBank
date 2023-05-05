# Bank System
This project is a simple Java-based client-server bank system that allows users to manage their bank accounts.

## Table of Contents
-[Project Structure](#project-structure)
-[How to Run](#how-to-run)
-[Features](#features)

## Project Structure
The project is divided into two main folders:

`server`: Contains the server-side components for the bank system.
`Account.java`: Represents a bank account with account name and opening balance.
`Customer.java`: Represents a customer with a list of accounts.
`CustomerID.java`: Represents a customer ID with a unique key.
`NewBank.java`: The main class for the bank's operations and data storage.
`NewBankClientHandler.java`: Handles individual client connections and processes client requests.
`NewBankServer.java`: The main server class that listens for incoming connections and starts client handler threads.

`client`: Contains the client-side components for the bank system.
`ExampleClient.java`: Represents a simple client that connects to the server and sends commands.

## How to run
1. Run the NewBankServer file
2. Run the EXampleClient file

## Features
The current implementation supports the following features:

1. User authentication
2. Displaying user's bank accounts and balances

The following commands are available for the user:

`SHOWMYACCOUNTS`: Displays the user's bank accounts and balances.
More features can be added by extending the NewBank.java class and implementing additional methods.£

