## Backend:

## Technologies:

Spring Boot: A Java-based framework for developing RESTful APIs.
MySQL: A relational database for data storage.
Spring Data JPA: Simplifies interaction with the database.

## Key Functionalities:

User Management:
Create a new user and store their data in a MySQL database.
Retrieve a list of all users or details of a specific user.
Update user information.
Delete a user by their unique ID.

Custom Exception Handling:
Handles scenarios where a user is not found with meaningful error messages.
Implemented using @ControllerAdvice and custom exceptions.

Cross-Origin Resource Sharing (CORS):
Allows the frontend to communicate with the backend seamlessly.
API Endpoints:
POST /users: Add a user.
GET /users: Retrieve all users.
GET /users/{id}: Retrieve a specific user.
PUT /users/{id}: Update user information.
DELETE /users/{id}: Remove a user.

# Summary

This project provides a complete solution for user management in a web application, integrating a modern frontend with a robust backend, ensuring smooth communication and effective user experience.