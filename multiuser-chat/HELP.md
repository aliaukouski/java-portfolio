# Multiuser Chat – Help

**Multiuser Chat** is a real-time chat application built with **Java 22** and **Spring Boot**, showcasing backend development skills, WebSocket communication, and database integration.

## Key Features
- Real-time messaging between multiple users
- WebSocket-based communication (`/ws/chat`)
- User management and message persistence
- PostgreSQL with HikariCP for database connection pooling
- Clean modular code structure

## Tech Stack
- Java 21
- Spring Boot (Web + WebSocket + Data JPA)
- PostgreSQL
- Flyway for DB schema changes
- Lombok
- Gradle Wrapper for build automation

## Quick Start
1. **Database:** Start PostgreSQL with Docker Compose:
   ```bash
   docker-compose up -d
2. **Run Application**   
   ```bash
   ./gradlew bootRun
3. Access REST endpoints at http://localhost:8080 and WebSocket at /ws/chat.

> Note: This project is for demonstration only. Code is open to view but not for reuse without permission.