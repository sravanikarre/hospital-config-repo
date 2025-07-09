# hospital-config-repo

Centralized configuration repository for the Hospital Microservices project.

## 📝 Config Files

| File Name             | Purpose                          |
|-----------------------|----------------------------------|
| `hospital-service.yml` | Configuration for Hospital Service |
| `api-gateway.yml`      | Configuration for API Gateway      |
| `eureka-server.yml`    | Configuration for Eureka Server    |

## 🔄 Dynamic Config Refresh

Supports Spring Cloud Config dynamic refresh using:
```bash
curl -X POST http://localhost:8081/actuator/refresh
