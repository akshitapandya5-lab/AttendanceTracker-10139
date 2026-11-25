# AttendanceTracker-10139
# Attendance Tracker System

A menu-driven **Java DSA project** to record, display, search, and sort student attendance.

## Features
- Enter student IDs and names.
- Mark attendance for a selected student and day.
- Display attendance percentages.
- Search students by ID using `HashMap`.
- Sort students by attendance using Bubble Sort.

## DSA Concepts
| Concept | Use |
|---|---|
| 1D Arrays | Store student IDs and names |
| 2D Array | Store daily attendance |
| HashMap | Map Student ID to array index |
| Searching | Find a student by ID |
| Bubble Sort | Sort attendance in descending order |

## Technologies
- Java (JDK 8 or later)
- HTML5 and CSS3 for the static project webpage
- VS Code / any Java IDE

## Project Structure
```text
AttendanceTracker-GitHub/
├── AttendanceTracker.java
├── README.md
└── web/
    ├── index.html
    └── style.css
```

## Run the Java Program
1. Install JDK 8 or later.
2. Open the project folder in a terminal.
3. Compile: `javac AttendanceTracker.java`
4. Run: `java AttendanceTracker`

## Attendance Values
- `1` = Present
- `0` = Absent

Attendance percentage = `(Present Days / Total Days) * 100`

## Notes
- Records are stored in memory and are lost when the program exits.
- Use a unique ID for every student.
- Unmarked attendance entries start at `0` and are counted as absent.
- The HTML/CSS page is a static project overview and is not connected to the Java console program.

## Future Improvements
- Permanent storage using files or a database.
- Monthly attendance reports.
- Teacher/admin login.
- GUI connected to the Java application.

## Author
**Akshita Pandya**

