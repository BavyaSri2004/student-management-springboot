# Student Management System

A beginner-friendly Student Management REST API built using Java and Spring Boot.

## Technologies
- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Maven

## Features
- Create student
- Get all students
- Get student by ID
- Update student
- Delete student
- Input validation

## Architecture
Controller -> Service -> Repository -> Database

## API Endpoints
| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/students` | Get all students |
| GET | `/api/students/{id}` | Get student by ID |
| POST | `/api/students` | Create student |
| PUT | `/api/students/{id}` | Update student |
| DELETE | `/api/students/{id}` | Delete student |

## Run
Run `StudentManagementApplication.java` and access the API at `http://localhost:8080`.
