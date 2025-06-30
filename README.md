# ToDoList-FastAPI: Simple Task Management Web App 🌐

![ToDoList-FastAPI](https://img.shields.io/badge/ToDoList-FastAPI-blue?style=flat-square&logo=fastapi)

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Usage](#usage)
6. [API Endpoints](#api-endpoints)
7. [Contributing](#contributing)
8. [License](#license)
9. [Releases](#releases)

## Overview

ToDoList-FastAPI is a simple web application for managing tasks. Built with a FastAPI backend and a frontend using HTML, CSS, and JavaScript, this application allows users to create, read, update, and delete tasks efficiently. 

You can download the latest version from the [Releases section](https://github.com/gqgt131q/ToDoList-FastAPI/releases).

## Features

- **User-Friendly Interface**: Clean and simple design for easy navigation.
- **CRUD Operations**: Create, Read, Update, and Delete tasks.
- **Responsive Design**: Works on various devices and screen sizes.
- **FastAPI Backend**: High performance and easy to use.
- **SQLite Database**: Lightweight database for storing tasks.
- **RESTful API**: Interact with the backend using standard HTTP methods.

## Technologies Used

- **Frontend**: 
  - HTML
  - CSS
  - JavaScript
- **Backend**: 
  - FastAPI
  - Python
  - SQLAlchemy
  - SQLite

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/gqgt131q/ToDoList-FastAPI.git
   cd ToDoList-FastAPI
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   uvicorn main:app --reload
   ```

5. **Access the Application**:
   Open your browser and go to `http://127.0.0.1:8000`.

## Usage

Once the application is running, you can use the interface to manage your tasks. Here’s how:

1. **Create a Task**: Fill in the task details and click "Add Task".
2. **View Tasks**: All tasks will be displayed in a list format.
3. **Update a Task**: Click on the task you want to edit, make changes, and save.
4. **Delete a Task**: Click the delete button next to the task you want to remove.

## API Endpoints

The application exposes several API endpoints for interacting with tasks. Here’s a summary:

- **GET /tasks**: Retrieve all tasks.
- **POST /tasks**: Create a new task.
- **PUT /tasks/{id}**: Update an existing task.
- **DELETE /tasks/{id}**: Delete a task.

You can test these endpoints using tools like Postman or curl.

## Contributing

We welcome contributions to improve this project. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

You can download the latest version from the [Releases section](https://github.com/gqgt131q/ToDoList-FastAPI/releases). Please ensure to follow the installation steps to set up the application properly. 

![Releases](https://img.shields.io/badge/Releases-Latest%20Version-green?style=flat-square)

---

For any issues or feature requests, feel free to open an issue in the repository. Happy task managing!