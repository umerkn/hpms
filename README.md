# Hospital Patient Management System (HPMS)

## 📚 Course Information

- **Course Name:** Programming Fundamentals
- **Course Code:** AI-133
- **Semester:** Spring 2025
- **Instructor:** Mr. Muhammad Usman Yousaf

## 👥 Group Members

- Amna
- Haider
- Rehman
- Umer

## 🏥 Project Description

HPMS is a console-based Hospital Patient Management System developed in C++ for managing patient records. It allows registration, searching, updating, and categorizing patients based on medical symptoms. Originally developed for Windows, this project has been adapted to run cross-platform on **Linux**, **macOS**, and **Windows** consoles.

## 💡 Features

- Register new patients
- Search patients by CNIC
- Update existing records
- Delete patients by CNIC
- Show categories based on symptoms
- List all patients
- Persistent storage using `patients.txt`

## 🖥 Cross-Platform Console

- Works on **Linux**, **macOS**, and **Windows**
- Uses standard C++ with ANSI escape codes for color on Unix-based systems and `windows.h` on Windows
- No external dependencies or GUI frameworks

## 🛠 Technologies Used

- Language: **C++17**
- Build Tools: `g++`, `clang++`, MSVC
- Persistence: Plain text file (`patients.txt`)
- Terminal coloring: ANSI escape sequences / `windows.h` (conditionally)

## 🚀 How to Compile and Run

### 🐧 On Linux/macOS

    g++ -o hpms src/hpms.cpp
    ./hpms

### 🪟 On Windows (e.g., CMD or PowerShell)

    g++ -o hpms.exe src/hpms.cpp
    hpms.exe

> 📌 Ensure `patients.txt` exists in the `src/` directory for data to persist.

## 🖼 Screenshot

Main menu of HPMS:

![Main Menu Screenshot](images/screenshot.png)

## 📂 Project Structure

    hpms/
    ├── src/
    │   ├── hpms.cpp
    │   └── patients.txt
    ├── docs/
    │   ├── HPMS_Report.pdf
    │   └── HPMS_Presentation.pptx
    ├── images/
    │   └── screenshot.png
    └── README.md

## 📎 Additional Materials

- 📄 [`HPMS_Report.pdf`](docs/HPMS_Report.pdf) – Final project report
- 🎞 [`HPMS_Presentation.pptx`](docs/HPMS_Presentation.pptx) – Course presentation

> ⚠️ **Note:**  
> The report and presentation reflect an earlier version of the project.  
> The current version includes improvements such as cross-platform compatibility and refactored terminal UI.

## 📄 License

This project is **open-source** and released under the **MIT License**.  
Feel free to use, modify, and distribute it for educational or personal use.
