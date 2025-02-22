# Hospital Management System
mini project using xampp

## 📌 Project Overview
The **Hospital Management System** is a web-based application designed to efficiently manage hospital operations such as patient records, doctor appointments, billing, and staff management. The backend is built using **PHP and MySQL**, hosted on **XAMPP**, while the frontend is pulled from a **Git repository**.

---

## 🚀 Features
- **Patient Management**: Register, update, and manage patient details.
- **Doctor Management**: Schedule, assign, and manage doctor appointments.
- **Staff Management**: Maintain staff records and roles.
- **Billing System**: Generate invoices and manage payments.
- **Admin Panel**: Control and manage all system users and hospital data.
- **User Authentication**: Secure login for patients, doctors, and admin.
- **Database Management**: MySQL database for data storage.

---

## 🛠️ Tech Stack
### Backend:
- PHP
- MySQL
- XAMPP (Local Server)

### Frontend:
- HTML / CSS / JavaScript
- Pulled from Git repository

---

## ⚙️ Installation Guide

### Prerequisites:
- Install [XAMPP](https://www.apachefriends.org/index.html)
- Install [Git](https://git-scm.com/)

### Steps:
1. **Clone the Frontend Repository**
   ```bash
   https://github.com/arkprocoder/Hospital-Management-System-dbmsminiproject/tree/main/hospital%20system/PROJECT
   ```
2. **Move the Project to XAMPP htdocs**
   ```bash
   mv hospital-management /xampp/htdocs/
   ```
3. **Start Apache and MySQL in XAMPP**
4. **Import the Database**
   - Open [phpMyAdmin](http://localhost/phpmyadmin/)
   - Create a new database (e.g., `hospital_db`)
   - Import `hospital_db.sql` file from the project
5. **Configure Database Connection**
   - Edit `config.php` with the correct MySQL credentials:
   ```php
   $servername = "localhost";
   $username = "root";
   $password = "";
   $dbname = "hospital_db";
   ```
6. **Run the Application**
   - Open the browser and go to:
     ```
 http://127.0.0.1:5000
     ```

---

## 📜 Usage Instructions
- **Admin Login**: `admin@example.com / admin123`
- **Doctor Login**: Credentials provided by admin
- **Patient Registration**: Register and book appointments

---

## 📌 Future Enhancements
- API integration for telemedicine
- AI-based appointment scheduling
- Cloud database support


