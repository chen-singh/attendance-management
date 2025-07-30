# Attendance Management System (AMS) - Terminal Based

This is a **Terminal-Based Attendance Management System** developed using **Core Java** and **Object-Oriented Programming (OOP)** principles. It is designed for simple attendance tracking for students and teachers without using a GUI or external libraries.

## 📌 Features

- 🔐 Student and Teacher login system
- 📅 Mark attendance
- 📊 View attendance records
- 📝 Add new students and teachers
- 📁 Stores data in CSV files (No external database required)
- 🖥️ Terminal-based UI (Simple menu system)

## 🛠️ Technologies Used

- Java (JDK 8+)
- File handling using CSV files
- OOP principles (Encapsulation, Inheritance, Polymorphism)

## 📂 Project Structure

```

.
├── Main.java                   # Entry point
├── model/
│   ├── Student.java            # Student class
│   ├── Teacher.java            # Teacher class
├── service/
│   ├── AttendanceService.java  # Attendance marking and viewing
│   ├── UserService.java        # Login and registration handling
├── data/
│   ├── students.csv            # Student data
│   ├── teachers.csv            # Teacher data
│   ├── attendance.csv          # Attendance records
└── util/
└── FileUtils.java          # File read/write helpers

````

## 🚀 Getting Started

### 1. Compile the project

Make sure Java is installed:

on cmd 
javac Main.java
````

### 2. Run the project

 on cmd
java Main
```

### 3. Use the terminal menu

Choose from options like:

1. Student Login
2. Teacher Login
3. Exit

## ✅ Usage Instructions

* Teachers can:

  * Add students
  * Selete Student
  * Update Student
  * View class-wise attendance

* Students can:

  * Log in to view their own attendance and mark attendance 

## 📁 Data Storage

All data is stored in CSV format for simplicity:

* `students.csv` — student details
* `teachers.csv` — teacher details
* `attendance.csv` — attendance logs

## 📌 Note

* This is a **basic version** intended for educational use or command-line environments.
* No external frameworks or GUI involved.

## 📧 Author

Developed by: Chen Singh . 



