# Student Management System

## Overview
This project is a Student Management System built using Flask (Python 3.7) for the backend and HTML, CSS, JavaScript, and Bootstrap for the frontend. It leverages SQLAlchemy for database management.

## Features
- **User Authentication**: Allows students, teachers, and administrators to log in with their respective credentials.
- **Student Profile Management**: Students can view and update their personal information such as name, contact details, and address.
- **Course Management**: Teachers and administrators can add, update, and delete courses. Students can view their enrolled courses.
- **Grade Management**: Teachers can assign grades to students for various assignments, exams, and projects.
- **Attendance Tracking**: Teachers can mark attendance for students in their courses.
- **Search Functionality**: Users can search for students, courses, grades, etc., using various search criteria.
- **Responsive Design**: The user interface is designed to be responsive, ensuring a seamless experience across different devices.

## Installation
1. Clone the repository:

git clone https://github.com/Muzammil0777/Student-Management-System.git

2. Navigate to the project directory:
cd Student-Management-System

3. Install Python 3.7 if not already installed.
4. Install Flask and other dependencies:
The following are the dependencies required:
Flask==1.1.2
Flask-Mail==0.9.1
Flask-SQLAlchemy==2.4.3
future==0.18.2
Jinja2==2.11.2
jmespath==0.9.5
Js2Py==0.70
MarkupPy==1.14
MarkupSafe==1.1.1
mysqlclient==2.0.1
Naked==0.1.31
packaging==20.4
Pillow==7.1.1
pipenv==2018.11.26
pipwin==0.5.0
pyttsx3==2.90
pytz==2020.1
pywin32==228
SQLAlchemy==1.3.17
sqlparse==0.3.1


5. Set up MySQL database:
- Create a MySQL database named `student_management_system`.
- Import the SQL schema provided in `database/schema.sql` to create the necessary tables.
- Update the database configuration in `config.py` with your MySQL credentials.

## Usage
1. Start the Flask server:
python app.py

2. Open a web browser and go to `http://localhost:5000` to access the application.
3. Log in with the provided credentials or create a new account if you're a new user.
4. Explore the various functionalities available in the system.

## Acknowledgements
- This project was built using Flask, a lightweight WSGI web application framework in Python.
- Frontend design and styling were done using HTML, CSS, JavaScript, and Bootstrap.
- Data persistence and retrieval were managed using SQLAlchemy.
