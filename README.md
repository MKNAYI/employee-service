# Employee-service

## Prerequisites

Before you begin, make sure you have the following installed:

- Java 21
- Maven 
- IDE - IntelliJ IDEA
- MongoDB - Database schema
  Download: (Windows machine) https://fastdl.mongodb.org/windows/mongodb-windows-x86_64-8.0.4-signed.msi

## Getting Started

### 1. Clone the Repository

First, clone this repository to your local machine:

```bash
git clone https://github.com/MKNAYI/employee-service.git

```

Build the Application
Navigate to the project directory and use Maven to build the application:

```bash
mvn clean install
```

Run the Application
To run the Spring Boot application, execute the following command:

```bash
mvn spring-boot:run
```

Access the Application
Once the application starts, it will be accessible on http://localhost:8080 by default. You can test the microservice by making an HTTP request.

For example, using curl:

```bash
curl --location 'localhost:8080/employees' \
--header 'Content-Type: application/json' \
--data '{
    "name": "Test",
    "department": "Test department",
    "salary": 10000
}'
```

### Postman collection 
[Download file](../../raw/master/CRUD-with-MongoDB.postman_collection.json)
