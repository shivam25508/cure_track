CureFit – Doctor Booking Application

Overview

CureFit is a full-featured Clinic Management System and Doctor Booking Application, built as a final project for the course Database Systems (CS203) during the 4th semester at National University of Computer and Emerging Sciences.
The system is based on a 3-Tier Architecture, offering seamless interaction between patients, doctors, and administrators with a clean, modern UI and robust database backend.

Technologies Used

Frontend: HTML, CSS, Bootstrap, JavaScript

Backend: C#, ASP.NET

Database: SQL Server

Pre-requisites

To run CureFit, ensure the following are installed:

Microsoft Visual Studio

Microsoft SQL Server Express

Microsoft SQL Server Management Studio (SSMS)

Interface Previews
Signup Page

Book Appointment

Current Appointments

Search Doctor / Staff

Core Functionalities
CureFit supports three major user types, each with specific features:

👨‍⚕️ Patient
Patient Dashboard – View profile, notifications, and appointments.

Book Appointment – Select department → doctor → free time slot → send booking request.

View Appointments – Track pending/approved appointments.

Treatment History – View medical and treatment history.

Billing History – Check previous visit invoices.

Notifications – Receive updates when doctors accept/reject bookings.

Feedback System – Rate completed appointments (1–5 stars).

Single Active Appointment Rule – Only one active appointment is allowed at a time.

🩺 Doctor
Doctor Profile – View personal and professional details.

Pending Appointments – Approve or reject incoming requests.

Today’s Appointments – Manage and update same-day bookings.

Medical History Access – View full treatment records of patients.

Prescription & Treatment Updates – Record prescriptions and patient progress.

Billing Module – Generate bills after treatment.

🧑‍💼 Administrator
Admin Dashboard – Overview of clinic stats: income, appointments, registered users, etc.

View Doctors/Patients/Staff – Complete profiles with search and filtering.

Search Staff – Quickly find a staff member by name.

Manage Users – Add/remove doctors, patients, and staff members.

How to Run
Install Requirements:

Visual Studio

SQL Server Express

SQL Server Management Studio (SSMS)

Setup Database:

Open SSMS → Connect to server:

yaml
Copy
Edit
Server Name: .\SQLEXPRESS  
Authentication: Windows Authentication
Run Schema.sql to create tables.

Then run: Admin.sql, Doctor.sql, Patient.sql, and Signup.sql.

Run Insertions.sql to populate test data (logins included).

Run Application:

Open Clinic Management System.sln in Visual Studio.

Set SignUp.aspx as the startup page.

Run via IIS Express.

Contact
📩 LinkedIn: [Insert Your LinkedIn Profile Link]
💻 GitHub: [Insert GitHub Profile Link]

If you found this helpful, please ⭐ star the repo and share it!

Contributions Welcome
Your contributions make CureFit better!

Report Bugs → Open an issue

Suggest Features → Use the Issues tab

Improve Codebase → Fork the repo and submit a pull request

Let’s collaborate to make CureFit the best open-source doctor booking system! 🚀
