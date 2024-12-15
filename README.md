
# Event Trigger Platform  

This backend service is designed for orchestrating and managing events based on user-defined rules. Built with **FastAPI**, **Docker**, and **PostgreSQL**, it provides a simple way to create, test, and manage event triggers.  

## Key Features  

- **Event Management**:  
  - Create, manage, and schedule event triggers (time-based or API-triggered).  

- **Event Logging**:  
  - Logs triggered events with customizable retention policies.  

- **Testing Capabilities**:  
  - Test both API and time-based triggers.  

- **User-Friendly Interface**:  
  - Access a simple interface via **Swagger/OpenAPI** documentation.  

## Requirements  

- **Docker** and **Docker Compose** (for local setup).  

## Setup and Execution  

### 1. Clone the Repository  

```bash  
git clone https://github.com/V22X4/segwise-assig.git
cd segwise-assig
```  

### 2. Run Locally  

```bash  
docker compose up --build  
```  

- Access the API documentation locally at:  
  - [http://localhost:8000/docs](http://localhost:8000/docs)  

## Access Cloud Deployment  

The platform is already deployed and accessible via Render. Use the following link to access it.
- [Swagger/OpenAPI Documentation (Render)](https://vishal-latest.onrender.com/docs)  
