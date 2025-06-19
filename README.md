# 🏥 Doctor Appointment Management System

A responsive and user-friendly **Doctor Appointment Management System** built using **HTML, CSS, JavaScript, Bootstrap (Frontend)** and **PHP & MySQL (Backend)**. This system allows patients to book appointments online, doctors to manage their schedules, and administrators to oversee the entire workflow.

## 🚀 Features

- Doctor Management (Admin Panel): Add, update, or remove doctor profiles Assign specialties and available time slots

- Patient Management: Booking appointments,select doctorand specilization date, and time slot,tracking status.

- Appointment Management: Doctors can accept, decline, or reschedule appointments Patients can cancel or reschedule before the appointment time

## 👥 User Roles
- **Admin**: Manage doctors, patients, appointments, and system settings.
- **Doctor**: View schedule, manage availability, approve or decline appointments.
- **Patient**: Register, login, book, reschedule, or cancel appointments.

### 📋 Functionalities

- User authentication (login/register for doctors and patients)
- Appointment booking with date & time slot selection
- Check Booking Status
- Notifications
- Email confirmation (optional extension)
- Admin dashboard with appointment and user analytics
- Responsive UI using Bootstrap

## 🛠️ Tech Stack

| Layer       | Technology                      |
|------------|----------------------------------|
| Frontend   | HTML, CSS, JavaScript, Bootstrap |
| Backend    | PHP                              |
| Database   | MySQL                            |

## Setup Database

    Import the database.sql file into your MySQL server using phpMyAdmin or CLI.

    Update the database connection credentials in includes/db.php.

## Run the Project

    Start your Apache server (e.g., XAMPP or WAMP).

    Place the project folder in your server’s root directory (htdocs for XAMPP).

    Navigate to http://localhost/doctor-appointment-system in your browser.

  ##  📌 To-Do / Future Improvements

    Calendar view for doctor schedule

    File upload for prescriptions

    REST API for mobile app integration
