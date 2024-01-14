# Bank Management System

This is a simple Bank Management System implemented in Java using Swing for the graphical user interface and JDBC for database connectivity. The system includes functionalities like creating a new account, depositing money, and viewing transaction history.

## Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)


## Introduction

This project aims to provide a basic banking system that allows users to create new accounts, deposit money, and view their transaction history. It is built using Java and incorporates a graphical user interface for ease of use.

## Features

- *New Account Creation:* Users can create a new bank account by providing personal details.
- *Deposit:* Users can deposit money into their accounts, and the transaction details are stored in the database.
- *Transaction History:* Users can view their transaction history, including deposits and withdrawals.

## Installation

1. Clone the repository to your local machine.
 git clone https://github.com/MANU5700/Bank-Management-System

2. Open the project in your preferred Java IDE (Integrated Development Environment).
3. Make sure to set up the necessary database connectivity details in the Conn.java file.
4. Compile and run the Signup.java file to start the application.

## Usage

### Existing Users:

1. *Sign In:*
   - Launch the application, and the initial screen will prompt existing users to sign in.
   - Enter your Card Number and PIN.
   - Click on the "Sign In" button.
2. *Operations for Existing Users:*
   - After signing in, you will be presented with the following options:
     - *Deposit:* Deposit money into your account.
     - *Withdraw:* Withdraw money from your account.
     - *Fast Cash:* Quickly withdraw a pre-defined amount.
     - *Mini Statement:* View a summary of your recent transactions.
     - *Balance Enquiry:* Check your account balance.
3. *Clear Details:*
   - To reset the Card Number and PIN fields, click on the "Clear" button.

### New Users:

1. *Sign Up:*
   - If you are a new user, click on the "Sign Up" option on the initial screen.
   - Fill in the required personal details in the first form, including name, address, father's name, etc.
   - Click on "Next" to proceed to the next form.
2. *Additional Information:*
   - Fill in additional information such as category, religion, etc.
   - Click on "Next" to proceed to the final form.
3. *Account Details:*
   - In the final form, you will be prompted to provide account details.
   - Once completed, click on "Create Account."
4. *Card Number and PIN:*
   - After successfully creating a new account, your Card Number and PIN will be displayed.
   - Use these details to sign in as an existing user.
5. *Operations for New Users:*
   - As a new user, after signing in with the provided Card Number and PIN, you can perform operations like depositing money, withdrawing, etc.
6. *Clear Details:*
   - To reset the details during the sign-up process, click on the "Clear" button.
