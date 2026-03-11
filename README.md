## 𐙚 ‧₊˚ ⋅ Student Registration Console Program

૮ ˶ᵔ ᵕ ᵔ˶ ა  
A simple **console-based student registration system** developed in Python.  
This program allows users to register students into different faculties and store the data in a CSV file.

---

## 𐙚 ‧₊˚ ⋅ Project Overview

This project implements a **console menu system** that allows the user to:

- Select a **faculty (course)**
- Register **multiple students**
- Store the information **temporarily in memory**
- Save the records **permanently in a CSV file**

The system continues asking for new student data until the user decides to stop.

---

## 𐙚 ‧₊˚ ⋅ Program Structure

### 📚 Courses

The program includes a list with the following faculties:

- Engineering  
- Languages  
- Legal Sciences  
- Health Sciences  

The user selects one of these options at the beginning of the program.

---

### 👩‍🎓 Students List

An **empty list** called `estudiantes` is used to store student information during the program execution.

All registered students are temporarily stored in this list.

---

### 📄 CSV File Storage

At the end of the program, the student information is stored in a **CSV file named `clientes.csv`**, allowing the data to be saved permanently.

---

## 𐙚 ‧₊˚ ⋅ Functions

### `mostrar()`

This function prints the students stored in the `estudiantes` list.

It helps visualize all registered students during the session.

---

## 𐙚 ‧₊˚ ⋅ Program Flow

1. The program asks the user to **choose a faculty** (from 1 to 4).
2. The selected faculty is displayed.
3. The program enters a **loop**.
4. Inside the loop, the system:
   - Requests student information
   - Stores the data in the `estudiantes` list
5. The loop continues until the user types **`n`** to stop.
6. Finally, the data is **saved into the CSV file**.

---

## 𐙚 ‧₊˚ ⋅ Notes

Even though the requirements may vary in complexity, the program successfully registers multiple students and stores their information efficiently.

---

૮ ˶ᵔ ᵕ ᵔ˶ ა  
*A small console project, but a solid step toward learning data management and file handling in Python.*
