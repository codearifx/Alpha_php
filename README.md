<<<<<<< HEAD
# Alpha Royal Hotel - Room Reservation System

The **Hotel Room Reservation System** is a web-based application developed using PHP, HTML/CSS, SQL, and JavaScript. It allows users to conveniently book, modify, or cancel room reservations at the Alpha Royal Hotel over the Internet. It also includes an admin panel to manage the hotel operations.

## Features
- **Booking Rooms:** Search for available rooms based on check-in/check-out dates, room type, and number of guests.
- **Modifying Reservations:** Update existing booking details (dates, room upgrades) dynamically.
- **Canceling Reservations:** Cancel existing bookings directly from the user dashboard.
- **Admin Dashboard:** Manage rooms, view reservations, and handle customer data.

## Technology Stack
- **Frontend:** HTML5, CSS3 (Bootstrap 3), JavaScript (jQuery)
- **Backend:** PHP (Core)
- **Database:** MySQL (SQL)

---

## Installation & Setup Guide

Follow these steps to run the project locally on your machine using **XAMPP**.

### Step 1: Start XAMPP Services
1. Open your **XAMPP Control Panel**.
2. Start the **Apache** service (runs the web server for PHP).
3. Start the **MySQL** service (runs the database server).

### Step 2: Set Up the Database
This project requires a database to store users, rooms, and reservations.
1. Open your web browser and go to: `http://localhost/phpmyadmin/`
2. Click on the **Databases** tab.
3. In the "Create database" field, type **`hotel`** and click **Create**.
4. Select the newly created `hotel` database from the left sidebar.
5. Click on the **Import** tab at the top.
6. Click **Choose File** and locate the `hotel.sql` file inside the project directory:
   `database/hotel.sql`
7. Scroll down and click **Import** (or "Go").

> **Note:** The database credentials are set inside `connection.php`. If you are using default XAMPP settings (username: `root`, password: `<blank>`), you do not need to change anything in this file.

### Step 3: View the Project
1. Open your web browser.
2. Navigate to the project URL:
   `http://localhost/resort/Resort-Room%20Booking-Reservation-System/`

---

## Admin Credentials
To access the backend administration panel, you can use the following default credentials provided in the system:

- **Admin Username:** `adminakshay@gmail.com`
- **Password:** `1234`
=======
# Alpha_php
A web-based Hotel Room Reservation System built with PHP, MySQL, HTML, CSS, and JavaScript that allows users to book, modify, and cancel hotel rooms online.
>>>>>>> 2cf5b8735f22eba66266090c7730988e5e9ea33d
