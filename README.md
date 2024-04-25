# campus-recruitment-management-system
ABSTRACT
The Campus Requirement Management System (CRMS) is a specialized web-based application tailored for educational institutions, primarily universities and colleges, to efficiently manage their recruitment processes. Comprising three distinct modules - Admin, Employee, and Candidate - CRMS offers a cohesive platform for different user roles to interact seamlessly.
In the Admin Module, system administrators gain comprehensive control over user management, role assignments, system configurations, and the ability to generate detailed reports. This module acts as the backbone, ensuring smooth operations and facilitating informed decision-making.
The Employee Module serves as a bridge between the institution's recruitment team and potential candidates. Employees, typically faculty or HR staff, can post job vacancies, review applications, schedule interviews, and communicate updates to applicants, thereby streamlining the recruitment workflow.
On the other hand, the Candidate Module focuses on delivering a user-friendly experience to job seekers. Candidates can explore available job opportunities, submit their applications with necessary documents, track their application status, and receive timely notifications, making the application process transparent and interactive.
Technologically, CRMS leverages PHP for backend development, complemented by HTML, CSS, and JavaScript for frontend interfaces. MySQL serves as the database backend, ensuring robust and secure data storage. With Apache Server for deployment, the system is designed for scalability and reliability.
Overall, CRMS aims to simplify the recruitment process, reduce administrative burdens, and enhance the experience for all stakeholders involved, ultimately contributing to a more efficient and transparent recruitment ecosystem within educational institutions.


Features

Admin Module

•	User management: Add, edit, and delete users.
•	Role-based access control: Assign roles and permissions to users.
•	Configuration management: Customize application settings and parameters.
•	Reporting: Generate reports on recruitment activities, candidate statistics, etc.

Employee Module

•	Job posting: Create and publish job vacancies with detailed descriptions.
•	Candidate shortlisting: Review and shortlist candidates based on qualifications.
•	Interview scheduling: Schedule and manage interview appointments.
•	Communication: Send notifications and updates to candidates.

Candidate Module

•	Job search: View available job vacancies based on criteria.
•	Application submission: Apply for jobs by submitting required documents and information.
•	Application status tracking: Monitor the progress of submitted applications.
•	Communication: Receive notifications on application status updates.

Technologies Used

•	Backend: PHP
•	Frontend: HTML, CSS, JavaScript
•	Database: MySQL
•	Authentication: PHP sessions
•	Deployment: Apache Server

Installation and Setup

Prerequisites
•	PHP 7.x
•	MySQL
•	Apache Server
•	Web Browser

Steps

1.	Import Database
•	Create a MySQL database and import the crmsdb.sql file provided in the project.

3.	Start Apache Server
•	Make sure Apache Server is running.

5.	Access the Application
               http://localhost/crms

Installation steps in AZURE:

1. Clone the CRMS Repository
Clone the CRMS repository to your local machine using Git:
git clone https://github.com/sanjaySJJ/crms.git

2.Navigate to Project Directory:
Change into the project directory:
cd repository

3.Create Virtual Environment:
Set up a virtual environment for the project to manage dependencies:
$ sudo dnf update
$ sudo dnf install https://rpms.remirepo.net/enterprise/remi-release-9.rpm
$ sudo dnf module list php
$ sudo dnf module enable php:remi-<VERSION>
$ sudo dnf install php 
$ php -v 
Activate the virtual environment:
On macOS/Linux:
source venv/bin/activate
On Windows:
venv\Scripts\activate

4.Configure Azure Database
Create a MySQL Database
Log in to the Azure Portal.
Navigate to "Azure Database for MySQL" and create a new MySQL database.
Note down the connection details (server name, username, password, etc.).
Import Database Schema
Export the crmsdb.sql file from the CRMS project.
Import this file into your Azure MySQL database using Azure Database for MySQL Tools or Azure Data Studio.

Usage

1.	Admin Module
•	Log in to the admin panel.
•	Manage users, roles, and system configurations.
•	Generate reports as needed.

2.	Employee Module
•	Log in as an employee.
•	Post job vacancies, shortlist candidates, and schedule interviews.
•	Communicate with candidates through the platform.

3.	Candidate Module
•	Register and log in as a candidate.
•	Search and apply for job vacancies.
•	Track application status and receive notifications.

Contributing

THABRESH U
Role:Front end
Responsibilities:Create and maintain project front end(PHP,CSS,JAVASCRIPT,BOOTSTRAP)

ROGITH R
Role:Back end
Responsibilities:create and maintain project back end(PHP and MYSQL)

SANJAY B
Role:Deploy project
Responsibilities:To deploy a blood center project in azure cloud

PRANESH N
Role:Voice Over 
Responsibilities:Give step by step voice to guide the project

