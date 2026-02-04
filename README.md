# Repo for CS4135 Group Project

## Development Instruction

> **Note**: Please develop on the `dev` branch. Only merge to `main` after testing.

### Frontend

1. Install nvm and nodejs
2. `cd ./frontend` and `npm i`
3. `npm run dev` to start dev server

### Backend

1. Install JDK 25 and Maven
2. `cd ./backend` and `mvn clean install`
3. `mvn spring-boot:run` to start dev server
4. Access H2 Console at <http://localhost:8080/h2-console>
   - JDBC URL: `jdbc:h2:mem:testdb`
   - Username: `sa`
   - Password: (empty)

## Tech Stack

- **Frontend**: Node.js
- **Backend**: Spring Boot 4.0.2, Java 25
- **Database**: H2 (dev) / PostgreSQL (prod)
