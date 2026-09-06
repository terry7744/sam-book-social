# 🌐 Sam-Book Social Network

**Java-Spring Social Network Application**

## Description

Sam-Book is a complete social networking platform built with Java-Spring Boot.

## Features

- ✅ User Authentication & Profiles
- ✅ Social Feed
- ✅ Post Creation & Sharing
- ✅ User Connections
- ✅ Real-time Notifications
- ✅ Message System
- ✅ Comment & Like System

## Stack

- **Backend**: Java Spring Boot 3.1.0
- **Database**: MySQL 8.0
- **ORM**: JPA/Hibernate
- **API**: RESTful

## Setup

```bash
# Install dependencies
mvn clean install

# Configure database
# Edit application.properties with MySQL credentials

# Run locally
mvn spring-boot:run

# Build for production
mvn clean package
```

## Configuration

Create `application.properties`:

```properties
spring.application.name=sam-book-social
spring.datasource.url=jdbc:mysql://localhost:3306/sambook
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=false
server.port=8080
```

## API Endpoints

- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User login
- `GET /api/users/{id}` - Get user profile
- `POST /api/posts` - Create post
- `GET /api/feed` - Get social feed
- `POST /api/connections/add/{userId}` - Add connection

## Creator

**SalyMiout**
**Contact**: salumy0703@proton.me

---
**Status**: Development
**License**: MIT