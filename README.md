# API Gateway Microservice - Spring Cloud

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/JoelMaciel/Product-Catalog/blob/readm/LICENCE)


## About the Project

This project is an API Gateway microservice, an essential part of a microservices architecture. The API Gateway acts as the single point of entry for external requests, routing them to the appropriate internal services. It also handles important functions such as authentication, SSL termination, and load balancing.

### Key Features

- **Dynamic Routing**: Utilizes Eureka Service Discovery to locate instances of microservices.
- **Load Balancing**: Effectively distributes traffic load among microservices.
- **Authentication and Authorization**: Integrates with Spring Security and JWT to ensure that only authorized users can access the services.
- **Resilience**: Implements resilience patterns like circuit breakers to ensure system stability.

## Technologies Used

- **Java & Spring Boot**: For building microservices with a mature and robust framework.
- **Spring Cloud Gateway**: For API Gateway functions like routing, load balancing, and resilience.
- **Eureka**: For service discovery.
- **Spring Security, JWT**: For token-based authentication and authorization.


## Request Images


#### Microservice registered with Eureka Discovery

![Captura de tela de 2023-11-12 20-41-16](https://github.com/JoelMaciel/EAD-COURSE/assets/77079093/a2dd17f6-f001-4350-9698-779858d7b7c9)

## Getting Started

### Prerequisites

- JDK 11 or higher
- Maven


### Configuration

Explain how to configure the local environment to run the microservice, for example:

```bash
# Clone the repository
git clone YOUR_REPO_URL

# Enter the project directory
cd api-gateway

# Build the project
mvn clean install

# Run the service
java -jar target/api-gateway-0.0.1-SNAPSHOT.jar

