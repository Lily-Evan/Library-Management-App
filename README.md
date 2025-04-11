📚 Library Management System – Backend API
A RESTful API built with Spring Boot for managing a library system with user roles (admin/user). This project was developed as part of a technical assignment and focuses on clean architecture, role-based access, and functional completeness.

🚀 Features
🧑‍💼 Admin
Add new books

Edit book details

Delete books

👤 User
Register and log in (JWT authentication)

View available books

Borrow and return books

⚙️ Tech Stack
Java 11

Spring Boot (MVC, Security, Data JPA)

MySQL

JWT for stateless authentication

Swagger UI for API documentation

🛠️ Getting Started
1. Clone the Repository
bash
Αντιγραφή
Επεξεργασία
git clone https://github.com/Lily-Evan/Library-Management-App.git
cd Library-Management-App
2. Set Up the Database
Create a MySQL database named library_db

Import the provided schema.sql file

3. Configure application.properties
Edit src/main/resources/application.properties and set your DB credentials:

properties
Αντιγραφή
Επεξεργασία
spring.datasource.username=yourUsername
spring.datasource.password=yourPassword
4. Run the Application
bash
Αντιγραφή
Επεξεργασία
mvn spring-boot:run
5. Access Swagger API Docs
Visit: http://localhost:8080/swagger-ui/

🧪 Postman Collection (Optional)
You can import a Postman collection to test endpoints directly. (To be added)

📌 Notes
The project demonstrates backend logic only — no frontend implementation is included.

Role-based access is handled with JWT tokens and simple role checks.

In-memory H2 database can be configured as an alternative for quick testing.

📷 ERD Diagram (Optional)
You can find the ERD diagram for the database structure here.

✅ To-Do / Future Improvements
Add unit tests (JUnit + Mockito)

Dockerize the application

Centralized error handling

Add Postman collection

