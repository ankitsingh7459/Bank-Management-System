🏦 Bank Management System

A Java-based Bank Management System that simulates basic banking operations such as account creation, deposits, withdrawals, and balance inquiry. The project demonstrates the use of Object-Oriented Programming (OOP) concepts and database connectivity using JDBC and MySQL to manage banking data efficiently.

This system automates simple banking processes and provides a structured way to manage customer accounts and transactions digitally.

🚀 Features

Create a new bank account

Deposit money into an account

Withdraw money from an account

Check account balance

Manage customer account information

Store and retrieve data using a database

🛠️ Technologies Used

Java – Core programming language

JDBC (Java Database Connectivity) – Connects Java application with MySQL database

MySQL – Database for storing account details and transactions

Object-Oriented Programming (OOP) – Used for modular and structured design

📂 Project Structure
Bank-Management-System
│
├── src
│   ├── Main.java
│   ├── Account.java
│   ├── Bank.java
│   └── DatabaseConnection.java
│
├── database
│   └── bank.sql
│
└── README.md
▶️ How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/ashuuu14/Bank-Management-System-.git
2️⃣ Open the Project

Open the project in any Java IDE:

IntelliJ IDEA

Eclipse

VS Code

3️⃣ Setup MySQL Database

Install MySQL Server

Create a new database (for example bankdb)

Create the required tables or import the SQL file if available

Example:

CREATE DATABASE bankdb;
4️⃣ Configure Database Connection

Update the database credentials in the Java file:

String url = "jdbc:mysql://localhost:3306/bankdb";
String username = "root";
String password = "yourpassword";
5️⃣ Compile and Run

Compile the Java files and run the main program.

Example:

javac Main.java
java Main
📚 Learning Outcomes

This project helps in understanding:

Java Object-Oriented Programming

JDBC database connectivity

MySQL database operations

Basic banking transaction logic

Software design for real-world applications
