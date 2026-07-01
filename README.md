# 🎓 Intelligent College Timetable Generator

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python" alt="Python Version">
  <img src="https://img.shields.io/badge/Flask-Web_App-black?style=for-the-badge&logo=flask" alt="Flask Framework">
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql" alt="MySQL Database">
  <img src="https://img.shields.io/badge/TailwindCSS-Frontend-38B2AC?style=for-the-badge&logo=tailwind-css" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Alpine.js-Interactive-8BC0D0?style=for-the-badge&logo=alpine.js" alt="Alpine.js">
  <br>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" alt="Project Status">
</p>

---

## 📖 Project Overview

The **Intelligent College Timetable Generator** is a comprehensive, web-based timetable management system designed to automate and streamline the complex process of academic scheduling. Built with Flask and MySQL, this application intelligently manages all academic resources—including departments, faculty, classrooms, subjects, and student schedules—to create optimal and conflict-free timetables.

The system features a modern, responsive interface and provides secure, role-based access for four distinct user types: **Administrator**, **Head of Department (HOD)**, **Faculty Members**, and **Students**. Each role has a tailored dashboard with specific functionalities to enhance the scheduling workflow.

---

## ✨ Key Features

### 👑 Administrator
- **Secure Authentication** with role-based access control
- **Manage Core Entities:** Create, read, update, and delete (CRUD) operations for Departments, Programs, Subjects, Faculty, HODs, Students, and Classrooms
- **Automated Timetable Generation:** One-click generation of a conflict-free timetable
- **Publish & Share:** Publish the final timetable for all users to view
- **Comprehensive Reporting:** View and export insightful reports on the academic schedule

### 👔 Head of Department (HOD)
- **Departmental Oversight:** View the full timetable for their specific department
- **Leave Management:** Approve or reject leave requests submitted by faculty members
- **Resource Allocation:** Manage and view faculty assignments within the department

### 👩‍🏫 Faculty Member
- **Personalized Timetable:** View a detailed timetable for their assigned classes
- **Leave Requests:** Submit leave requests for approval
- **Notifications:** Stay informed about schedule changes and leave status

### 🧑‍🎓 Student
- **Student Timetable:** View their personal class schedule
- **Real-time Notifications:** Receive updates and announcements

---

## 🎨 User Interface

The application boasts a modern, intuitive, and responsive user interface built with a focus on user experience.

- **Tailwind CSS** for a utility-first, highly customizable design
- **Font Awesome** for a rich set of scalable vector icons
- **AOS Animation** for smooth, engaging scroll animations
- **Glassmorphism UI** for a sleek, contemporary aesthetic
- **Animated Dashboard** to visualize key information at a glance
- **Responsive Navigation** that adapts seamlessly to any device

---

## ⚙️ Technology Stack

| Layer        | Technology / Library                                      |
| :----------- | :-------------------------------------------------------- |
| **Backend**  | Python, Flask Framework                                   |
| **Frontend** | HTML5, Tailwind CSS, JavaScript, Alpine.js                |
| **Database** | MySQL                                                     |
| **Libraries**| Flask-SQLAlchemy, Flask-Login, PyMySQL, Pandas, NumPy, python-constraint |

---

## 📂 Folder Structure


intelligent-college-timetable-generator/
├── app.py 
├── config.py 
├── requirements.txt
├── database.sql 
├── static/ 
├── templates/ 
│ ├── admin/ 
│ ├── faculty/ 
│ ├── student/ 
│ └── base.html 
├── controllers/ 
├── models/ 
├── screenshots/ 
└── README.md 

---

## 🚀 Quick Start (Installation)

Follow these steps to get the project up and running on your local machine.

### 1. Clone the Repository

git clone https://github.com/ribinpsamu/intelligent-college-timetable-generator.git
cd intelligent-college-timetable-generator


📸 Screenshots
(Screenshots of the application will be added here soon. Stay tuned!)

🔮 Future Enhancements
This project is designed for continuous improvement. Upcoming features include:

AI Timetable Optimization: Using machine learning to generate even more efficient schedules

Attendance Analytics Dashboard: Track and analyze student attendance

Mobile Application: Native mobile apps for students and faculty

Automated Email Notifications: Real-time alerts for schedule updates and approvals

Cloud Deployment: Deploy the application to platforms like AWS, Azure, or Heroku

Export Functionality: Timetable export as PDF or iCal files

👨‍💻 Developer
Ribin P Samu

MCA Student & Python Backend Developer

Kerala, India

GitHub: https://github.com/ribinpsamu

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

⭐ Support
If you find this project helpful and would like to support its development, please consider giving it a ⭐ on GitHub.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.



Made with ❤️ by Ribin P Samu
