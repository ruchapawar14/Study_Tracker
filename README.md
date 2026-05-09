# 📚 Study Tracker App

> A console-based Java application developed to manage, track, summarize, and export daily study activities efficiently.

---

## 📌 Project Overview

**Study Tracker App** is a menu-driven Java application that helps students maintain daily study records systematically.

The application allows users to:

- Insert study logs
- View all study records
- Generate summaries by date
- Generate summaries by subject
- Export study records to a CSV file

This project demonstrates practical implementation of:

- Object-Oriented Programming
- Java Collections Framework
- File Handling
- Menu-Driven Programming
- LocalDate API

---

## 🧠 Key Features

### 📖 Insert Study Logs
- Add study session details
- Automatically captures current date
- Stores:
  - Subject
  - Duration
  - Description

### 📋 Display All Logs
- Displays all stored study records
- Shows complete study history in formatted output

### 📅 Summary by Date
- Calculates total study hours per day
- Uses `TreeMap` for sorted date-wise summary

### 📘 Summary by Subject
- Calculates total study duration subject-wise
- Helps analyze study patterns

### 📂 Export to CSV
- Exports all records into:
  
```text
StudyTracker.csv
```

- CSV file can be opened in:
  - Excel
  - Google Sheets
  - LibreOffice Calc

### ⚙️ Menu-Driven Console Interface
- Simple switch-case based navigation
- Easy to use command-line interface

---

## 🎯 Learning Outcomes

- Understanding of Java OOP concepts
- Practical usage of:
  - Classes & Objects
  - Constructors
  - Encapsulation
  - ArrayList
  - TreeMap
- Experience with Java File Handling
- Knowledge of CSV file generation
- Improved problem-solving and console application development skills

---

## 🛠️ Technologies Used

- Java
- Java Collections Framework
- LocalDate API
- File Handling
- Scanner Class
- VS Code / Command Prompt

---

## 🧱 Classes Used

### 📘 StudyLog
Represents a single study session.

#### Attributes
- Date
- Subject
- Duration
- Description

#### Methods
- Constructor
- Getter methods
- `toString()`

---

### 📗 StudyTracker
Handles all study log operations.

#### Methods
- `InsertLog()`
- `DisplayLog()`
- `ExportCSV()`
- `SummaryByDate()`
- `SummaryBySubject()`

---

### 📙 StudyTrackerApp
Contains:
- `main()` method
- Menu-driven interface
- User interaction logic

---

## ▶️ Compilation

```bash
javac StudyTrackerApp.java
```

---

## ▶️ Execution

```bash
java StudyTrackerApp
```

---

## 📌 Sample Console Output

### 💻 Main Menu

```text
---------------------------------------------------------
----------------Welcome to Study Tracker-----------------
---------------------------------------------------------

1. Insert new study log
2. View all study log
3. Export study log to CSV file
4. Summary of study log by the date
5. Summary of study log by the subject
6. Exit the application
```

---

### 📖 Insert Study Log

```text
Please enter the name of the subject like C/C++/Java/Python
Java

Enter the time period of your study in hours :
2

Please provide the description of your study :
OOP Concepts

Study Log gets stored successfully...
```

---

### 📋 Display Logs

```text
---------------------------------------------------------
----------------Log Report of Study Tracker--------------
---------------------------------------------------------

2026-05-09 | Java | 2.0 | OOP Concepts
2026-05-09 | Python | 1.5 | Functions and loops
2026-05-09 | DBMS | 1.0 | SQL Queries

---------------------------------------------------------
```

---

### 📂 CSV Export Output

```text
Data gets exported in CSV : StudyTracker.csv
```

---

## 🔥 Key Concepts Demonstrated

- Object-Oriented Programming
- Collections Framework
- File Handling
- Exception Handling
- Menu-Driven Programming
- Data Summarization
- CSV Generation

---

## 👩‍💻 Author

### Rucha Hanumant Pawar
