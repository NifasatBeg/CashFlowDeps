# CashFlowDeps

CashFlowDeps is a repository containing configuration files and Docker Compose setups for the CashFlow microservices ecosystem. It includes Kong API Gateway configurations, Docker Compose files for service orchestration, and support for exposing local services using Ngrok.

## Features

- **Kong API Gateway** for centralized request routing.
- **Docker Compose** configurations for setting up services.
- **Authentication Flow**: Requests go through Kong, which first forwards them to AuthService for authentication before routing to respective services.
- **Ngrok Integration** to expose Kong's local URL for external access.

## Tech Stack

- **Kong API Gateway**
- **Docker & Docker Compose**
- **Ngrok**
- **Spring Boot Microservices (AuthService, UserService, etc.)**

## Security
- JWT authentication via **AuthService**.
- Ngrok for securely exposing local endpoints.
