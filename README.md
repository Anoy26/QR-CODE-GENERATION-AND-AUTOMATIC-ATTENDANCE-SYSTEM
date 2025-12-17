# QR Code Generation and Automatic Attendance System

Built with PHP, MySQL, HTML, CSS, JavaScript

# 📌 Overview

This project is an Admission Test Management System that generates QR codes for students and provides an automatic attendance system using QR code scanning. The purpose is to reduce manual errors, time consumption, and the hassle of verifying student information during university admission tests.

The system includes:
- Student Registration & Profile Management
- Admin Login System
- QR Code Generation for Student Information
- Admit Card with Two QR Codes
- Automated Attendance via QR Code Scanner
- MySQL Database Connectivity
- Display & Manage Student Records

# 🚀 Features
***✔️ Student Panel***
Sign-up / Login
Profile creation & editing
Admission registration
Downloadable admit card with:
Profile photo
Exam roll
QR Code (info)
QR Code (attendance)

***✔️ Admin Panel***
Login system
View all student information
Monitor attendancea
Manage database records

***✔️ System Functionalities***
Store all data in MySQL database
Generate two unique QR codes:
Information QR – contains full student details
Attendance QR – contains exam roll only
Automatic attendance system using QR scanner
Organized database for student profiles, registrations, and attendance records

# 🛠️ Technologies Used
-HTML5	
-CSS3	
-JavaScript	
-PHP	
-MySQL	
-phpqrcode Library

# 📂 System Modules
***1️⃣ Profile Creation***
Student signs up using a registration form
Data stored in student_info table
Login using User ID + email

***2️⃣ Admission Registration***
Student fills the admission form
Data stored in registration_info table

***3️⃣ QR Code Generation***
Using phpqrcode/qrlib.php, system generates:
QR 1: All student information
QR 2: Only exam roll
Stored inside the qr table.

***4️⃣ Admit Card Generation***
The admit card includes:
Student photo
Exam roll
Unit
Two QR codes

***5️⃣ Attendance System***
Invigilator scans QR code using a specified scanner.
Attendance automatically saved in the attendance_info table.

# 🔄 Workflow (Simplified)

1.Open website
2.Student creates a profile
3.Student logs in
4.Student fills the admission form
5.System stores all data in MySQaL
6.System generates two QR Codes
7.System creates student admit card
8.Invigilator scans QR code for attendance
9.Attendance stored automatically

# Output
***Landing Page***
<img width="1430" height="682" alt="Picture1" src="https://github.com/user-attachments/assets/e3d87280-c67a-4c3c-a623-0ff7ffe42d93" />
***Clicking Sign-up Button***
<img width="1430" height="669" alt="Picture2" src="https://github.com/user-attachments/assets/c6c20a3c-1810-43bd-b60c-62322a4ba4f3" />
***Sign-up***

<img width="468" height="261" alt="Picture3" src="https://github.com/user-attachments/assets/0c29879c-b230-4d30-9368-8e0b6204b7ed" />

***Profile Created***
<img width="1430" height="744" alt="Picture4" src="https://github.com/user-attachments/assets/42f499e1-8b2c-40d1-b043-04acbda01361" />
***Log in***
<img width="1430" height="666" alt="Picture5" src="https://github.com/user-attachments/assets/31a35c50-e509-47a1-a292-1ed2b33f2b1d" />
***Registration***
<img width="468" height="252" alt="Picture6" src="https://github.com/user-attachments/assets/13e84eaa-1563-4439-8256-04c51a21e332" />
***Displaying Students information***
<img width="468" height="204" alt="Picture7" src="https://github.com/user-attachments/assets/ad1b50cb-1682-47fc-ac20-7affb7ddd8ce" />
<img width="468" height="194" alt="Picture8" src="https://github.com/user-attachments/assets/f022794a-9896-4883-931e-f95dbbd6280c" />
***Admit Card***
<img width="468" height="250" alt="Picture9" src="https://github.com/user-attachments/assets/2f0db4ff-57e0-4b81-851a-223520a3def9" />
***Scanning QR Code for Automatic Attendance***
<img width="624" height="492" alt="Picture10" src="https://github.com/user-attachments/assets/b1ea935a-426c-47e6-aa46-7000a897b93b" />
![Picture11](https://github.com/user-attachments/assets/393177e3-feb5-4a84-88ba-adf3689da2e2)
<img width="1430" height="743" alt="Picture12" src="https://github.com/user-attachments/assets/4168019e-cec7-44b2-945f-01f42f0420eb" />
