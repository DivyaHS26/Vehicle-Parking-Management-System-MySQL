# 🚗 Vehicle Parking Management System
A complete web-based solution to manage vehicle parking efficiently. Built with **PHP** and **MySQL**, this system allows administrators to manage parking slots, track vehicle entries and exits, calculate charges, and handle user registrations.

## 📌 Features

- **Admin Panel**: Manage vehicles, view parking history, update status (In/Out), and set parking charges.
- **User Panel**: Register as a user, view current parking status, and check past parking records.
- **Vehicle Categories**: Support for multiple vehicle types (e.g., Two Wheeler, Four Wheeler, Bicycles).
- **Automatic Parking Number Generation**: Unique parking slot numbers for each vehicle.
- **Real-time Status**: Track whether a vehicle is currently parked or has exited.
- **Secure Authentication**: Password hashing for admin and users.
- **Responsive UI**: Built with Bootstrap 5 for mobile-friendly access.

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
- **Backend**: PHP (Core)
- **Database**: MySQL
- **Server**: Apache (XAMPP / WAMP / LAMP)

## 🚀 Installation Guide

Follow these steps to set up the project on your local machine:

### 1. Prerequisites
- PHP (>=7.4)
- MySQL (>=5.6)
- Apache Server (XAMPP / WAMP / LAMP recommended)

### 2. Download & Extract
- Download the project zip file.
- Extract the folder and rename it to `vpms` (if not already).
- Copy the `vpms` folder into your server's root directory:
  - **XAMPP**: `C:\xampp\htdocs\`
  - **WAMP**: `C:\wamp\www\`
  - **LAMP**: `/var/www/html/`

### 3. Create Database
### 3. Create Database
- Open phpMyAdmin: `http://localhost/phpmyadmin`
- Create a new database named `vpmsdb`.
- Import the SQL file:
  - Click on the `vpmsdb` database.
  - Go to the **Import** tab.
  - Choose the file `vpmsdb.sql` from the project folder.
  - Click **Go**.

## 4. Run the Application
Open your browser and go to: http://localhost/vpms/

## Database Schema Overview
* `tbladmin` :	Admin login details
* `tblcategory` :	Vehicle categories (e.g., 2 wheeler)
* `tblregusers` :	Registered users
* `tblvehicle` : Parking records with in/out times


## Happy Parking Management! 🚗💨
