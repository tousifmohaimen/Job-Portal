Job Portal
A responsive job portal that connects job seekers and employers, built using HTML, CSS, JavaScript, PHP, and MySQL.

Features
For Job Seekers:

Create and manage profiles
Browse and search for job listings
Apply for jobs online
Track application status
For Employers:

Register and manage company profiles
Post job openings
Review job applications
Contact shortlisted candidates
Admin Panel:

Manage users (job seekers and employers)
Monitor job postings and applications
Perform CRUD operations on data
Tech Stack
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL
Installation
Clone the Repository

bash
Copy code
git clone https://github.com/yourusername/job-portal.git
cd job-portal
Set Up the Database

Import the SQL file (job_portal.sql) into your MySQL database.
Update the database connection details in config.php:
php
Copy code
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "job_portal";
Configure the Project

Ensure your server supports PHP and MySQL.
Place the project in the web server's root directory (e.g., htdocs for XAMPP).
Run the Application

Start your server (e.g., XAMPP or WAMP).
Access the portal at http://localhost/job-portal.
