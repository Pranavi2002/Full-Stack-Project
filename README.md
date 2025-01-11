# Full Stack Web Application to manage user data. 
The application uses Spring Boot for the backend and React.js for the frontend, with a MySQL database for storing user information. 
The system supports basic CRUD operations (Create, Read, Update, Delete) and includes custom exception handling and routing.

## Technologies:

React.js: A JavaScript library for building user interfaces.
Bootstrap: A CSS framework for styling the app.
Axios: For HTTP requests to the backend.

## Key Functionalities:

Home Page:
Displays a table listing all users retrieved from the backend.
Buttons to add, edit, view, and delete users.

Add User:
A form for registering a new user.
Data is sent to the backend using Axios POST requests.

Edit User:
A form pre-filled with user data for updating user information.
Uses Axios PUT requests.

View User:
Displays details of a specific user.

Delete User:
Deletes a user with Axios DELETE requests.
Removes the user from the UI dynamically.

Routing:
React Router is used for page navigation.
Routes include Home, Add User, Edit User, and View User.

Navigation Bar:
Built using Bootstrap.
Includes links for quick navigation between pages.