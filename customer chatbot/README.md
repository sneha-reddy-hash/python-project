# 📁 File Organizer Automation System

## 📌 Project Overview

The **File Organizer Automation System** is a Python-based application that automatically organizes files into different folders based on their file extensions.

It helps users maintain a clean and organized directory by sorting files into categories such as Documents, Images, Videos, Audio, Archives, Code, Installers, and Others.

The application also includes logging functionality to track file movements, errors, and completed operations.

## ✨ Features

- **Automatic File Organization:** Organizes files based on their extensions.
- **Documents:** Sorts PDF, DOCX, TXT, PPTX, XLSX, and CSV files.
- **Images:** Organizes JPG, PNG, GIF, SVG, and other image files.
- **Videos:** Sorts MP4, MKV, AVI, MOV, and WMV files.
- **Audio:** Organizes MP3, WAV, AAC, FLAC, and OGG files.
- **Archives:** Sorts ZIP, RAR, 7Z, TAR, and GZ files.
- **Code Files:** Organizes Python, Java, C, C++, HTML, CSS, JavaScript, and SQL files.
- **Installers:** Sorts EXE, MSI, APK, and DEB files.
- **Duplicate File Protection:** Prevents overwriting files with the same name.
- **Error Handling:** Handles file operation errors.
- **Logging:** Records file movements and errors in a log file.
- **Final Report:** Displays the number of moved, failed, and skipped files.

## 🛠️ Technologies Used

- Python 3
- OS Module
- Shutil Module
- Logging Module
- Pathlib Module
- Datetime Module

## 📂 Project Structure

```text
File-Organizer/
│
├── main.py
├── organizer.log
└── README.md
```

**Note:** The `organizer.log` file is generated automatically when the application runs.

## ⚙️ Installation and Setup

### Step 1: Install Python

Download and install Python 3:

https://www.python.org/downloads/

### Step 2: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 3: Open the Project

Open the project folder in Visual Studio Code.

### Step 4: Run the Application

Open the terminal and execute:

```bash
python main.py
```

### Step 5: Enter Folder Path

When prompted, enter the folder path you want to organize.

Example:

```text
Enter the folder path to organize:
C:\Users\YourName\Downloads
```

**Tip:** Test the application using a sample folder first. It moves files into category folders inside the selected directory.

## 📊 File Categories

| Category | File Extensions |
|---|---|
| Documents | PDF, DOCX, TXT, PPTX, XLSX, CSV |
| Images | JPG, PNG, GIF, SVG, WEBP |
| Videos | MP4, MKV, AVI, MOV |
| Audio | MP3, WAV, AAC, FLAC |
| Archives | ZIP, RAR, 7Z, TAR |
| Code | PY, JAVA, C, CPP, HTML, CSS, JS |
| Installers | EXE, MSI, APK, DEB |
| Others | Unrecognized extensions |

## 🎯 Learning Outcomes

- Understanding Python file handling.
- Learning directory management using OS and Pathlib.
- Working with file movement using Shutil.
- Implementing exception handling.
- Understanding logging functionality.
- Automating repetitive file management tasks.
- Developing a practical Python automation project.

## 🚀 Future Enhancements

- Create a graphical user interface (GUI).
- Add file search functionality.
- Support automatic folder monitoring.
- Add custom file categories.
- Generate detailed organization reports.
- Add an undo option for file movements.

## 👩‍💻 Author

**Sneha Reddy Madduri**

## 📄 License

This project is developed for educational and learning purposes.
