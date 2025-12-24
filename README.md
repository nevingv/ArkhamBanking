# ArkhamBanking
Project Overview:

This project is a microservices-based banking system that allows users to create and manage financial transactions through APIs. It includes real-world banking features such as transaction validation, fraud detection, batch processing, notifications, and audit logging. The system is designed for scalability, security, and efficient tracking of transaction lifecycles.

Key Features:

User & Account Management:

User registration, login, and role-based access.

Account creation, CRUD operations, daily limits, and country restrictions.

Transaction Processing:

Create transactions via REST APIs.

Validate sender/receiver accounts and balances.

Generate unique transaction IDs.

Fraud Detection:

Rule-based checks for unusual activity.

Optional ML-based risk scoring for complex fraud patterns.

Flag suspicious transactions before processing.

Batch Processing:

Scheduled batch jobs to process pending transactions.

Atomic debit/credit operations with retries and failure handling.

Notifications:

Email and SMS alerts for transaction success, failure, or fraud flags.

Audit Logs:

Track all user actions, transaction events, and batch operations.

Ensure traceability and compliance.

Deployment & Integration:

Dockerized microservices with PostgreSQL (and optional Redis).

CI/CD integration with GitHub and Jira for issue tracking.

Swagger/OpenAPI documentation for all APIs.

Technology Stack:

Backend: Java 17+, Spring Boot (Web, Data JPA, Security, Batch)

Database: PostgreSQL

Build & Dependency Management: Maven

Containerization: Docker, Docker Compose

Version Control: Git + GitHub

Testing: JUnit, Mockito, Postman

Optional: Redis, Flyway, Swagger/OpenAPI

System Architecture:
User / Client → API Gateway → Transaction Service → Fraud Detection → Pending Transactions → Batch Processor → Account Service → Notification Service → Audit Logs

Project Goals:

Build a full-stack backend project incorporating industry-relevant technologies.

Demonstrate knowledge of microservices, database efficiency, batch processing, security, and system design.

Enable GitHub-Jira integration for professional development workflow.

Prepare for backend software developer interviews with practical project experience.
