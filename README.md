# E-commerce Application

## Overview

This is a e-commerce application built using Spring Boot, PostgreSQL, Docker, and OpenAPI. The application supports CRUD operations on products, orders, and order items.

## Prerequisites

- Java 17
- Docker
- Docker Compose

## Build

To build the application, run the following command:

```bash
mvn clean install
```

## Running the Application with Docker

Make sure Docker is running and then run:

```bash
docker-compose up -d
mvn spring-boot:run
```

## API Documentation

Access the Swagger UI for API documentation:

Swagger UI: http://localhost:8080/swagger-ui.html

Use this link to explore and interact with the API endpoints.

## Testing

Ensure Docker containers are running, then execute:

```bash
mvn test
```
