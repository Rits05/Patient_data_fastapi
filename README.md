# Patient Management System API

A RESTful API for managing patient records using FastAPI and Python. The project supports CRUD operations, data validation, automatic BMI calculation, BMI-based verdict generation, and patient sorting.

## Live Demo

Swagger API Documentation:  
[https://patient-data-fastapi.onrender.com/docs](https://patient-data-fastapi.onrender.com/docs)

Live API:  
[https://patient-data-fastapi.onrender.com/](https://patient-data-fastapi.onrender.com/)

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/` | Check API status |
| GET | `/about` | Get API information |
| GET | `/view` | View all patients |
| GET | `/patient/{patient_id}` | View a specific patient |
| GET | `/sort` | Sort patients |
| POST | `/create` | Create a new patient |
| PUT | `/edit/{patient_id}` | Update patient information |
| DELETE | `/delete/{patient_id}` | Delete a patient |
