# 🎓 Student Result Management System  
A Java console-based application demonstrating **Exception Handling**, **Custom Exceptions**, and **Robust Input Validation**.  
This project is created for **Java Programming – Assignment 3**.

---

## 📌 Project Summary  
The system allows entry of student details and their marks, validates the input using custom exceptions, calculates average marks, and displays the final result (Pass/Fail).  
This project highlights strong exception-handling skills using:

- Built-in exceptions  
- Custom exceptions  
- try–catch–finally  
- throw and throws  

---

## 🛠️ Features  
### 👨‍🎓 Student Management  
- Add student details (Roll Number, Name, Marks)  
- Validate each mark (0–100)  
- Calculate average marks  
- Display pass/fail result  

### ⚠ Exception Handling  
- **InvalidMarksException** (custom)  
- Handles:
  - Invalid mark input  
  - Non-numeric input (InputMismatchException)  
  - Null inputs  
  - Missing data  

### 🧮 Result Criteria  
- Pass → Average ≥ 40  
- Fail → Average < 40  

---

## 📚 Concepts Covered  
✔ Checked vs. Unchecked Exceptions  
✔ Custom Exception Class  
✔ try–catch–finally  
✔ throw & throws  
✔ Modular Java class design  

---

## 🧩 Class Overview  

### **1️⃣ InvalidMarksException (Custom Exception)**  
- Thrown when marks are not between 0 and 100  

### **2️⃣ Student Class**  
- Attributes: rollNumber, studentName, marks[3]  
- Methods:
  - validateMarks()  
  - calculateAverage()  
  - displayResult()  

### **3️⃣ ResultManager Class**  
- Handles user input  
- Menu-driven program  
- Stores multiple Student objects  
- Manages:
  - Adding students  
  - Displaying student details  
  - Exception handling  

---

## 🎮 Sample Program Interaction  

Welcome to Student Result Management System

Add Student

Show Student Details

Exit

Enter choice: 1
Enter Roll Number: 101
Enter Name: John Doe
Enter Marks for 3 Subjects: 88 76 92
Student added successfully!

Enter choice: 2
Enter Roll Number to Search: 101

Roll Number: 101
Name: John Doe
Marks: 88 76 92
Average: 85.33
Result: PASS
