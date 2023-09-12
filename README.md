# Summative-2: Bookstore Management System

## 🎥 Video Walkthrough
Embark on a [brief visual journey](https://youtu.be/e5Slel04DJI) that demonstrates the project's capabilities and highlights.
[![Project Thumbnail](https://img.youtube.com/vi/e5Slel04DJI/0.jpg)](https://youtu.be/e5Slel04DJI)

## 📌 Overview
This project presents a Bookstore Management System backed by a RESTful API and GraphQL, providing seamless management of authors, publishers, and books.

## 📘 Models 
- 📖 **Authors**: CRUD operations.
- 🏢 **Publishers**: CRUD operations.
- 📚 **Books**: CRUD operations and find all by a given author.

## 🔧 Technical Features

### Setup and Configuration
- **Environment**: Developed with `Java 11` using `IntelliJ`.
- **Framework**: Initialized with `Spring Boot (2.x.x)`.
- **Build Tool**: Managed with `Maven`.
- **API Domain**: Set under `com.company.bookstore`.

### Backend Technologies
- **Database**: Synced with the `book_store` database managed using DBeaver and powered by Docker.
- **REST API**: Manages books, authors, and publishers with JSON data transactions.
- **Testing**: Leveraged `MockMvc` for thorough testing.
- **API Documentation**: Systematically documented using `Swagger`.

### GraphQL Queries
- Retrieve detailed info about a publisher, author, or book, including their related entities such as the first name, last name, ISBN, etc...
