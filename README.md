Perfect! Here's your **final `README.md` content for the `main` branch** of the repository [https://github.com/Pranavi2002/Full-Stack-Project](https://github.com/Pranavi2002/Full-Stack-Project):

---

# 👤 Full Stack User Management Web Application – React Frontend

This is the **frontend** of a full-stack web application designed to manage user data. The UI is built using **React.js** and styled with **Bootstrap**. It communicates with a secure backend (hosted on the `master` branch) via RESTful APIs.

> ⚠️ **Project Structure**
>
> * `main` branch: React.js **Frontend**
> * `master` branch: Spring Boot **Backend**
>
> Please switch branches accordingly to explore the complete project.

---

## 🌐 Technologies Used

* **React.js** – Building responsive, component-based UI
* **Bootstrap** – Styling and layout
* **Axios** – HTTP communication with the backend
* **React Router DOM** – Client-side routing

---

## 🔧 Key Functionalities

### 🏠 Home Page

* Displays a list of all users in a table.
* Options to **Add**, **Edit**, **View**, and **Delete** users.

### ➕ Add User

* A form to register a new user.
* Sends data to backend using `POST` request via Axios.

### ✏️ Edit User

* Pre-filled form with user data.
* Allows updates using a `PUT` request.

### 👁️ View User

* Displays user details in a read-only format.

### ❌ Delete User

* Deletes user from backend using a `DELETE` request.
* Dynamically removes user from the UI.

### 🔁 Routing

* Implemented with **React Router**.
* Pages: `/`, `/adduser`, `/edituser/:id`, `/viewuser/:id`

### 🧭 Navigation Bar

* Built using Bootstrap.
* Easy access to all app pages.

---

## 🏁 Running the Frontend

```bash
# Clone the repository and checkout main branch
git clone https://github.com/Pranavi2002/Full-Stack-Project.git
cd Full-Stack-Project
git checkout main

# Install dependencies
npm install

# Start the development server
npm start
```

The app will run on `http://localhost:3000` by default.

---

## 📂 Project Structure

```plaintext
main (React Frontend)
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.js
│   ├── index.js
├── package.json
└── ...
```

For backend details and API documentation, see the [master branch README](https://github.com/Pranavi2002/Full-Stack-Project/blob/master/README.md).