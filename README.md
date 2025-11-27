# Student Record Management System

A simple **Student Record Management System** built in **Java** using core **Object-Oriented Programming (OOP)** principles.  
This program allows users to add student details, view all records, and automatically calculate grades based on marks.

---

## 🚀 Features
- Add new student records (Roll No, Name, Course, Marks)
- Automatic grade calculation:
  - **A** → Marks ≥ 90  
  - **B** → Marks ≥ 75  
  - **C** → Marks ≥ 50  
  - **D** → Marks < 50  
- Display all student records in a clean, readable format
- Menu-driven console interface
- Uses **ArrayList** for dynamic storage
- Implements OOP concepts like inheritance, constructors, encapsulation, and methods

---

## 🏗️ Class Structure

### **Person** (Base Class)
- **Field:** `name`

### **Student** (Derived Class)
- **Fields:** `rollNo`, `course`, `marks`, `grade`  
- **Methods:**  
  - `inputDetails()` – Takes input from user  
  - `displayDetails()` – Shows student details  
  - `calculateGrade()` – Computes grade based on marks  

---

## 🖥️ Sample Output

```plaintext
===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit

Enter your choice: 1
Enter Roll No: 101
Enter Name: Rahul
Enter Course: B.Tech
Enter Marks: 87.0

===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit

Enter your choice: 2
Roll No: 101
Name: Rahul
Course: B.Tech
Marks: 87.0
Grade: B

Enter your choice: 3
