# University Database Management System

## Project Overview

The University Database Management System is a comprehensive web application built using the Python Flask framework for backend operations, with MySQL as the database. The frontend is developed using HTML, CSS, and JavaScript. This system provides a centralized platform for managing university-related data, including student information, teacher details, course administration, and timetable management.

## Features

- **User Authentication**: Secure login system for administrators, teachers, and students
- **Admin Dashboard**: Centralized control panel for managing all university data
- **Student Management**: Create, view, and manage student profiles and records
- **Teacher Management**: Handle teacher information and course assignments
- **Course Administration**: Create and manage university courses
- **Timetable System**: Generate and view schedules for students and teachers
- **Profile Management**: Individual profile pages for students and teachers

## Technology Stack

- **Backend**: Python with Flask framework
- **Frontend**: HTML5, CSS3, JavaScript
- **Database**: MySQL
- **Server**: Flask development server (can be deployed to production servers)

## File Structure Explanation

```
UNIVERSITY-DATA-BASE/
│
├── assets/ - Contains all static assets and images
│   ├── collegebg.jpeg - Background image for college-related pages
│   ├── loginbg.jpeg - Background image for login page
│   ├── search.png - Search icon image
│   ├── studentbg.jpeg - Background for student pages
│   ├── teacherbg.jpeg - Background for teacher pages
│
├── Backend/ - Contains all backend logic and server files
│   ├── app.py - Main Flask application file (entry point)
│   ├── javascript/ - Folder for JavaScript files
│   │   └── script.js - Main JavaScript file for client-side functionality
│   ├── static/ - Contains all static CSS files
│   │   ├── admin.css - Styles for admin interface
│   │   ├── adminReg.css - Styles for admin registration
│   │   ├── auth.css - Authentication page styles
│   │   ├── sstyles.css - Secondary styles file
│   │   ├── styles.css - Main styles file
│   │   ├── tempCodeRunnerFile.css - Temporary styles (can be removed)
│   │   └── timetable.css - Styles for timetable pages
│   │
│   └── templates/ - Contains all HTML templates
│       ├── admin/ - Admin-specific templates
│       │   ├── admin dashboard.html - Main admin control panel
│       │   ├── create course.html - Form for creating new courses
│       │   ├── create student.html - Form for adding new students
│       │   ├── create teacher course.html - Form for assigning courses to teachers
│       │   ├── create teacher.html - Form for adding new teachers
│       │   ├── create TimeTable.html - Form for creating timetables
│       │   ├── login.html - Admin login page
│       │   └── manageStudents.html - Interface for managing student records
│       │
│       ├── student/ - Student-specific templates
│       │   ├── student subject.html - Displays student's enrolled courses
│       │   ├── studentProfile.html - Student profile page
│       │   └── studentTimeTable.html - Student's personal timetable
│       │
│       ├── teacher/ - Teacher-specific templates
│       │   ├── teacher subject.html - Displays courses taught by teacher
│       │   ├── teachersProfile.html - Teacher profile page
│       │   └── teacherTimeTable.html - Teacher's personal timetable
│       │
│       ├── Login.html - Main login page for all users
│
├── 1000036677.jpg - Sample image file (can be removed or replaced)
└── README.md - Project documentation (this file)
```

## Setup Instructions

1. **Prerequisites**:
   - Python 3.x
   - MySQL Server
   - Flask (`pip install flask`)
   - Flask-MySQLdb (`pip install flask-mysqldb`)

2. **Database Setup**:
   - Create a MySQL database for the project
   - Update the database connection details in `app.py`

3. **Running the Application**:
   ```
   python app.py
   ```
   The application will be available at `http://localhost:5000`

4. **Initial Admin Account**:
   - The first admin account needs to be created directly in the database
   - Subsequent accounts can be created through the admin interface

## Future Enhancements

- Implement password reset functionality
- Add student-teacher communication system
- Include attendance tracking features
- Develop examination management module
- Implement data export/import functionality

## Contribution Guidelines

Contributions to this project are welcome. Please fork the repository and submit pull requests for any enhancements or bug fixes.

## License

This project is open-source and available under the MIT License.
