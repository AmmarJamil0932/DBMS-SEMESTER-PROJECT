# Course Registration Conflict Resolution System

This is a semester project for the Database Management Systems (DBMS) course at Bahria University, Islamabad. The project aims to design and implement a system that resolves course registration conflicts and ensures optimized scheduling for students, advisors, and classrooms.

## 👨‍💻 Team Members

- Ammar Jamil (01-134231-010)  
- Zameer Hussain (01-134231-096)  
- Zaryab Ahmed (01-134231-097)

## 🧠 Objective

The objective of this project is to address common issues students face during course registration — such as timetable clashes a by implementing a centralized database system.

## 📚 Project Components

### 1. Entity-Relationship Diagram (ERD)

The ERD defines the structure of the system using entities like:
- **Advisor**: Advisor ID, Name, Email
- **Student**: Enrollment, Name, Email
- **Course**: Course ID, Name, Credit Hours, etc.
- **Course Offering**, **Time Table**, **Classroom**, and **Register** relationships

👉 _Detailed ERD and Relational Schema can be found in [ERD.pdf](./ERD.pdf)_


### 2. Normalization

The database schema is normalized to:
- **1NF**: Ensure atomicity
- **2NF**: Remove partial dependencies
- **3NF**: Remove transitive dependencies

👉 _Normalization details are available in [Normalization&Script.pdf](./Normalization&Script.pdf)_

---

### 3. SQL Script

The `Normalization&Script.pdf` also includes full DDL (Data Definition Language) scripts:
- Creating tables like `Advisor`, `Student`, `Course`, `TimeTable`, `Classroom`, `Section`, `Register`
- Setting up primary and foreign key constraints

## 💡 Features

- Centralized data model
- Simplified maintenance
- Integrated conflict resolution logic
- Clear relationships between entities
- Optimized for academic institutions

## 🛠 Technologies Used

- **Database**: MySQL / PostgreSQL (DDL script compatible)
- **Design**: Conceptual, Logical, and Physical DB design
- **Tools**: ERD Drawing Tools, SQL Workbench

## 🧾 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/AmmarJamil0932/DBMS-SEMESTER-PROJECT.git
