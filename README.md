🏦 Smart Banking Management System (Python & SQLite)
📌 Project Overview

The Core Banking Management System is a Python-based application designed to manage essential banking operations using an SQLite database. The system efficiently handles customer data, bank accounts, and financial transactions while maintaining relational integrity between entities.

It enables secure storage, retrieval, and analysis of banking records and presents database outputs in a clear, professional tabular format using the tabulate library.

🎯 Key Objectives

Manage core banking data using a relational database

Perform fundamental banking operations programmatically

Enable structured querying and transaction analysis

Display database results in a readable and professional format

🛠️ Technologies Used

Programming Language: Python

Database: SQLite

Libraries:

sqlite3 – Database connectivity and operations

tabulate – Display database tables in grid format

📂 Database Structure

The project maintains multiple relational tables, including:

BANK_CUSTOMER – Stores customer details

BANK_ACCOUNT – Manages bank account information

TRANSACTIONS – Records deposits and withdrawals

CUSTOMER_ACCOUNT_LINK – Links customers with multiple accounts

⚙️ Core Features
👤 Customer Management

Add new customers

Update existing customer details

Retrieve customer records from the database

🏦 Account Management

Create bank accounts

Link multiple accounts to a single customer

Fetch account details using SQL queries

💰 Transaction Handling

Deposit funds into accounts

Withdraw funds with balance validation

Automatically update account balances

📄 Statement Generation

Generate account statements

View transaction history by account or customer

Analyze financial data using SQL queries

📊 Professional Data Display

Uses the tabulate library to display SQLite table data

Presents outputs (e.g., BANK_CUSTOMER table) in clean, grid-formatted tables

Enhances readability for debugging, analysis, and reporting

🧪 Sample Output Format
+-------------+--------------+-------------+
| Customer ID | Name         | Phone       |
+-------------+--------------+-------------+
| 101         | Rahul Sharma | 9876543210  |
| 102         | Ananya Patil | 9123456780  |
+-------------+--------------+-------------+

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/core-banking-system.git


Navigate to the project directory:

cd core-banking-system


Install required library:

pip install tabulate


Run the main Python file:

python main.py

📈 Learning Outcomes

Hands-on experience with SQLite and relational databases

Understanding of SQL queries for financial data analysis

Implementation of CRUD operations in Python

Improved data presentation using Python libraries

Practical exposure to real-world banking system logic

🚀 Future Enhancements

User authentication and role-based access

GUI or Web interface (Flask / Streamlit)

Transaction logging and audit trails

Encryption for sensitive banking data

📄 Conclusion

This project demonstrates a structured and scalable approach to building a core banking management system using Python and SQLite. It effectively combines database design, SQL querying, transaction handling, and professional data presentation, making it suitable for academic projects, internships, and entry-level software roles.
