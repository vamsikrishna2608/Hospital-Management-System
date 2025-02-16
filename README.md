Hospital Management System (HMS)

 Overview
The **Hospital Management System (HMS) is a full-stack application built using **Spring Boot** and **RESTful APIs** to efficiently manage hospital operations. It includes modules for patient management, doctor scheduling, appointment booking, billing, and pharmacy management.

 Features
✔️ User Authentication & Role-Based Access (Admin, Doctor, Patient, Receptionist)  
✔️ Patient Registration & Medical History Tracking  
✔️ Doctor Management & Appointment Scheduling  
✔️ Pharmacy & Medicine Inventory Management  
✔️ Billing & Payment System (Stripe/PayPal Integration)  
✔️ Secure API with JWT Authentication  
✔️ API Documentation using Swagger  

Tech Stack
Backend
- Java 17 + Spring Boot 3
- Spring Data JPA (MySQL/PostgreSQL)
- Spring Security + JWT
- Spring Cloud (for microservices)
- Hibernate ORM
- Swagger API Documentation
- Redis (for caching)
- Kafka / RabbitMQ (for event-driven communication in microservices)

Frontend (Optional)
- React.js / Angular (for UI)

DevOps & Cloud
- Docker (Containerization)
- Kubernetes (Microservices Deployment)
- AWS/GCP (Cloud Deployment)
- Jenkins/GitHub Actions (CI/CD Pipeline)
- Prometheus + Grafana (Monitoring)

📂 Project Structure

hospital-management-system/ │── backend/ │ 
                            ├── user-service/ (Handles user authentication) │
                            ├── patient-service/ (Manages patient records) │ 
                            ├── doctor-service/ (Handles doctor data) │ 
                            ├── appointment-service/ (Schedules & tracks appointments) │ 
                            ├── billing-service/ (Processes payments & invoices) │
                            ├── pharmacy-service/ (Manages hospital inventory) 
                            │── frontend/ (Optional React/Angular) 
                            │── config-server/ (Centralized configuration) 
                            │── service-registry/ (Eureka-based microservices discovery) 
                            │── api-gateway/ (Spring Cloud API Gateway) 
                            │── docker-compose.yml
                            │── k8s-deployment/ 
                            │── README.md
