# 🎓 Student Record Management System (SRMS) – C++

A simple, menu-driven **Student Record Management System** built using **C++**, supporting:

- Add, update, delete students  
- Search by ID  
- Sorting options  
- Analytics (highest CGPA, average CGPA, total students)  
- File storage using `students.txt`  
- Auto-generated student IDs (format: `SRM2025XX`)  

---

## 🚀 Features

### ✅ 1. Add Student
- Auto-incremented ID  
- Stores: Name, Department, Year, CGPA  
- Saves instantly to file  

### ✅ 2. Display All Students
- Shows full list with formatting  
- Displays ID as: `SRM2025<ID>`

### ✅ 3. Search Student
- Search using numeric ID only (after `SRM2025`)

### ✅ 4. Delete Student
- Removes a student from memory + file  

### ✅ 5. Update Student
- Modify name, department, year, and CGPA  

### ✅ 6. Analytics Dashboard
- Total number of students  
- Highest CGPA + Top student  
- Average CGPA  

### ✅ 7. Sorting Options
Sort the student list by:
- Name (A → Z)
- CGPA (High → Low)
- Year (Ascending)

---

## 📂 File Handling

The data is automatically stored in:
students.txt
Copy code

File format for each student:
ID Name Department Year CGPA
Copy code

The system loads this file at startup and saves to it after every update.

---

## 🛠️ How to Compile & Run

### **Using g++**
```bash
g++ main.cpp -o srms
./srms
Using Visual Studio / VS Code
Create a C++ project
Paste the code
Build & run
🧩 Code Structure
Copy code

main.cpp
 ├── class Student
 ├── class SRMS
 │     ├── loadFromFile()
 │     ├── saveToFile()
 │     ├── addStudent()
 │     ├── displayAll()
 │     ├── searchStudent()
 │     ├── deleteStudent()
 │     ├── updateStudent()
 │     ├── showStats()
 │     └── sortMenu()
 └── main()  // menu-based system
📌 Example ID Format
Every student gets IDs like:
Copy code

SRM20251
SRM20252
SRM20253
📸 Output Preview
Copy code

========== ADVANCED SRMS ==========
1. Add Student
2. Display All Students
3. Search Student
4. Delete Student
5. Update Student
6. Analytics Dashboard
7. Sorting Options
8. Exit
Enter your choice:
📜 License
This project is free to use for learning or academic purposes.
👨‍💻 Author
Your Name (replace this)
Copy code

