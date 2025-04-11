# 📚 Library Management App

A Spring Boot REST API for managing a library system with admin and user roles.

## Features
- User registration & login (JWT authentication)
- Admin: Add / Edit / Delete books
- User: Search, borrow and return books

## Tech Stack
- Java 11
- Spring Boot, Spring Security, Spring Data JPA
- MySQL
- JWT for authentication

## Setup

1. Clone the repo  
2. Set up MySQL database and import `schema.sql`
3. Configure `application.properties`
4. Run with: `mvn spring-boot:run`
