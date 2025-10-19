# J.P. Morgan Software Engineering Virtual Experience (via Forage)

**Repository:** [Arjundas08/forage-midas](https://github.com/Arjundas08/forage-midas)

## 1. Project Overview  
This project was completed as part of the **J.P. Morgan Software Engineering job simulation** provided by **Forage** during Oct 2025. In this simulation I built a backend system to mimic how financial services applications handle real-time transactions and distributed data flows.

## 2. What I Built  
- Implemented a **Spring Boot** microservice architecture for transaction processing.  
- Integrated **Apache Kafka** for event-driven messaging to enable scalable, asynchronous workflow.  
- Used **H2 Database** (in-memory) to simulate persistence and quick local testing.  
- Developed RESTful APIs and controllers to expose services and handle requests (create/read/update flows).  
- Set up automated testing (unit/integration) to validate endpoints and message flows.

## 3. Why It Matters  
In real financial systems, latency, scaling, reliability and message handling are critical. By using Kafka and a microservice design, I simulated how a backend system can handle high-throughput, distributed transactions — a key concept in fintech and enterprise backends.

## 4. Technologies Used  
- Java 17 • Spring Boot  
- Apache Kafka (Producer/Consumer)  
- H2 Database (in-memory)  
- REST API (Spring Web) & Controllers  
- JUnit / Mockito (Testing)  
- GitHub Actions (CI pipeline) — *optional: if you set this up*.

## 5. What I Learned  
- How to design and implement event-driven architectures using Kafka.  
- The importance of decoupling microservices and using message brokers for real-time workflows.  
- Best practices for REST API design and integration with databases.  
- Hands-on with testing and local environment setup for rapid development.

## 6. Next Steps & Improvements  
- Replace H2 with a persistent relational DB (e.g., PostgreSQL) for production-level simulation.  
- Deploy microservices to cloud (AWS/Azure/GCP) and use managed Kafka.  
- Add logging/monitoring (e.g., with Prometheus/Grafana) for observability.  
- Expand APIs to include authentication/authorization (OAuth2/JWT) and API gateway.

## 7. Certificate  
Issued by **J.P. Morgan & Forage** on *<insert actual date>*.  
![Certificate Screenshot](link-to-certificate-image-if-you-upload)  

*Feel free to explore the code, and reach out with any questions!*
