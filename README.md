# Student Record Management System

A simple **Student Record Management System** built in **Java** using core **Object-Oriented Programming (OOP)** principles.  
This program lets users add student details, view all records, and automatically calculate grades based on marks.

---

## 🚀 Features
- Add new student records (Roll No, Name, Course, Marks)
- Automatic grade calculation:
  - **A** → Marks ≥ 90  
  - **B** → Marks ≥ 75  
  - **C** → Marks ≥ 50  
  - **D** → Marks < 50  
- Display all student records in a neat table format
- Menu-driven console interface
- Uses **ArrayList** to store multiple records dynamically
- Implements OOP concepts: **inheritance, constructors, encapsulation, methods**

---

## 🏗️ Class Structure

### **Person** (Base Class)
- **Field:** name

### **Student** (Derived Class)
- **Fields:** rollNo, course, marks, grade  
- **Methods:**  
  - `inputDetails()` – Take user input  
  - `displayDetails()` – Display student details  
  - `calculateGrade()` – Compute grade based on marks  

---

## 🖥️ Sample Output

