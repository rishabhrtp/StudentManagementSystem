# Student Management System (Java + JDBC + MySQL + Maven)

A simple **Student Management System** built using Java, JDBC, MySQL, and Maven.  
This project demonstrates basic CRUD operations with a clean DAO architecture.

---

## 📌 Features

- Add new student
- View all students
- Update student details
- Delete student
- Search student by ID

---

## 🛠️ Tech Stack

- Java (Core Java)
- JDBC (Java Database Connectivity)
- MySQL Database
- Maven (Dependency Management)
- Eclipse IDE

---

## 🗄️ Database Setup

Create database and table in MySQL:

```sql
CREATE DATABASE student_db;

USE student_db;

CREATE TABLE student (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    age INT,
    marks INT,
    city VARCHAR(100)
);

⚙️ Project Setup
Clone the repository
Import as Maven Project in Eclipse/IDE
Update pom.xml dependencies
Configure MySQL username and password in DBConnection.java
Run Main.java

👨‍💻 Author

Rishabh Kumar
Java Backend Developer (Learning Phase)

📜 License

This project is for learning purposes.
