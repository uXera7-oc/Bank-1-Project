# Bank 1 Project – Console Banking System (C++)

This repository contains the **Bank 1 Project**, a **console-based banking system** written in **C++**, designed to manage client records efficiently.

The project is built as a **practical application** based on exercises from  
**Cplusplus Problems V3**, starting from **Problem #37**, and represents a transition from solving isolated problems to building a **complete, structured program**.

The system allows users to:
- Add new clients
- Delete existing clients
- Update client information
- Find clients by account number
- Display all clients in a formatted table

---

## 📂 Project Overview
The **Bank 1 Project** is developed following the **Divide and Conquer principle**, where the program logic is divided into **small, clear, and reusable functions**, each responsible for a single task.

All client data is stored persistently in a text file:
- **ClientsRecords.txt**

This simulates a simple database system using file handling.

---

## 🧱 Core Features
- Structured client data management
- Persistent storage using files
- Menu-driven user interface
- Clear separation between:
  - Input handling
  - Business logic
  - File operations
  - User interface

---

## 🛠️ Technologies Used
- **Language:** C++
- **File Handling:** `<fstream>`
- **Data Structures:** `struct`, `vector`
- **Formatting:** `<iomanip>`
- **Standard Libraries:** `<iostream>`, `<string>`, `<cctype>`

---

## 📐 Project Structure & Design
- Client data is represented using a **struct** (`stClientData`)
- Menu options are handled using an **enum** (`enMenuOptions`)
- Each operation (Add, Delete, Update, Find, Show List) is implemented in:
  - A **dedicated function**
  - A **separate screen function**
- File operations are abstracted into reusable helper functions
- The program uses a **loop-based main menu** until the user chooses to exit

---

## 🎯 Learning Objectives
This project demonstrates and reinforces the following concepts:

- Building a **complete console application**
- Applying **Divide and Conquer** methodology
- Writing **clean, readable, and maintainable code**
- Designing programs using **functions instead of monolithic logic**
- Transitioning from problem-solving to **real-world style applications**

---

## 🧠 Concepts & Skills Demonstrated in This Code
By completing this project, the programmer demonstrates solid understanding of:

### 🔹 C++ Fundamentals
- Variables and data types
- Conditional statements (`if`, `switch`)
- Loops (`while`, `do-while`, `for`)

### 🔹 Functions
- Function declaration and definition
- Passing parameters by value and by reference
- Returning values from functions
- Code reusability and modularity

### 🔹 Structures & Enums
- Using `struct` to model real-world entities (Client Data)
- Using `enum` to represent menu options clearly and safely

### 🔹 Vectors & Data Handling
- Using `vector<struct>` to manage dynamic collections
- Iterating over vectors
- Searching and updating elements

### 🔹 File Handling
- Reading data from text files
- Writing and rewriting files
- Simulating delete and update operations via file rewriting
- Converting between text lines and structured data

### 🔹 String Manipulation
- Splitting strings using custom delimiters
- Converting strings to numeric values (`stof`)
- Formatting output for clean console display

### 🔹 Input Handling
- Using `getline` safely
- Handling mixed input (`cin` + `getline`)
- Input validation and confirmation prompts

### 🔹 Console UI Design
- Menu-driven navigation
- Screen separation
- User-friendly prompts and messages
- Tabular data display using `iomanip`

---

## 🧪 Recommended Development Environment
For best experience:
- **Visual Studio (Windows)**

However, the project can be compiled using any standard C++ compiler that supports modern C++ standards.

---

## 📌 Important Notes
- This project is **educational**, not intended for production use
- Data persistence is file-based (no databases)
- The project represents a **major step** after mastering basic C++ problems
- You should start by choosing:
  - **[2] Add New Client**
  to create the data file initially

---

## 🙏 Acknowledgment
Special thanks to:
- **Programming Advices**
- **Professor Abouhodhoud**

for providing a strong learning path that focuses on **practical understanding**, **clean code**, and **real-world thinking**.

---

⭐ If you find this project helpful, feel free to star the repository and use it as a reference while building more advanced C++ applications.
