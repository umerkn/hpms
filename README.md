# Hospital Patient Management System (HPMS)

## 📘 Course Info

- **Course:** Programming Fundamentals
- **Code:** AI-133
- **Semester:** Spring 2025
- **Instructor:** Mr. Muhammad Usman Yousaf

## 👥 Group Members

- Amna
- Haider
- Rehman
- Umer

## 🏥 Project Overview

A simple console-based Hospital Patient Management System in **C++**. It allows registering patients, searching by CNIC, updating, deleting, categorizing based on symptoms, and listing all records. Patient data is saved to a text file.

## 🔧 Features

- Register new patients
- Search patients by CNIC
- Update existing patient records
- Delete patient by CNIC
- Categorize based on symptoms
- List all patients
- Data saved to `patients.txt`

## 🖥 Platform Compatibility

- Works on **Windows**, **Linux**, and **macOS** terminals
- Uses platform-specific color support:
  - `windows.h` on Windows
  - ANSI escape codes on Linux/macOS
- No external libraries used

## 🛠 How to Compile

### Linux/macOS

```bash
g++ -o hpms hpms.cpp
./hpms
```

### Windows (MinGW or cmd)

```bash
c++ hpms.cpp -o hpms.exe
hpms.exe
```

> Make sure `patients.txt` exists in the same folder for data to be saved.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
