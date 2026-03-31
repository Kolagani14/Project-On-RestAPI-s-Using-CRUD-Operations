# Project-On-RestAPI-s-Using-CRUD-Operations
# FastAPI REST API - CRUD Operations

This project is a backend application built using **FastAPI**, designed to demonstrate how to create RESTful APIs with full **CRUD (Create, Read, Update, Delete)** functionality. It provides a simple and efficient way to manage data through HTTP requests while following best practices for API development.

## 🚀 Overview

FastAPI is a modern, high-performance Python web framework used for building APIs quickly and efficiently. This project showcases how to:

* Build RESTful endpoints
* Handle HTTP methods (GET, POST, PUT, DELETE)
* Connect backend logic with data storage
* Validate request and response data
* Structure a scalable API project

## ⚙️ Features

* **Create**: Add new records using POST requests
* **Read**: Retrieve single or multiple records using GET requests
  -- **Update**: Modify existing records using PUT/PATCH requests
* **Delete**: Remove records using DELETE requests
* Automatic API documentation with Swagger UI (`/docs`)
* Data validation using Pydantic models
* Clean and modular code structure

## 🛠️ Tech Stack

* **Backend**: FastAPI
* **Language**: Python
* **Data Validation**: Pydantic
* **Server**: Uvicorn

## 📂 Project Structure

```
project/
│── main.py          # Entry point of the application
│── models.py        # Data models / schemas
│── database.py      # Database connection logic
│── routers/         # API route handlers
│── requirements.txt # Dependencies
```

## 📌 API Endpoints

| Method | Endpoint    | Description     |
| ------ | ----------- | --------------- |
| GET    | /items      | Get all items   |
| GET    | /items/{id} | Get item by ID  |
| POST   | /items      | Create new item |
| PUT    | /items/{id} | Update item     |
| DELETE | /items/{id} | Delete item     |

## ▶️ How to Run

1. Clone the repository
2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
3. Run the server:

   ```
   uvicorn main:app --reload
   ```
4. Open in browser:

   * API Docs: `http://127.0.0.1:8000/docs`

## 💡 Why This Project?

Most beginners mess up APIs by:

* Mixing business logic everywhere
* Not validating data properly
* Writing unstructured code

This project avoids that by keeping things **clean, modular, and scalable**.


