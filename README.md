📚 Library Management System – Technical Assignment
This project is a backend implementation of a Library Management System, developed as part of a technical assignment. It provides a RESTful API for managing a digital library, including user roles (admin/user), book inventory, and borrowing functionality.

🎯 Objectives
The purpose of this assignment is to demonstrate:

Clean architecture and separation of concerns (Controller - Service - Repository)

Usage of Spring Boot and modern backend development practices

Simple role-based access control (Admin/User)

API documentation and ease of testing

Functional completeness and code maintainability

🛠️ Tech Stack
Language: Java 11

Frameworks: Spring Boot, Spring Security, Spring Data JPA

Database: MySQL

Authentication: JWT (JSON Web Tokens)

Documentation: Swagger UI

✅ Main Features
🧑‍💼 Admin Capabilities
Add new books to the catalog

Edit existing book information

Delete books

📚 User Capabilities
Register and log in

Search for available books

Borrow and return books

⚙️ Setup & Installation
Clone the repository:

bash
Αντιγραφή
Επεξεργασία
git clone https://github.com/your-username/Library-Management-App.git
cd Library-Management-App
Configure the MySQL database:

Create a database named library_db

Import the schema.sql file (provided in the repo)

Set your MySQL credentials in src/main/resources/application.properties:

ini
Αντιγραφή
Επεξεργασία
spring.datasource.username=yourUsername
spring.datasource.password=yourPassword
Run the application:

bash
Αντιγραφή
Επεξεργασία
mvn spring-boot:run
Access the API documentation (Swagger):

bash
Αντιγραφή
Επεξεργασία
http://localhost:8080/swagger-ui/
📦 API Documentation
The project includes Swagger UI for easy exploration of all available endpoints, including authorization headers for JWT tokens.

📂 Optional Enhancements (for future development)
Docker containerization for deployment

Postman collection for simplified testing

Unit & integration tests with JUnit / Mockito

Centralized exception handling with @ControllerAdvice

ERD diagram to visualize database schema
