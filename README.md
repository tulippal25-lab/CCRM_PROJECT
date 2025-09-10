# Campus Course & Records Manager (CCRM)

## 🎯 Project Overview
Campus Course & Records Manager (CCRM) is a console-based Java SE application designed for institutes to manage:
- Students (Create, Update, Enroll/Unenroll in courses)
- Courses (Create, Update, Assign Instructors)
- Grades & Transcripts (Record marks, Compute GPA, Print transcripts)
- File Utilities (Import/Export CSV, Archive/Backup data)

This project demonstrates key Java concepts:
- Object-Oriented Programming (Encapsulation, Inheritance, Abstraction, Polymorphism)
- Design Patterns (Singleton, Builder)
- File I/O using NIO.2 and Streams API
- Exception Handling (Custom Exceptions)
- Date/Time API usage
- Enums for Semester and Grade
- Recursive utilities

---

## ✅ How to Run

### Requirements
- Java SE JDK 17 or newer
- Eclipse IDE (or command-line setup)

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/CCRM_Project.git
    ```
2. Open the project in Eclipse IDE or use terminal.

3. Compile and run:
    ```bash
    javac edu/ccrm/CCRMApp.java
    java edu.ccrm.CCRMApp
    ```

4. Follow the CLI menu for operations.

---

## ⚡ Minimum Demo Flow
1. AppConfig (Singleton) loads config (e.g., data folder path).
2. CLI menu options:
    - Manage Students, Courses, Enrollment, Grades
    - Import/Export Data
    - Backup & Show Backup Size (recursive)
    - Reports (e.g., GPA distribution)
    - Exit
3. Support for student enrollments, grades input, transcript display (via polymorphism).
4. Data export and backup (to timestamped folders).
5. Summary platform note: Java SE vs ME vs EE.

---

## ✅ Package Structure Example
