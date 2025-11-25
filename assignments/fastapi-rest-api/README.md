
# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build and deploy RESTful APIs using the FastAPI framework in Python. You will create a simple API for managing resources, practice handling requests and responses, and understand basic API design principles.

## 📝 Tasks

### 🛠️ Set Up FastAPI Project

#### Description
Set up a new Python project with FastAPI. Install required packages and create a basic FastAPI application that runs locally.

#### Requirements
Completed program should:
- Use FastAPI and Uvicorn
- Start a local development server
- Display a welcome message at the root endpoint (`/`)

### 🛠️ Create CRUD Endpoints

#### Description
Implement RESTful endpoints for a resource (e.g., books, users, tasks). Support Create, Read, Update, and Delete operations using FastAPI routes.

#### Requirements
Completed program should:
- Define a resource model using Pydantic
- Implement endpoints for GET, POST, PUT, and DELETE
- Store resource data in-memory (list or dictionary)
- Return appropriate status codes and JSON responses

### 🛠️ API Documentation & Testing

#### Description
Explore FastAPI's automatic documentation and test your endpoints using the interactive Swagger UI.

#### Requirements
Completed program should:
- Provide OpenAPI documentation at `/docs`
- Allow users to test endpoints via Swagger UI
- Include example requests and responses in the README
