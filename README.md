ClaimConnect – Insurance Claim Processing System
Technologies: React,Bootstrap, Spring Boot, Spring Cloud (Eureka, Gateway, Config Server), Feign Client, JWT, MySQL, GitHub

•	Developed an end-to-end insurance claim processing platform using Spring Boot Microservices and React, 
enabling role-based workflows for hospitals, patients, and insurance companies.
•	Implemented four modular microservices:
- Hospital Service
 – allows hospitals to log in and initiate claim requests on behalf of patients.
  
- Patient Service
 – enables patients to view claim requests and update their status (Accept / Reject / Revert).

- Insurance Company Service 
 – processes claims only after patient approval, allowing insurance officers to approve valid claims.

- Claim Request Service
  – acts as the central orchestrator handling end-to-end claim lifecycle.

•	Used Eureka Server for service discovery and Spring Cloud Gateway for secure, unified API routing with JWT-based authentication.
•	Managed centralized configuration for all services using Spring Cloud Config Server backed by a GitHub repository.
•	Enabled inter-service communication through Open Feign, ensuring efficient RESTful interactions.
•	Built an interactive frontend using React and Axios, offering role-specific views and operations.
•	Used MySQL for persistent storage across services with proper entity mapping and indexing.
