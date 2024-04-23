# Email Microservice
***
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

This project is a Microservice built using **Java, Java Spring, MySQL as a database.**

# About the project
___
This microservice is designed to centralize the sending of emails to any service within a microservices architecture. Using the Spring Boot framework together with Spring Email, it offers a robust and efficient solution for managing email communications.

Initially, the microservice was configured to operate with Gmail's SMTP, handling requests synchronously through a REST API. To increase efficiency and handle scalable demands, it has been evolved to support asynchronous processing, using RabbitMQ for message management.

## Table of Contents
***
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)

## Technologies Used
***

- Java 17
- Sring boot
- Maven

## Installation
***
1. Clone the repository:

```bash
git clone https://github.com/geisonbruno1/Email-Microservice
```

2. Run the command ```mvn clean install``` in the project root to download dependencies and compile the code.

3. Run the command ```mvn spring-boot:run``` to start the application.

## Usage
***

1. Start the application with Maven
2. The API will be accessible at http://localhost:8080

## API Endpoints
***
The API provides the following endpoints:

```markdown
POST /sending-email - Send a new email

GET /emails - Lists all emails already sent
```
