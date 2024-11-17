# ServiceDiscovery

## Overview
The **ServiceDiscovery** service is responsible for dynamic service registration and discovery across the eCommerce platform. It ensures reliable communication between microservices.

---

## Features
- Service registration and health checks
- Integration with Eureka

---

## Technologies Used
- **Java 8**
- **Spring Boot**
- **Netflix Eureka**

---

## Installation
1. Run the Eureka Server:
   ```bash
   mvn clean install
   java -jar target/ServiceDiscovery-0.0.1-SNAPSHOT.jar
