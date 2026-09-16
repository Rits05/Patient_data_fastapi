Patient Management System API

A RESTful Patient Management System API built with FastAPI and Python. This project provides CRUD operations for managing patient records, data validation using Pydantic, automatic BMI calculation, BMI-based verdict generation, and patient sorting.

Live Demo

Swagger API Documentation:
https://patient-data-fastapi.onrender.com/docs

Live API:
https://patient-data-fastapi.onrender.com/

Features
Create patient records
View all patients
View individual patient details
Update patient information
Delete patient records
Sort patients by height, weight, or BMI
Automatic BMI calculation
Automatic BMI verdict
Data validation using Pydantic
Interactive Swagger UI documentation
RESTful API architecture
JSON-based data storage
Deployed on Render
Technologies Used
Python
FastAPI
Pydantic
Uvicorn
JSON
REST API
Swagger UI
Render
API Endpoints
Method	Endpoint	Description
GET	/	Check API status
GET	/about	Get API information
GET	/view	View all patients
GET	/patient/{patient_id}	View a specific patient
GET	/sort	Sort patients
POST	/create	Create a new patient
PUT	/edit/{patient_id}	Update patient information
DELETE	/delete/{patient_id}	Delete a patient
