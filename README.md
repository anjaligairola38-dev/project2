# 🏧 ATM System (Python Project)

## 📌 Project Description

This project is a simple **ATM Simulation System** developed using Python.
It is a **menu-driven program** that allows users to perform basic banking operations such as checking balance, depositing money, withdrawing money, and viewing transaction history.

The project is designed using **modular programming**, where each functionality is implemented in a separate file for better readability and maintainability.

---

## 🎯 Features

* Display current account balance
* Deposit money into account
* Withdraw money from account
* View transaction history (Statement)
* Menu-driven system using infinite loop

---

## 🛠️ Technologies Used

* Python (Basic Concepts)
* Functions
* Modules (Multiple Files)
* Lists (for storing transactions)

---

## 📁 Project Structure

```
atm_project/
│
├── main.py        # Main menu-driven program
├── utils.py       # Stores balance and transactions
├── deposit.py     # Handles deposit functionality
├── withdraw.py    # Handles withdrawal functionality
├── balance.py     # Displays balance
├── statement.py   # Shows transaction history
```

---

## 🔄 How the Program Works

1. The program starts from `main.py`
2. A menu is displayed using an infinite loop (`while True`)
3. User selects an option
4. Based on the choice, the respective function is called from different modules
5. Data (balance & transactions) is stored in `utils.py`

---

## ▶️ How to Run the Program

1. Make sure all files are in the same folder
2. Open terminal or command prompt
3. Run the following command:

```
python main.py
```

---

## 💡 Example Output

```
===== ATM MENU =====
1. Display Balance
2. Deposit Money
3. Withdraw Money
4. Statement
5. Exit

Enter your choice: 2
Enter amount to deposit: 500
Amount deposited successfully
```

---

## 📚 Key Concepts Covered

* Modular Programming
* Function Usage
* Infinite Loop (`while True`)
* Conditional Statements (`if-elif-else`)
* List Data Structure

---

## 🚀 Future Enhancements

* Add PIN authentication
* Store data using file handling (permanent storage)
* Add user account system
* Improve user interface

---

## 👨‍💻 Author
ANJALI
Developed as a beginner-friendly Python project for learning purposes.
