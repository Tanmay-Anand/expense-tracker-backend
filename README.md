# Expense Tracker — Backend

Stack: Spring Boot 3, Java 17, Postgres, JPA, Flyway.

## Run
- Start Postgres: see docker command in this README.
- `./mvnw spring-boot:run`

## Health
Actuator health: `GET http://localhost:8080/actuator/health`

## Migrations
Flyway location: `src/main/resources/db/migration`