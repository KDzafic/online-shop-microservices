# Online Shop Microservices Application

## Overview

This application is comprised of several microservices, each serving a specific purpose: Inventory Service, Order Service, Product Service, and Notification Service. To enhance its functionality and maintain a seamless user experience, the application leverages various technologies and architectural patterns.

## Supporting Infrastructure

To ensure a secure, resilient, and observable architecture, the Online Shop Microservices Application incorporates the following components:

1. **API Gateway:**

   - Serves as the entry point for external clients.
   - Efficiently routes requests to the corresponding microservices.
   - Provides a unified API interface for the entire online shop.

2. **Service Discovery:**

   - Facilitates dynamic service registration and discovery.
   - Enhances microservices' ability to locate and communicate with each other.
   - Improves system scalability and fault tolerance.

3. **Keycloak:**

   - Manages authentication and authorization securely.
   - Ensures controlled access to the microservices.
   - Integrates seamlessly with Spring Security for comprehensive application security.

4. **Resilience4J Circuit Breaker:**

   - Implements circuit-breaking patterns to prevent system failures.
   - Enhances the application's resilience by isolating faulty services.
   - Guards against cascading failures in a distributed environment.

5. **Distributed Tracing:**

   - Captures and traces requests across microservices.
   - Provides insights into request flow and performance.
   - Facilitates efficient debugging in a distributed system.

6. **Event-Driven Programming with Kafka:**

   - Enables asynchronous communication between microservices.
   - Facilitates decoupling, ensuring scalable and responsive systems.
   - Utilized by the Notification Service for real-time order event handling.

7. **Monitoring with Grafana and Prometheus:**
   - Grafana: Visualizes and analyzes data from Prometheus.
   - Prometheus: Collects and stores metrics from microservices.
   - Offers real-time monitoring and alerting capabilities for proactive system management.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/KDzafic/online-shop-microservices.git
   ```
