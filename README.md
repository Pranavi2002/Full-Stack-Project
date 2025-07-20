# 🔧 Full Stack User Management Web Application – Spring Boot Backend

This is the **backend** of a full-stack web application for managing user data. Built with **Spring Boot** and connected to a **MySQL** database, it provides a set of RESTful APIs that the frontend (in the `main` branch) consumes.

---

## 💻 Technologies Used

* **Spring Boot** – Java-based framework for building REST APIs
* **MySQL** – Relational database for user data persistence
* **Spring Data JPA** – Abstraction layer for database interaction
* **Spring Web** – For building RESTful web services
* **Lombok** – Reduces boilerplate code for models
* **CORS Configuration** – Allows frontend to access backend APIs

---

## ⚙️ Key Functionalities

### 👥 User Management (CRUD)

* **Create** a new user and store their data
* **Retrieve**:

  * List of all users
  * Specific user by ID
* **Update** user information by ID
* **Delete** user by ID

### 🚫 Custom Exception Handling

* Uses `@ControllerAdvice` and custom exceptions
* Returns meaningful error messages (e.g., *User not found*)

### 🔗 CORS Support

* Configured to allow frontend (React app) to make HTTP requests to this backend

---

## 📑 API Endpoints

| Method | Endpoint      | Description               |
| ------ | ------------- | ------------------------- |
| POST   | `/users`      | Add a new user            |
| GET    | `/users`      | Retrieve all users        |
| GET    | `/users/{id}` | Get a specific user by ID |
| PUT    | `/users/{id}` | Update user information   |
| DELETE | `/users/{id}` | Delete a user by ID       |

---

## ▶️ Running the Backend Locally

```bash
# Clone the repository and checkout master branch
git clone https://github.com/Pranavi2002/Full-Stack-Project.git
cd Full-Stack-Project
git checkout master

# Import the project into your IDE (e.g., IntelliJ or Eclipse)
# Make sure MySQL is running and database is created

# Run the application
./mvnw spring-boot:run
```

Make sure to update your `application.properties` with correct DB credentials.

---

## 📝 Summary

This backend application powers the user management system by providing REST APIs to perform all CRUD operations. With robust exception handling and CORS support, it seamlessly integrates with the React frontend for a full-stack experience.
