# 🏥 Healthcare Backend API – Django Assignment

This project is a RESTful backend API built with **Django**, **Django REST Framework**, and **PostgreSQL**. It provides a secure system for managing users, patients, doctors, and their mappings, designed as part of a backend developer internship assignment.

---

## 🚀 Features

- ✅ User Registration & Login with JWT
- 👨‍⚕️ CRUD operations for Doctors
- 🧑‍⚕️ CRUD operations for Patients (restricted to authenticated users)
- 🔗 Patient-Doctor mapping system
- 🔒 Authentication using JWT (via `djangorestframework-simplejwt`)
- 🗃️ PostgreSQL database integration
- 🛡️ Environment variable-based configuration for sensitive data
- 🌐 RESTful API structure

---

## 🛠️ Tech Stack

- Python 3.x
- Django 4.x
- Django REST Framework
- PostgreSQL
- JWT Authentication (SimpleJWT)
- dotenv for environment variables

---
📡 API Endpoints Summary
🔑 Authentication
POST /api/auth/register/ – Register a user

POST /api/auth/login/ – Obtain JWT tokens

👥 Patients (Auth required)
POST /api/patients/ – Add patient

GET /api/patients/ – List patient records

GET /api/patients/<id>/ – Retrieve a patient

PUT /api/patients/<id>/ – Update a patient

DELETE /api/patients/<id>/ – Delete a patient

👨‍⚕️ Doctors
POST /api/doctors/ – Add doctor

GET /api/doctors/ – List all doctors

GET /api/doctors/<id>/ – Retrieve a doctor

PUT /api/doctors/<id>/ – Update a doctor

DELETE /api/doctors/<id>/ – Delete a doctor

🔁 Patient-Doctor Mapping
POST /api/mappings/ – Assign doctor to patient

GET /api/mappings/ – List all mappings

GET /api/mappings/<patient_id>/ – Get patient’s doctors




This project is for educational and evaluation purposes as part of a technical assessment.



DELETE /api/mappings/<id>/ – Remove doctor from patient




