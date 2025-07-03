# Hospital Patient Management System (HPMS)

## 📚 Course Information

- **Course:** Programming Fundamentals
- **Course Code:** AI-133
- **Semester:** Spring 2025
- **Instructor:** Mr. Muhammad Usman Yousaf

## 👥 Group Members

- Amna
- Haider
- Rehman
- Umer

## 🏥 Project Description

**HPMS** is a console-based Hospital Patient Management System written in **C++**. It allows you to register, search, update, delete, and categorize patient records. The program uses a plain text file for saving data between sessions.

This project runs on **Windows**, **Linux**, and **macOS**, and uses basic console features (no GUI or external libraries).

## 💡 Features

- Register new patients
- Search by CNIC
- Update existing records
- Delete patients
- Categorize by symptom
- List all patients
- Save/load from `patients.txt`

## 🖥 Cross-Platform Support

- Runs in any terminal (CMD, Bash, etc.)
- Uses:
  - ANSI escape codes for Linux/macOS
  - `windows.h` for Windows console colors

## 🚀 How to Compile and Run

### 🐧 Linux/macOS

```bash
g++ hpms.cpp -o hpms
./hpms
```

### 🪟 Windows

```bash
c++ hpms.cpp -o hpms.exe
hpms.exe
```

> 📌 Make sure `patients.txt` is in the same folder as your `.exe` or `.out` file to load and save patient data.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
