# Backend - Spring Boot REST API

## Structure

```text
src/main/java/com/myapp/
├── controller/   -> REST endpoints
├── service/      -> Business logic
├── repository/   -> Database queries
├── model/        -> Entity classes
├── dto/          -> Data transfer objects
└── exception/    -> Custom exceptions
```

## Setup

### Prerequisites

- Java 11+
- Maven
- PostgreSQL

### Run Locally

```bash
# 1. Create database
psql -U postgres -c "CREATE DATABASE myapp_db;"

# 2. Build
mvn clean install

# 3. Run
mvn spring-boot:run
```

API runs on: http://localhost:8080/api

## Team Members

- Add your APIs here as you develop them.
- Update this file when adding new endpoints.