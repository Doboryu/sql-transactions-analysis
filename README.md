# 💳 Fintech Transactions Database

This repository contains a simple SQL database and dataset for fintech-style transactions.  
It is designed to demonstrate **basic database design, SQL, and data handling** as part of my IT portfolio.

---

## 📂 Project Contents
- `transactions.sql` → SQL script to create and insert sample data.  
- `transactions.csv` → CSV export of the transactions table.  
- `README.md` → Project documentation.  

---

## 🛠 Table Structure
**transactions**  
| Column            | Type      | Description                       |
|-------------------|-----------|-----------------------------------|
| `transaction_id`  | INT       | Primary Key                       |
| `user_id`         | INT       | Sample user ID                    |
| `amount`          | DECIMAL   | Amount of the transaction         |
| `transaction_type`| VARCHAR   | Deposit, Withdrawal, or Payment   |
| `transaction_date`| DATE      | Date of the transaction           |

---

## 🚀 How to Use
### Option A: Import via SQL
1. Open **phpMyAdmin** (or MySQL CLI).  
2. Create a database (e.g., `portfolio_database`).  
3. Import `transactions.sql`.  

### Option B: Use the CSV
1. Open **Excel / Google Sheets / Python (Pandas)**.  
2. Load `transactions.csv`.  
3. Analyze or visualize the data.  

---

## 🎯 Purpose
This project is part of my **portfolio as an IT student pursuing Fintech**,  
showcasing database design and data export for **fintech and data science** use cases.

---

## 🔮 Future Improvements
- Add more transaction types (e.g., Transfer, Refund).  
- Simulate multiple users.  
- Build dashboards with Python & SQL.  

---

👨‍💻 Created with ❤️ by *Jiro Azil Santillan*  
