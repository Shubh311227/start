# DoorDelights (v1.0.0)

## Overview
This repository contains the source code for **DoorDelights**, a microservices-based application [1]. 

## Architecture & Components
The project is structured into several distinct microservices and components to handle different functionalities [1]. The repository includes the following modules:

*   **`eureka`**: The service discovery server (likely Netflix Eureka) used to register and locate microservices [1].
*   **`apiGateway`**: The API Gateway that acts as the single entry point, routing client requests to the appropriate backend services [1].
*   **`userservice`**: A microservice dedicated to handling user data and operations [1].
*   **`searchservice`**: A microservice designed to handle search functionalities within the application [1].
*   **`favoriteservice`**: A microservice responsible for managing user favorites or saved items [1].
*   **`webapp`**: The frontend web application or user interface [1].

## Technologies & Infrastructure
Based on the configuration files present in the repository root, this project utilizes the following tools [1]:

*   **Build Tool**: The presence of a `pom.xml` file indicates the project uses Maven for dependency management and building [1].
*   **Containerization**: A `docker-compose.yml` file is included, which allows for the orchestration and deployment of the microservices via Docker [1].
*   **CI/CD**: Continuous Integration and Continuous Deployment pipelines are configured using the `.gitlab-ci.yml` file [1].
*   **Version Control**: A standard `.gitignore` file is included to keep the repository clean from build artifacts [1].

## Getting Started
*(Note: Please verify these standard instructions against your actual project requirements)*

### Prerequisites
*   Docker and Docker Compose installed.
*   Java/Maven installed (if running locally without Docker).

### Running the Application
1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd start/doordelights-v1.0.0