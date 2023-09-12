# Bookstore Management System

## 🎥 Video Walkthrough
Embark on a [brief visual journey on YouTube](https://youtu.be/e5Slel04DJI) that demonstrates the project's capabilities and highlights.
[![Project Thumbnail](https://img.youtube.com/vi/e5Slel04DJI/0.jpg)](https://youtu.be/e5Slel04DJI)

## 📌 Overview
This project presents a Bookstore Management System backed by a RESTful API and GraphQL, providing seamless management of authors, publishers, and books.

## 📘 Logistics
- Models: 📖 **Authors** | 🏢 **Publishers** | 📚 **Books**
- Full CRUD operations for all models.
- Search by specific/niche searches, such as find a book by author or publisher.
- Retrieve detailed information, including associated publisher and author, and as far as their first name and last name.

## 🔧 Technical Features

### Backend Technologies
- **Database**: Synced with the `book_store` database managed using `DBeaver` and powered by `Docker`.
- **REST API**: Manages books, authors, and publishers with `JSON` data transactions.
- **Testing**: Leveraged `MockMvc`, `JUnit` and `Insomnia` for thorough testing.
- **API Documentation**: Systematically documented using `Swagger`.
  
### Setup and Configuration
- **Environment**: Developed with `Java 11` using `IntelliJ`.
- **Framework**: Initialized with Spring Boot (2.x.x).
- **Build Tool**: Managed with `Maven`.
- **API Domain**: Set under `com.company.bookstore`.

### GraphQL Queries
- Retrieve detailed info about a publisher, author, or book, including their related entities such as the first name, last name, ISBN, etc...

## 🌟 Highlights
- **Object Relational Mapping**: An author or publisher can have many books, but books cannot have many authors or publishers. Addressed this by establishing relationships (such as one to many) in the models.
- **Intuitive API Endpoints**: CRUD operations made easy for authors, publishers, and books.
- **GraphQL Integration**: Dive deep with detailed queries, offering flexible data retrieval.
