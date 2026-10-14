# 🏦 Banking System Using Python OOP

A simple console-based **Banking System built using Python and Object-Oriented Programming (OOP)**. This project demonstrates fundamental OOP concepts through a banking application where users can create a savings or current account and perform basic banking operations.

## 📌 Project Overview

The Banking System allows users to enter their account details, select an account type, manage their balance, deposit and withdraw money, and calculate interest. It uses Python classes and methods to organize the banking operations.

This project was created for learning and practicing Python OOP concepts.

## ✨ Features

- **Account Creation:** Enter an account number, account holder name, and initial balance.
- **Account Types:** Choose between a Savings Account and a Current Account.
- **Check Balance:** View account details and the current balance.
- **Deposit Money:** Add money to the account with basic amount validation.
- **Withdraw Money:** Withdraw money while checking for sufficient balance.
- **Interest Calculation:** Calculate interest at a rate of 1% of the current balance.
- **Input Validation:** Handle invalid numeric inputs and prevent negative initial balances.
- **Interactive Banking Menu:** Perform multiple banking operations until the user exits.

## 🧠 OOP Concepts Used

This project demonstrates the following Object-Oriented Programming concepts in Python:

| Concept | Implementation |
|---|---|
| Classes and Objects | `Bankaccount`, `SavingAccount`, and `CurrentAccount` |
| Encapsulation | The account balance is stored in the private attribute `__balance` and accessed through a property. |
| Inheritance | `SavingAccount` and `CurrentAccount` inherit from `Bankaccount`. |
| Polymorphism | Both account types implement their own `calculate_intrest()` method. |
| Abstraction | The notebook uses the `@abstractmethod` decorator to introduce the concept of abstract methods. |

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Concepts:** Object-Oriented Programming
- **Development Environment:** Jupyter Notebook
- **Libraries:** Python standard library (`abc` module is imported in the notebook)

## 📂 Project Structure

```text
Banking-System-OOP/
│
├── oops programms .ipynb
└── README.md
```

## 🚀 How to Run the Project

### Option 1: Run using Jupyter Notebook

1. Clone or download this repository.
2. Install Python 3 and Jupyter Notebook if they are not already installed.
3. Open a terminal in the project directory.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `oops programms .ipynb`.
6. Run the notebook cells in order.
7. Enter the requested account details and use the interactive banking menu.

### Option 2: Run using Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook file.
3. Run the cells in sequence.
4. Enter your account information when prompted.

## 💻 How to Use

When the program starts:

1. Enter your account number.
2. Enter the account holder's name.
3. Select an account type:
   - `1` — Savings Account
   - `2`
