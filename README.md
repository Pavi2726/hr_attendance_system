# HR Attendance System

## Project Overview

This project is a backend application developed using FastAPI for managing employee attendance. It includes features like user registration, attendance tracking, leave management, and report generation.

The main objective of this project is to provide a simple and efficient system for handling HR-related attendance operations.

---

## Technologies Used

* FastAPI
* SQLite
* SQLAlchemy
* Pydantic
* Pytest
* Docker

---

## Features

* Employee registration and authentication
* Attendance check-in system
* Leave management
* Monthly attendance reports
* Input validation
* API testing using pytest

---

## Project Structure

hr_attendance_system/

* app/

  * main.py
  * models.py
  * database.py
  * schemas.py
  * crud.py
  * validators.py
  * routes/

    * auth.py
    * attendance.py
    * leave.py
    * reports.py
* test_api.py
* requirements.txt
* .gitignore

---

## How to Run the Project

Step 1: Install dependencies
pip install -r requirements.txt

Step 2: Run the server
uvicorn app.main:app --reload

Step 3: Open in browser
http://127.0.0.1:8000
http://127.0.0.1:8000/docs

---

## Running Tests

pytest test_api.py

---

## Docker Setup

Build Docker image
docker build -t hr-api .

Run container
docker run -p 8000:8000 hr-api

---

## Conclusion

This project demonstrates the use of FastAPI to build a backend system with proper structure, validation, and testing. It can be extended further by adding a frontend and deploying it on cloud platforms.

---

## Author

Pavithra Thupakula
GitHub: https://github.com/Pavi2726
