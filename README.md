# Maincrafts
gain hands-on experience, develop industry-relevant skills, and complete real-world tasks related to your domain.
# User Management Web Application - Task 1

## Overview
This project is a simple, end-to-end full stack web application designed to store and manage user details. It was built as part of Task 1 for the Maincrafts Technology internship to demonstrate the integration of a frontend, backend, and database system.

## Project Flow
The application follows a standard Client-Server architecture:
1. **Frontend (Client):** The user visits the home page and sees an HTML form styled with CSS. 
2. **Data Submission:** When the user enters their Name and Email and clicks "Add User", an HTTP POST request is sent to the backend.
3. **Backend (Server):** The Python Flask application intercepts this POST request, extracts the form data, and connects to the SQLite database.
4. **Database (Storage):** The Flask app executes an `INSERT` SQL query to save the user's details permanently in the `users` table.
5. **Display:** The server then redirects the user back to the home page, executing a `SELECT *` query to fetch all saved users from the database, rendering them dynamically into the HTML table using Jinja2 templating.

## Technologies Used
* **Backend:** Python (v3.10+), Flask
* **Frontend:** HTML5, CSS3
* **Database:** SQLite
* **Development Tools:** VS Code, Web Browser
