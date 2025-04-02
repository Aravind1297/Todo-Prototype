Todo-Prototype

📌 Project Overview

Todo-Prototype is a full-stack Task Management Application that allows users to Create, Read, Update, and Delete (CRUD) tasks. The backend is built using Spring Boot, and the frontend will be developed in future versions.

🛠 Current Version: v1.1
Whats new in v1.1?
Integrated MySQL – Replaced in-memory H2 database with a persistent MySQL database for better data management.
Environment Configurations – Added separate Dev and Prod configurations to support continuous testing and integration


Backend: Spring Boot with an in-memory database (H2)

RESTful API with CRUD operations for tasks

Basic security authentication (Username & Password)

Uses Gradle for build and dependency management

🚀 Future Roadmap

v2.0 → Add frontend (React/Angular/Vue)

v3.0+ → Implement OAuth, Role-based authentication, and other features

📂 Project Structure

Todo-Prototype/
│── .idea/                # IntelliJ project settings (ignored in Git)
│── frontend/             # (Will contain UI in future versions)
│   └── my-todo-app/      # Placeholder for frontend
│── backend/              # Backend application (Spring Boot)
│   └── taskmanager/      # Spring Boot source code
│── README.md             # Project documentation
│── .gitignore            # Ignored files & directories

🔧 Setup & Installation

1️⃣ Clone the Repository

git clone https://github.com/your-username/Todo-Prototype.git
cd Todo-Prototype/backend

2️⃣ Configure the database

Create a MySQL database for the project.

CREATE DATABASE taskdb

--> Update application-dev.properties for local deployment

3️⃣ Build & Run the Backend

./gradlew bootRun

The application runs at: http://localhost:8081

4️⃣ Access the API Endpoints

You can test API endpoints using Postman or cURL:

GET /tasks → Retrieve all tasks

POST /tasks → Create a new task

PUT /tasks/{id} → Update a task

DELETE /tasks/{id} → Delete a task

Sample JSON for Creating a Task:
{
  "title": "Complete Spring Boot Project",
  "description": "Implement CRUD operations",
  "completed": false
}

Note: The application requires authentication (username & password) to access API endpoints.

🛠 Technologies Used

Backend: Java, Spring Boot, Spring Data JPA, Spring Security

Database: MySQL

Build Tool: Gradle

Version Control: Git & GitHub

📌 Contributing

Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

✨ Author: Aravind
📅 Started On: March 2025

