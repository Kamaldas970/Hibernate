# FirstHibernateProject

# First Hibernate Project

A simple introductory Java project demonstrating core Hibernate ORM concepts: entity mapping, CRUD operations, SessionFactory usage, and MySQL integration. Perfect for beginners learning persistence in Java apps.

## Features
- POJO entity (e.g., Student) with @Entity, @Id annotations
- hibernate.cfg.xml for DB config (MySQL dialect, connection pooling)
- Basic operations: save, update, delete, list entities
- Transaction handling with rollback on exceptions
- Maven dependencies for Hibernate Core 5.x+ and MySQL connector

## Tech Stack
- Java 8/11+
- Hibernate 5.x/6.x
- MySQL 8.x
- Maven/Eclipse/IntelliJ
- JDBC driver

## Quick Setup
1. Clone repo: `git clone <your-repo-url>`
2. Update `hibernate.cfg.xml` with your DB credentials
3. Run `mvn clean install` or `App.java` in IDE
4. Tables auto-create on first run; check DB for data

Built for learning—extend to Spring Boot/JPA next![web:2]
