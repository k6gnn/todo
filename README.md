### 📝 ToDo List Web Application
This is a lightweight and modular ToDo List Web Application built using Spring Boot, leveraging Spring MVC, Spring Data JPA, Thymeleaf, and an H2 (or configurable SQL) database. It offers essential task management functionality with clean code architecture.

## 🛠️ Tech Stack
Backend: Java 17, Spring Boot, Spring MVC, Spring Data JPA

Frontend: Thymeleaf (HTML templating engine)

Database: H2 (in-memory, default) – configurable to MySQL, PostgreSQL, etc.

Build Tool: Maven

## ⚙️ Configuration
Note:
You must update the database credentials in src/main/resources/application.properties if using a persistent SQL database (e.g., MySQL or PostgreSQL). Replace the default H2 configuration with your database URL, username, and password.

Example:

spring.datasource.url=jdbc:mysql://localhost:3306/todo

spring.datasource.username=your_username

spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update

## 📌 Notes
The application is preconfigured for an in-memory H2 database.

Switch to a persistent database by editing application.properties.

