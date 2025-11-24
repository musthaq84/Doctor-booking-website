Web-Based Hospital Management System — Full Extended Description
1. Introduction
The Web-Based Hospital Management System (HMS) is a comprehensive digital platform designed to streamline and automate various operations within a hospital or healthcare institution. This system provides an efficient environment for managing patient information, doctor schedules, hospital departments, appointments, diseases, medical records, and administrative tasks.
The system aims to replace traditional paper-based management with a centralized digital system, improving accuracy, accessibility, and performance. It is developed using HTML, CSS, JavaScript, and PHP, with MySQL as the backend database.
This HMS is suitable for clinics, medium-sized hospitals, diagnostic centers, and specialized healthcare units.
2. Key Objectives
Reduce paperwork and manual effort.
Provide an easy, accessible platform for doctors, staff, and patients.
Improve appointment and scheduling efficiency.
Maintain accurate digital medical records.
Provide user-level authentication for secure access.
Enable monitoring of critical metrics, such as patient count, departments, and disease records.
Integrate notification systems like SMS alerts for appointments and updates.
3. Core Features
 3.1 Online Appointment System
Patients can book appointments online.
Doctors can view upcoming visits.
Admin can approve, reschedule, or cancel appointments.
SMS/email notifications for booking confirmation.
 3.2 Patient Management System
Add & update patient records (Name, Age, Gender, Disease, Department).
Maintain appointment history & diagnosis reports.
Manage patient admission, discharge, and ward allocation.
Track treatment progress and prescribed medications.
 3.3 Doctor Scheduling & Management
Maintain doctor profiles.
Manage availability (daily/weekly slots).
Automatic conflict detection for overlapping appointments.
Doctor shift management.
3.4 Department Management
The system supports all major hospital departments:
General Medicine
Surgery
Radiology
Cardiology
Orthopedics
Diagnostics
Emergency
Pediatrics
Gynecology
Neurology
Admin can add new departments anytime.
 3.5 Disease Management Module
Contains detailed info about various diseases:
COVID-19
Tuberculosis
Cancer
Dengue
Malaria
Heart diseases
Skin infections
Fever, infections, chronic conditions
Special detail pages (e.g., disease1.html for COVID-19) include:
Symptoms
Causes
Prevention guidelines
Available treatments
Precautions for patients
 3.6 User Authentication & Roles
Different users have different permissions:
Admin → Full control (patients, staff, doctors, reports)
Principal / Hospital Head → Monitor reports
Faculty / Doctors → View schedules, patient files
Office Staff → Manage admission, payment, records
Students / Interns → Learning-based limited access
 3.7 Dashboard (index1.html)
A centralized dashboard summarizing:
Total number of patients
Active doctors
Departments
Today’s appointments
Notifications
Emergency alerts
 3.8 Feedback & Grievance Module
Patients can submit feedback.
Complaints can be registered for follow-up.
Admin receives notifications for all grievances.
 3.9 SMS Integration
Automated SMS alerts for:
Appointment confirmation
Doctor availability
Test results uploaded
Emergency notifications
4. Technologies Used
Frontend
HTML5 – structure of the webpages
CSS3 – styling using style1.css
JavaScript (main.js) – dynamic interactions, validations
Backend
PHP (patient1.php, display.php, etc.)
MySQL Database (patient table + others)
Server Environment
XAMPP / WAMP / LAMP / MAMP
5. Project Directory Structure (Extended Version)
|-- index1.html          # Main Dashboard (home page)
|-- basics.html          # Introductory information
|-- about.html           # About the hospital + Contact info

|-- department.html      # All hospital departments
|-- disease.html         # Disease list
|-- disease1.html        # COVID-19 description (disease details page)

|-- patient.html         # Patient registration form
|-- display.php          # Displays patient data from DB
|-- patient1.php         # Backend logic for inserting patient data

|-- main.js              # JavaScript file (menu, form validation, alerts)
|-- style1.css           # Global stylesheet

|-- link.html            # Shortcut links to important pages
|-- assets/              # Images, icons, logos
|-- php/                 # Additional PHP scripts (login, update, delete)
|-- db/                  # SQL database files (optional)

6. How the System Works (Workflow)
Step 1 — User logs in
Depending on the role (Admin/Doctor/Staff), the dashboard options change.
Step 2 — Patient Registration
Patient info is stored in the patient database via patient1.php.
Step 3 — Appointment Booking
Patient selects doctor, disease type, date, and time.
System prevents overlapping bookings.
Step 4 — Doctor Management
Doctors can:
View appointment lists
Update treatment notes
Check schedules
Step 5 — Display Data
display.php shows stored patient data in a table with:
Patient ID
Name
Age
Gender
Disease
Department
Contact info
Step 6 — SMS/Notifications
Automatic messages sent via integrated SMS API.

7. Database Structure (Extended)
patient Table
Field	Type	Description
pid	INT (PK)	Unique patient ID
pname	VARCHAR	Patient full name
age	INT	Age of the patient
gender	VARCHAR	Male/Female/Other
disease	VARCHAR	Patient’s disease
department	VARCHAR	Department assigned
phone	BIGINT	Contact number
address	TEXT	Full address
date	DATE	Registration date
More tables can be added:
doctors
appointments
departments
login
complaints
8. How to Run the Project (Expanded Guide)
Step 1 — Install XAMPP/LAMP/MAMP
Start Apache and MySQL.
Step 2 — Place Project Folder
Copy your project folder to:
C:/xampp/htdocs/hms/
Step 3 — Create Database
Open phpMyAdmin, then:
Database Name: patient
Import or run the SQL file from patient1.php.
Step 4 — Run the Application
Go to browser and open:
http://localhost/hms/index1.html
Step 5 — Explore Modules
Patient Registration
Display Patients
View Departments
View Diseases
Appointment Booking
Dashboard
9. Advantages of the System
✔ Cuts down paperwork
✔ Saves time for hospital staff
✔ Accurate record maintenance
✔ Easy retrieval of data
✔ Improves doctor-patient communication
✔ Scalable and customizable
✔ Accessible from any device
10. Future Enhancements (Detailed)
Online payment integration
AI-based appointment prediction
Voice-based patient search
Medical image storage
Online prescription and e-pharmacy
Chatbot for patient queries
Integration with Aadhar/Health ID
Analytics dashboard for admin
11. Conclusion
This Web-Based Hospital Management System provides a complete platform for digitizing hospital operations. It enhances efficiency, reduces workload, and ensures smooth coordination between different departments. It is scalable and can be customized for small clinics as well as large hospitals.
