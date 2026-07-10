\# Attendance Automation System using UiPath



\## Project Overview



Attendance Automation System is an RPA-based project developed using UiPath to automate the attendance management process.



The system reads student attendance data from an Excel file, analyzes attendance percentage, generates attendance reports, converts them into PDF format, and sends notifications through email.



\## Technologies Used



\- UiPath Studio

\- Robotic Process Automation (RPA)

\- Excel Automation

\- PDF Generation

\- Email Automation



\## Features



\- Reads attendance details from Excel

\- Processes student attendance automatically

\- Identifies low attendance students

\- Generates attendance reports

\- Converts reports into PDF

\- Sends reports through email



\## Workflow



1\. Import attendance data from Excel

2\. Process student records using UiPath workflow

3\. Check attendance percentage

4\. Generate attendance report

5\. Convert report into PDF

6\. Send email notification



\## Project Structure



```text

Attendance-Automation-UiPath

│

├── Main.xaml

├── project.json

├── attendance.xlsx

├── AttendanceReport.pdf

├── Screenshots

│   ├── workflow.png

│   ├── attendance\_input.png

│   ├── report.png

│   └── email.png

│

└── README.md

```

## Screenshots

### 1. UiPath Workflow

This workflow reads attendance data from Excel, processes each student's attendance, generates a report, converts it to PDF, and sends it via email.

![Workflow](Screenshots/workflow.png)

---

### 2. Attendance Excel Input

The automation reads student attendance records from an Excel file.

![Attendance Input](Screenshots/attendance_input.png)

---

### 3. Generated Attendance Report

After processing the data, the bot generates a formatted attendance report highlighting students with low attendance.

![Attendance Report](Screenshots/report.png)

---

### 4. Email Notification

Finally, the generated PDF report is automatically sent to the configured email address.

![Email Notification](Screenshots/email.png)
