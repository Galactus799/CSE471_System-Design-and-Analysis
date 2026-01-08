# CSE471 Project – Property Rental Management System

This repository contains a Django-based web application developed as part of the CSE471 (System Analysis and Design / Software Engineering) course. The project aims to provide an online system for managing rental properties, users, and rental-related operations.

## Project Overview

The Property Rental Management System allows users to register, log in, browse available properties, add and manage rental listings, and generate rental vouchers. Administrators can manage users, properties, and system data through the Django admin panel.

## Features

- User registration and authentication  
- Property listing and detailed property view  
- Add, update, and manage rental properties  
- Rental voucher generation  
- User profile management  
- Password reset functionality  
- Admin dashboard for system management  

## Technologies Used

- Backend: Python, Django  
- Frontend: HTML, CSS, Django Template Engine  
- Database: SQLite3  
- Authentication: Django built-in authentication system  

## Project Structure

CSE471-Project/  
├── Project/ (Main Django project settings)  
├── home/ (Application logic)  
├── templates/ (HTML templates)  
├── static/ (CSS, images, JS files)  
├── db.sqlite3  
├── manage.py  
└── README.md  

## Installation and Setup

1. Clone the repository  
   git clone https://github.com/your-username/CSE471-Project.git  
   cd CSE471-Project  

2. Create and activate a virtual environment  
   python -m venv venv  
   Windows: venv\Scripts\activate  
   Linux/macOS: source venv/bin/activate  

3. Install dependencies  
   pip install django  

4. Apply migrations  
   python manage.py migrate  

5. Create a superuser  
   python manage.py createsuperuser  

6. Run the development server  
   python manage.py runserver  

7. Open the application in a browser  
   http://127.0.0.1:8000/  

## Admin Panel

The admin panel can be accessed at:  
http://127.0.0.1:8000/admin/  

## Academic Purpose

This project was developed for academic purposes only as part of the CSE471 course to demonstrate software requirement analysis, system design, and web application development using Django.

## Author

Avishek Paul  
Department of Computer Science and Engineering  

## License

This project is intended for educational use only.
