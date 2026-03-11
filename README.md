# 🏦 Bank Management System

A Java-based Bank Management System that simulates basic banking operations such as account creation, deposits, withdrawals, and balance inquiry. The project demonstrates the use of Object-Oriented Programming (OOP) concepts and database connectivity using JDBC and MySQL to manage banking data efficiently.

This system automates simple banking processes and provides a structured way to manage customer accounts and transactions digitally.

---

## 🚀 Features

* Create a new bank account
* Deposit money into an account
* Withdraw money from an account
* Check account balance
* Manage customer account information
* Store and retrieve account data using a MySQL database

---

## 🛠️ Technologies Used

* **Java** – Core programming language
* **JDBC (Java Database Connectivity)** – Used for connecting Java with the database
* **MySQL** – Database for storing account and transaction details
* **OOP Concepts** – Encapsulation, modular design, and structured programming

---

## 📂 Project Structure

```
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
```

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```
git clone https://github.com/ashuuu14/Bank-Management-System-.git
```

### 2. Open the Project

Open the project using any Java IDE such as:

* IntelliJ IDEA
* Eclipse
* VS Code

### 3. Setup MySQL Database

1. Install MySQL Server
2. Create a database (example: `bankdb`)
3. Create required tables or import the provided SQL file

Example:

```
CREATE DATABASE bankdb;
```

### 4. Configure Database Connection

Update database credentials in the Java code:

```
String url = "jdbc:mysql://localhost:3306/bankdb";
String username = "root";
String password = "yourpassword";
```

### 5. Run the Program

Compile and run the main Java file.

```
javac Main.java
java Main
```

---

## 📚 Learning Outcomes

* Understanding Java Object-Oriented Programming
* Implementing JDBC database connectivity
* Performing CRUD operations with MySQL
* Designing simple banking transaction systems

---

## 🔮 Future Improvements

* Add Graphical User Interface (GUI) using Java Swing or JavaFX
* Implement authentication and user login system
* Add transaction history feature
* Improve security and error handling

---

## 👨‍💻 Author

**Ankit Singh**
B.Tech CSE (AI & ML)
