# 👟 Sneakers Store Backend with JWT Authentication and Role-Based Authorization - Java / Spring Boot

This project is a backend for a sneakers ecommerce system.
It provides user authentication and authorization functionalities using JWT (JSON Web Tokens) and a role-based access control system.
The backend is built with Java / Spring Boot and uses PostgreSQL as the database.


---

## 📌 Features

User Authentication: User registration and login system.

JWT Authorization: After logging in, users receive a JWT token for subsequent requests.

Product Management: Add, view, update, and delete sneaker products and manage their details.

Unit Testing: Controllers, repositories, and services tested with JUnit and Mockito.



---

## 🛠️ Technologies Used

Java / Spring Boot → Backend framework.

PostgreSQL → Database for storing user and ecommerce data.

JWT (JSON Web Tokens) → Used for authentication and role-based authorization.

JUnit4 / Mockito → Unit testing tools.



---

## 📖 API Documentation

The complete API documentation is available at the endpoint:

👉 /swagger-ui/index.html

It is fully interactive and allows testing endpoints directly from the Swagger UI.


---

## ⚙️ Installation & Usage

### 1. Clone the repository

git clone [REPOSITORY_URL]


### 2. Navigate to the project folder and install dependencies

cd [PROJECT_FOLDER_NAME]
mvn install

This will update dependencies and generate the application JAR if needed.


### 3. (Optional) Install PostgreSQL 14

Download from: PostgreSQL Official Website

Follow installation steps for your OS.

Set postgres as the username and admin as the password for the PostgreSQL superuser.

Create a new database named sneakers_store.


### 4. Run the server

Start the application using the main class in your preferred IDE (IntelliJ IDEA Community or Ultimate recommended).


### 5. Access the API documentation

Open your browser at:
👉 http://localhost:8080/swagger-ui/index.html

---

## 👨‍💻 Author

Developed with ❤️ by Samuel Baldasso
