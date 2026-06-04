# TreatyFlow

## Project Overview

TreatyFlow is an enterprise-grade Reinsurance Treaty Administration Platform used by insurers, reinsurers, brokers, MGAs, and TPAs to manage treaty business.

The platform supports:

* Treaty lifecycle management
* Premium processing
* Claims processing
* Bordereaux management
* Reinsurance accounting
* Reporting and analytics
* AI-assisted treaty administration

---

## Technology Stack

Backend:

* Java 21
* Spring Boot 3.x
* Spring Security
* Spring Data JPA
* Hibernate

Database:

* PostgreSQL

Frontend:

* React
* TypeScript

Infrastructure:

* Docker
* Docker Compose

API:

* REST APIs
* OpenAPI / Swagger

Authentication:

* JWT Authentication
* Role Based Access Control

---

## Architecture Principles

* Domain Driven Design
* Clean Architecture
* Layered Architecture
* SOLID Principles
* API First Design
* Audit Logging
* Multi-Tenant Support

---

## Core Modules

1. User Management
2. Role Management
3. Cedant Management
4. Reinsurer Management
5. Broker Management
6. Treaty Management
7. Treaty Version Management
8. Premium Processing
9. Claims Processing
10. Bordereaux Management
11. Reporting
12. Dashboard
13. AI Copilot

---

## Development Rules

* Generate production-ready code only
* Create DTOs for all APIs
* Use validation annotations
* Create Flyway database migrations
* Create unit tests
* Follow clean code practices
* Add audit fields to all entities
* Use UUID primary keys
* Generate OpenAPI documentation

---

## Database Standards

All tables must contain:

* id
* created_at
* created_by
* updated_at
* updated_by
* status

Use PostgreSQL conventions.

---

## Coding Standards

* Follow Java naming standards
* Follow REST best practices
* Use constructor injection
* Avoid field injection
* Use Lombok where appropriate
* Use exception handling framework
* Use service layer pattern

---

## Output Expectations

When generating code:

1. Explain assumptions
2. Create architecture first
3. Create database schema second
4. Create backend third
5. Create frontend fourth
6. Create tests
7. Create deployment artifacts
