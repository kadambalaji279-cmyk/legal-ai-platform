# Legal AI Backend

Spring Boot backend for Legal AI.

## Technologies

- Java 25
- Spring Boot 3.5
- Spring Security
- Spring Data JPA
- MySQL
- JWT Authentication
- Swagger OpenAPI
- Maven

## Setup

### Clone

```bash
git clone <repository-url>
```

### Create Database

```sql
CREATE DATABASE legal_ai_db;
```

### Configure

Copy

```
application-example.properties
```

to

```
application.properties
```

and update:

- Database username
- Database password
- JWT secret

### Run

```bash
mvn spring-boot:run
```

or run

```
LegalAiBackendApplication.java
```

## Swagger

```
http://localhost:8081/swagger-ui/index.html
```

## API Docs

```
http://localhost:8081/v3/api-docs
```