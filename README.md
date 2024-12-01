# Borcelle Eureka Server

This repository contains the Eureka Server service for the e-commerce platform, built using Spring Boot and Spring Cloud. The Eureka Server acts as a service registry, enabling microservices to discover and communicate with each other dynamically in a distributed system.


## Overview

The **Eureka Server** serves as the service discovery server for the microservices architecture. It registers all running microservices and provides information about their instances, enabling:

- Dynamic service registration and deregistration.
- Load balancing and fault tolerance.
- Improved scalability by discovering services at runtime.

This service is a core component in the Spring Cloud ecosystem.

---

## Features

- **Service Registry**: Stores and manages service instances.
- **Dynamic Discovery**: Microservices can register themselves dynamically.
- **High Availability**: Configurable to run in a cluster for redundancy.
- **Dashboard Interface**: View registered services and their statuses.
- **Heartbeat Mechanism**: Monitors the availability of services and removes unreachable instances.

---

## Technologies

- **Spring Boot** - Framework for building Java-based applications.
- **Spring Cloud Netflix Eureka** - Provides service registry and discovery capabilities.
- **Maven** - Build tool for managing dependencies and building the application.

---

## Setup

### Prerequisites

Before you begin, ensure that you have the following installed:

- Java 21
- Maven

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/akram-idrissi/borcelle-eureka-server.git
   cd borcelle-eureka-server
   ```
2. mvn clean install
3. mvn spring-boot:run
4. open browser got to: http://localhost:8761
