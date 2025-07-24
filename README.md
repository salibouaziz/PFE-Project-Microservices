# PFE-Project-Microservices
📘 Graduation Project – Microservices & DevOps Integration for Cybersecurity Platform

📌 Project Overview
The objective of this graduation project was to migrate a legacy monolithic architecture of the CyberShield cybersecurity platform into a modern microservices-based architecture while integrating DevOps best practices.

This transformation aimed to improve:

-Scalability

-System maintainability

-Deployment automation

-Observability and performance testing

-Security in the CI/CD pipeline

🛠️ Technologies & Tools
-Backend Framework: Express.js

-Database: MongoDB

-Communication: Kafka, gRPC

-Containerization: Docker

-Orchestration: Kubernetes (set up manually using kubeadm)

-CI/CD & DevOps: Jenkins, SonarQube, trivy

-Monitoring & Observability: Prometheus, Grafana

-Security & Networking: WireGuard VPN

-Testing: Jest (unit testing), K6 (performance/load testing)

🧩 Project Components
🔁 1. Architecture Migration
Migrated core services of the CyberShield platform from a monolithic Node.js application to modular microservices.

Designed service boundaries and communication using gRPC and Kafka for async messaging.

🚀 2. CI/CD Integration
Implemented a CI/CD pipeline using Jenkins to automate:

-Code building

-Testing with Jest

-Static code analysis via SonarQube

-Container scanning with trivy

-Docker image publishing

📦 3. Containerization & Orchestration
-Dockerized all microservices for deployment.

-Set up a Kubernetes cluster manually using kubeadm on server.

-Deployed services using YAML configurations for:

-Deployments

-Services (ClusterIP, LoadBalancer)

-Ingress Controller

-ConfigMaps & Secrets

-Implemented rolling updates and basic auto-scaling policies.

🔐 4. Secure Networking
Configured WireGuard VPN for secure communication between microservices.

Managed access control between internal and external components.

📊 5. Monitoring & Observability
Integrated Prometheus to collect service metrics.

Created detailed dashboards in Grafana to visualize service health, response times, and error rates.

🧪 6. Testing & Performance
Unit tested services using Jest.

Simulated user traffic and load scenarios using K6 to test microservices under stress.

