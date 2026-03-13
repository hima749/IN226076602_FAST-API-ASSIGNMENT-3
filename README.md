# IN226076602_FAST-API-ASSIGNMENT-3
# FastAPI Internship Assignment – CRUD API

## Overview

This repository contains my FastAPI assignment completed as part of the internship training.
The project implements a simple **Product Management API** with CRUD operations using **FastAPI**.

## Technologies Used

* Python
* FastAPI
* Uvicorn
* Swagger UI (for API testing)

## API Endpoints Implemented

* **GET /** – Home endpoint
* **GET /products** – Retrieve all products
* **GET /products/{product_id}** – Retrieve a specific product
* **POST /products** – Add a new product
* **PUT /products/{product_id}** – Update product details
* **DELETE /products/{product_id}** – Delete a product
* **GET /products/audit** – Inventory summary endpoint

## Assignment Tasks Completed

1. Added new products using POST request
2. Updated product stock and price using PUT request
3. Deleted products using DELETE request
4. Performed full CRUD workflow
5. Created an inventory audit endpoint

## Project Structure

```
YOUR_INTERNID_FASTAPI
 └── ASSIGNMENT 1
      ├── main.py
      ├── Q1_Output.png
      ├── Q2_Output.png
      ├── Q3_Output.png
      ├── Q4_Output.png
      └── Q5_Output.png
```

## How to Run the Project

1. Install dependencies

```
pip install fastapi uvicorn
```

2. Run the FastAPI server

```
uvicorn main:app --reload
```

3. Open Swagger UI

```
http://127.0.0.1:8000/docs
```

## Author

Himanshu Singh
