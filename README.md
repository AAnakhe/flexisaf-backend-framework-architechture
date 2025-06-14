# 📝 Task Management System

A simple RESTful API built with Spring Boot for managing tasks, demonstrating CRUD operations, layered architecture, JPA/Hibernate persistence, and automated database migrations using Flyway.

## 📌 Features

- **Create Task**: Add new tasks with title and description.
- **Retrieve Tasks**: Fetch all tasks or a specific task by ID.
- **Delete Task**: Remove tasks by ID.
- **Layered Architecture**: Separation of concerns with Controller, Service, and Repository layers.
- **JPA/Hibernate Integration**: Utilizes JPA annotations for ORM and Hibernate as the implementation.
- **Database Migration with Flyway**: Automatically manages schema changes and versioning via SQL migration scripts.

## 🚀 Flyway Migration

Flyway tracks and applies versioned SQL migrations on application startup, ensuring database schema is versioned and consistent across environments.
