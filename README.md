# Java & Spring Boot Microservices — Learning Project

A hands-on microservices learning project using Java, Spring Boot, PostgreSQL, Kafka, gRPC, authentication, and containerised services.

> **Course-based project**  
> This repository is based on training material by **Chris Blakely / Code Jackal**. It is maintained here as a learning implementation and reference. Original course authorship remains with the course creator.

## Architecture

The project explores a distributed healthcare-style domain with multiple services, including:

- **Patient Service** — persistence and domain operations.
- **Billing Service** — service-to-service communication via gRPC.
- **Notification Service** — asynchronous event processing with Kafka.
- **Auth Service** — authentication, security, JWT handling, and persistence.
- **PostgreSQL** — service data stores.
- **Kafka** — event transport between services.

## Technology stack

- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- PostgreSQL
- Apache Kafka
- gRPC / Protocol Buffers
- JWT
- Maven
- Containers / local service orchestration

## Getting started

Each service has its own configuration and runtime requirements. Review the relevant service directory and configure environment variables before starting it.

Example development variables include database connectivity, Kafka bootstrap servers, service addresses, and gRPC ports. **Do not commit real credentials or production secrets.**

## Development principles demonstrated

- Service boundaries and independent persistence.
- Synchronous gRPC communication.
- Event-driven processing with Kafka.
- Authentication and authorisation.
- Environment-based configuration.
- Local debugging of distributed services.

## Security note

Sample passwords, local users, or development database values in course material are for local learning only. Replace them with secure secret management in any real deployment.

## Attribution

Copyright and original course material: **Code Jackal / Chris Blakely**.

## Status

**Active learning/reference project.** The repository is intended to demonstrate architecture and implementation techniques rather than serve as a production deployment template.
