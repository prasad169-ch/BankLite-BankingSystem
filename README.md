# 🏦 BankLite – Console Banking System (p)

BankLite is a Python console application that simulates a basic banking system. It allows users to create accounts, deposit and withdraw money, view balances and transaction history, and save/load data persistently using JSON. This project is built with Object-Oriented Programming (OOP) principles to give a real-world feel of banking software.

---

## 📌 About

This project is part of my placement preparation journey with #placementprep2025 and #nxtwave.

---

## 🎯 Objective

- Create accounts with unique IDs and starting balances.
- Deposit and withdraw funds with input validation.
- View current balance and full transaction history.
- Save all account data and transactions to a JSON file (`bank.json`) and load it on startup.

---

## 🧰 Technologies & Concepts Used

| Technology / Concept          | Implemented |
|------------------------------|-------------|
| Python 3                     | ✅          |
| Object-Oriented Programming  | ✅          |
| File Handling (JSON)         | ✅          |
| Unique ID Generation (incremental IDs) | ✅          |
| Timestamped Transactions     | ✅          |
| Input Validation             | ✅          |
| Console-based User Interface | ✅          |

---

## 🚀 Features

- Create Account with unique numeric ID.
- Deposit and Withdraw funds with balance checks.
- View Account balance and transaction history.
- Save and Load data from `bank.json` file.
- Log all transactions with timestamps.

---

## 📂 File Structure

BankLite/
├── banklite.py # Main source code with Account and Bank classes
├── bank.json # JSON file storing account and transaction data (generated after running)
└── README.md # Project documentation 

## 💻 How to Run

### Using Google Colab (Recommended)

Open this link: [BankLite Colab Notebook](https://colab.research.google.com/drive/1SwCCw6C3d_7Sfkx10kKNRRPhbHHB7Xyq?usp=sharing)  
Run each cell step-by-step and interact with the console interface.

### Using Local Python

Run this command in your project directory:

```bash
python banklite.py



3. **Add Sample Output**

Show a small snippet of what the user sees:

```markdown
## 📸 Sample Console Interaction

--- BankLite Menu ---

Create Account

Deposit

Withdraw

View Balance & History

Save Data

Exit

Enter choice: 1
Enter your name: Prasad
Enter starting balance: 1000
Account created with ID: 1

Enter choice: 2
Enter account ID: 1
Enter deposit amount: 500
Deposit successful.

Enter choice: 4
Enter account ID: 1
Account ID: 1
Name: Prasad
Balance: ₹1500
Transaction History:
2025-08-12 01:39:50 - Deposited ₹500


📘 What I Learned
✅ How to design and implement reusable OOP structures
✅ How to manage real-time data input/output from users
✅ How to persist data using JSON
✅ How real banking systems track and log transactions

💡 Future Enhancements (Optional Ideas)
🔒 Add PIN-based account login system

📈 Interest calculator or recurring deposits

🖥️ GUI version using Tkinter or web version using Flask/Django

🗃️ Database integration with SQLite or MongoDB

📢 Share Your Thoughts
This project helped me grow in both technical and logical thinking. I’d love your feedback, suggestions, or even collaboration ideas!

#placementprep2025 #nxtwave #pythonproject #banking #oop #jsonstorage #filehandling #consoleapp
