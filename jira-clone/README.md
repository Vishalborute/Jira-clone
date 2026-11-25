# Jira Clone

A Spring Boot REST API for managing users, projects, and tasks.

## Requirements

- Java 21
- MySQL

## Run locally

1. Create the MySQL database configured by the application.
2. Set your local database credentials and JWT secret in `src/main/resources/application.properties`.
3. From this directory, run:

   ```powershell
   .\mvnw.cmd spring-boot:run
   ```

The application starts on the default Spring Boot port, `8080`.

## Run tests

```powershell
.\mvnw.cmd test
```
