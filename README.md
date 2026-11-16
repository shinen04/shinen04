# Hi there, I'm Shin En! 👋

🎓 I'm a Year 3 Computer Science undergraduate at **Singapore Management University (SMU)**, specialising in **Artificial Intelligence and Cybersecurity**.

🚀 Through university projects and hackathons, I've had the opportunity to work on different aspects of software development, including frontend and backend development, microservices, and cloud technologies.

💻 I'm continuing to explore different technologies and gain more hands-on experience building applications.

### 🛠️ Technologies I've Worked With

**Languages:** Java, Python, JavaScript, TypeScript, SQL, Go, C

**Frameworks:** React, Spring Boot, Node.js, Express, FastAPI

**Databases:** PostgreSQL, MySQL

**Cloud & DevOps:** AWS Lambda, AWS CloudFormation, Docker, Kubernetes, Git, GitLab CI/CD

**Other Tools:** Figma, Jira

### 🚀 Featured Projects

**🏦 CRM System**

**Tech Stack:** JavaScript, TypeScript, Node.js, React, PostgreSQL (Aurora), AWS (Lambda, SQS, EventBridge, S3, CloudFormation)

A cloud-based CRM system developed by a team of 7 for SMU's CS301 module, designed to help banking relationship managers manage client, account, and transaction information using a microservices architecture.

**My Contributions:**
- Developed REST API endpoints for the transaction service, including internal APIs for sharing aggregated transaction data across services
- Implemented an AWS Lambda-based pipeline to ingest daily bank transaction files via SFTP, validate records, and store transaction and audit information
- Developed React admin pages for managing transactions, monitoring data ingestion, and viewing audit records

---

**🎟️ Concert Booking Platform**

**Tech Stack:** Go, PostgreSQL, RabbitMQ, GitLab CI/CD, Docker, Kubernetes, Argo CD, Kustomize

An event ticketing platform developed by a team of 5 for SMU's CS302 module, featuring 8 backend microservices.

**My Contributions:**
- Developed the seat service in Go and PostgreSQL, implementing seat holds, expiry, confirmation, and release, with database constraints to prevent double-booking
- Implemented a transactional outbox pattern with RabbitMQ for reliable event publishing, alongside automated unit and integration tests
- Set up GitLab CI/CD pipelines with automated testing, code quality checks, security scans, and integration tests
- Configured GitOps deployment using Argo CD and Kustomize on Kubernetes, enabling version-controlled deployments and rollbacks

---

**🚢 PortPilot — Agentic AI Port-Call Coordination (https://github.com/rynrindesu/PortPilot)** 

**Tech Stack:** Python, FastAPI, LangGraph, LangChain, PostgreSQL, Groq, AWS Bedrock

A hackathon prototype that monitors incoming vessel ETAs for Singapore port calls. When an ETA changes, an AI agent replans berth, pilot, and tug bookings. Deterministic rules validate each option, and unresolved conflicts are escalated to human officers.

**My Contributions:**
- Implemented deterministic validation and ranking rules to evaluate rescheduling options and flag conflicts for human review
- Contributed to agent tools, scheduling option generation, and escalation handling
- Configured the agent's system prompt and final-answer format, and added support for switching between Groq and AWS Bedrock
- Added unit tests and live ETA-change test scripts to validate scheduling logic and agent behaviour

---

**🌐 Tariff Calculation Web App (https://github.com/shakeazeez/CSD_TARIFF_PROJECT)**

**Tech Stack:** Java, Spring Boot, React, PostgreSQL, Rust, Docker, GitHub Actions, JUnit, Mockito, RestAssured

A microservices-based web application developed by a team of 5 for SMU's Collaborative Software Development module, enabling general users, businesses, and banks to explore international trade tariffs, analyse historical trends, and access tariff-related insights.

**My Contributions:**
- Developed Spring Boot REST APIs for historical tariff data, pinned tariffs, and user search history, including fallback to historical WITS data when current tariff rates were unavailable
- Implemented an OpenNLP lemmatizer to improve item-name matching and documented backend APIs using Swagger
- Developed React frontend features for search history and tariff calculation
- Added automated unit and integration tests using JUnit, Mockito, and RestAssured across multiple backend services

### 📫 Connect With Me

- LinkedIn: www.linkedin.com/in/shin-en
- Email: shinen2004@gmail.com
