# 🏦 Banking Management System in C++

This is a console-based banking application written in C++. It simulates the core functionalities of a bank such as user authentication, account management, and loan handling. The system supports both admin and customer roles, with persistent data storage using plain text files.

---

## ✨ Features

### 👤 User Roles

- **Admin**
  - Create, update, delete customer accounts
  - View and manage loans
  - Modify passwords

- **Customer**
  - Login using username/password
  - View personal profile
  - Deposit and withdraw money
  - Check balance
  - Change login credentials

---

## 💰 Account & Loan Management

### Account Types
- **Savings Account**
- **Checking Account**

### Loan Types
- **Student Fee Loan**
- **Personal Loan**

Each account or loan is saved in a different file and includes information such as name, ID, balance, credit type, email, phone number, etc.

---

## 📁 Example Data Files

Each row in the text files corresponds to a single record (customer or loan). Data is aligned in columns for clarity.

### 🔹 `save.txt` – Savings Accounts

| First Name | Last Name | Username | Password | Account No | Balance | Credit Type | Email | Phone |
|------------|-----------|----------|----------|------------|---------|-------------|-------|-------|
| John       | Doe       | johnuser | pass123  | 1001       | 5000    | Debit       | john@example.com | 1234567890 |
| Alice      | Smith     | alice_s  | pass456  | 1002       | 7500    | Credit      | alice@example.com | 2147483647 |

---

### 🔸 `check.txt` – Checking Accounts

| First Name | Last Name | Username | Password | Account No | Balance | Credit Type | Email | Phone |
|------------|-----------|----------|----------|------------|---------|-------------|-------|-------|
| Robert     | Johnson   | robj     | pass789  | 2001       | 3000    | Debit       | rob@example.com | 2147483647 |
| Emily      | Davis     | emilyd   | pass000  | 2002       | 6200    | Credit      | emily@example.com | 2147483647 |

---

### 🟢 `student.txt` – Student Fee Loans

| First Name | Last Name | Username | Password | Loan ID | Amount | Interest (%) | Year | Email | Phone |
|------------|-----------|----------|----------|---------|--------|---------------|------|--------|-------|
| Michael    | Brown     | mikeb    | pass111  | 3001    | 10000  | 5             | 2023 | mike@example.com | 33311223344 |
| Sarah      | Wilson    | sarahw   | pass222  | 3002    | 8000   | 4.5           | 2024 | sarah@example.com | 22233445566 |

---

### 🟠 `personal.txt` – Personal Loans

| First Name | Last Name | Username | Password | Loan ID | Amount | Interest (%) | Term (years) | Email | Phone |
|------------|-----------|----------|----------|---------|--------|---------------|----------------|--------|-------|
| David      | Miller    | davidm   | pass333  | 4001    | 15000  | 7.5           | 5              | david@example.com | 77788990011 |
| Jennifer   | Lee       | jenlee   | pass444  | 4002    | 12000  | 6             | 3              | jen@example.com | 88877665544 |

---

### 💼 `invest.txt` – Investment Accounts

| First Name | Last Name | Username | Password | Account ID | Amount | Nominee Name | Risk Level | Email | Phone |
|------------|-----------|----------|----------|------------|--------|---------------|-------------|--------|-------|
| Thomas     | Moore     | tommy    | pass555  | 5001       | 20000 | UncleMoore    | High        | tom@example.com | 99988776655 |
| Olivia     | Green     | oliviag  | pass667  | 5002       | 25000 | AuntGreen     | Medium      | olivia@example.com | 11122334455 |

---

## ⚙️ How to Compile

```bash
g++ -o bank_app Banking_Management_System.cpp
```

---

## 🔒 Default Login Credentials
Admin:

- Username: admin
- Password: admin

Customer Example:

- Username: johnuser
- Password: pass123

---

## 📌 Future Enhancements
- Replace .txt files with a database (SQLite, MySQL)

- Encrypt passwords

- Add GUI using Qt or Tkinter (via Python)

- Implement user roles via classes/interfaces

- Add transaction history for each user

---

## 👨‍💻 Author
Developed by Cristi

This is an academic-style project simulating real-world banking operations using C++ and file handling.
