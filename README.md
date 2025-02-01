# 🎓 CollegeSpace - College Resource Management System

## 📌 Overview
This project is a **PHP & MySQL-based College Resource Management System**, providing a centralized platform for students to access **notes, exam papers, syllabus, and notices**. It follows a **dynamic web-based architecture** built with **PHP, MySQL, Bootstrap, and jQuery**.

### 🎯 Features
✅ User-friendly college resource portal  
✅ Access to **exam papers, notes, syllabus, and notices**  
✅ **Bootstrap-powered UI** for responsive design  
✅ **MySQL database integration** for content storage  
✅ Secure database connection via **connect_db.php**  
✅ jQuery-powered interactive elements  
✅ Easy-to-deploy PHP-based system  

---

## 📂 Project Structure
```
collegespace/
│── CollegeSpace/
│   ├── index.php                # Homepage
│   ├── contactus.php            # Contact Us Page
│   ├── adminpage.php            # Admin Dashboard
│   ├── ExamPaper.php            # Exam Papers Section
│   ├── Notes.php                # Notes Section
│   ├── Notices.php              # College Notices
│   ├── Sysllabus.php            # Syllabus Section
│   ├── connect_db.php           # Database Connection
│   ├── Navbar.php               # Navigation Bar
│   ├── Footer.php               # Footer Section
│── sql_database/
│   ├── collegespace.sql         # SQL Database Script
│── assets/
│   ├── mystyle.css              # Custom CSS Styles
│── JQuery/
│   ├── jquery-3.3.1.js          # jQuery Library
│   ├── jquery-3.4.1.min.js      # jQuery Library
│── bootstrap-4.3.1-dist/
│   ├── css/                     # Bootstrap Stylesheets
│   ├── js/                      # Bootstrap Scripts
│── uploads/
│   ├── (Uploaded Files Section) # Storage for user-uploaded files
```

---

## 🛠️ Installation & Setup
### Prerequisites
- Install **XAMPP/WAMP/LAMP** for PHP & MySQL support
- A web browser (Chrome, Firefox, etc.)
- A text editor (VS Code, Sublime, etc.)

### 🚀 Running the Application
1. Download and extract the project files.
2. Move the extracted **CollegeSpace** folder to your **XAMPP/WAMP/LAMP** `htdocs` directory.
3. Start Apache & MySQL services from XAMPP/WAMP/LAMP.
4. Open **phpMyAdmin** and create a new database named `collegespace`.
5. Import the database:
   ```sh
   Import `sql_database/collegespace.sql` into `collegespace`
   ```
6. Open your browser and navigate to:
   ```sh
   http://localhost/CollegeSpace/index.php
   ```

---

## 🏗️ Future Enhancements
🔹 Implement **user authentication (login & registration)**  
🔹 Add **search functionality** for notes and exam papers  
🔹 Improve UI with **modern styling** and animations  
🔹 Introduce an **admin dashboard** for better content management  

---

## ✉️ Contact
For any queries, reach out to:
- **Vennela Kothakonda** - Developer

---

Happy Coding! 🚀
