# Hospital Management System (HMS)

A comprehensive, web-based **Hospital Management System** designed to streamline hospital operations such as patient management, doctor scheduling, appointments, billing, and administrative control. The system provides a clean, user-friendly interface and efficient backend processing for reliable day-to-day hospital workflows.

---

## ✨ Features

* **User Authentication**: Secure login system for Admin, Doctors, and Patients
* **Patient Management**: Add, update, view, and manage patient records
* **Doctor Management**: Manage doctor profiles, departments, and availability
* **Appointment System**: Easy appointment booking and scheduling
* **Department Management**: Organize hospital departments efficiently
* **Medical Records**: Maintain patient diagnosis and treatment history
* **Billing System**: Generate and manage patient bills
* **Admin Dashboard**: Centralized control with statistics and reports
* **Responsive Design**: Works smoothly on desktop and mobile browsers

---

## 🛠 Tech Stack

### Frontend

* HTML5
* CSS3
* Bootstrap
* JavaScript

### Backend

* PHP (Core PHP)
* MySQL Database

### Server

* Apache (XAMPP)

---

## 🚀 Getting Started

### Prerequisites

* XAMPP (Apache + MySQL)
* Web Browser (Chrome, Edge, Firefox)
* Code Editor (VS Code recommended)

---

## 📥 Installation & Setup

1. **Download the project**

   * Clone the repository or download the ZIP file

2. **Extract the project**

   * Extract the folder and copy the project directory

3. **Move to XAMPP directory**

   ```
   C:\xampp\htdocs\hospital
   ```

4. **Start XAMPP**

   * Open XAMPP Control Panel
   * Start **Apache** and **MySQL**

5. **Create Database**

   * Open browser and go to:

     ```
     http://localhost/phpmyadmin
     ```
   * Create a database named:

     ```
     hms
     ```

6. **Import Database File**

   * Click the **Import** tab
   * Select the provided `hms.sql` file
   * Click **Go**

7. **Run the Project**

   * Open browser and go to:

     ```
     http://localhost/hospital
     ```

---

## 🔐 Default Login Credentials (Example)

### Admin

* **Username:** admin
* **Password:** admin123

*(Credentials may vary depending on database configuration)*

---

## 📂 Project Structure

```
Hospital-Management-System/
├── admin/                 # Admin dashboard and controls
├── doctor/                # Doctor panel and features
├── patient/               # Patient portal
├── assets/                # CSS, JS, images
├── includes/              # Database connection & common files
├── hms.sql                # Database file
├── index.php              # Main entry point
└── README.md              # Project documentation
```

---

## 🧑‍⚕️ User Roles

### Admin

* Manage doctors, patients, departments
* View reports and system statistics

### Doctor

* View appointments
* Manage patient medical records

### Patient

* Book appointments
* View medical history and bills

---

## 🎨 Design Highlights

* Clean and professional hospital-themed UI
* Bootstrap-based responsive layout
* Simple navigation and forms
* User-friendly dashboards

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 📞 Support

If you face any issues or have questions:

* Open an issue in the repository
* Contact the project maintainer

---

### Built with ❤️ to simplify hospital management
