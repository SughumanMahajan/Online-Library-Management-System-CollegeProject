# Online Library Management System

This project is an **Online Library Management System** developed by Sughuman Mahajan and Tushar Singh. The system is designed to automate the process of managing a library's resources, including books, users, and borrowing activities.

## Project Overview

The Online Library Management System (OLMS) is a web-based application developed using **PHP** and **MySQL** for the back-end, and **HTML**, **CSS**, and **JavaScript** for the front-end. The system provides an interface for both library administrators and users (students) to perform various library-related operations.

## Features

### User Features:
- **User Registration and Login**: Users can register and log in to the system to access library resources.
- **Book Issuing**: Users can issue books online, view the list of books they have issued, and check their due dates and fines.
- **Profile Management**: Users can update their profile information and change their passwords.

### Admin Features:
- **Admin Dashboard**: The admin can manage book categories, update book records, and handle user registrations.
- **User Management**: The admin can view and manage all registered users.
- **Book Management**: The admin can add new books, update existing ones, and track issued books.
- **System Updates**: The admin can update the system regularly to maintain its efficiency.

## System Requirements

### Software Requirements:
- **WAMP/XAMPP/LAMP/MAMP**: A software stack that includes Apache, MySQL, and PHP.
- **Visual Studio Code**: A source code editor for Windows, Linux, and macOS.

### Hardware Requirements:
- **Processor**: Intel Core i3 or above.
- **RAM**: 4GB or more.
- **System Type**: 64-bit Operating System, x64-based processor.

### Database Requirements:
- **MySQL Server 5.0** or later (included in XAMPP/WAMP/LAMP/MAMP).

### Web Server:
- **Apache HTTP Server 2.2** or later (included in XAMPP/WAMP/LAMP/MAMP).

## Installation Guide

### Kindly Extract The Files First as The Shared Content is in a Zip File

### 1. Clone the Repository
```bash
git clone https://github.com/SughumanMahajan/online-library-management-system-collegeproject.git
cd online-library-management-system-collegeproject
```

### 2. Set Up the Environment
- Install **WAMP/XAMPP/LAMP/MAMP** depending on your operating system.
- Start the Apache and MySQL servers.

### 3. Configure the Database
- Open `phpMyAdmin` from your WAMP/XAMPP/LAMP/MAMP control panel.
- Create a new database named `library`.
- Import the SQL file provided in the `database` directory into the `library` database.

### 4. Configure the Project
- Update the database configuration in the PHP files if needed (usually located in a configuration file).

### 5. Run the Project
- Place the project folder inside the `www` directory (for WAMP) or `htdocs` (for XAMPP).
- Open a web browser and navigate to `http://localhost/library` to access the system.

## Admin Credentials
- **Username**: `admin`
- **Password**: `1234`

## Future Scope
- Integration of eBook downloads.
- Enhanced user notification system via email and SMS.
- Expansion of book categories and management features.

## Authors
- **Sughuman Mahajan** - [GitHub Profile](https://github.com/SughumanMahajan)
- **Tushar Singh**
