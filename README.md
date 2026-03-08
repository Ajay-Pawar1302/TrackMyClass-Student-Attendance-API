# TrackMyClass — Student Attendance Management System

A REST API based Student Attendance Management 
System built using Spring Boot and MySQL.

## Tech Stack
- Java | Spring Boot | Spring Data JPA | Hibernate
- MySQL | REST APIs | Maven | Git | Postman

## Features
- Full CRUD for students, subjects, attendance records
- 5-table normalized MySQL database schema
- Entity relationships with Spring Data JPA
- Input validation and business logic
- Exception handling with proper HTTP responses
- All endpoints tested using Postman

## Database Schema
- Students table
- Subjects table
- Attendance table
- Teacher table
- Course table

## Project Structure
src/
├── controller/    → REST API endpoints
├── service/       → Business logic
├── repository/    → Database operations
└── model/         → Entity classes
