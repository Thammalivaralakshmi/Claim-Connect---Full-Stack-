# ClaimConnect 🚑💳  
*A Spring Boot Microservices & React-Based Insurance Claim Processing System*  

---

## 📌 Overview  
**ClaimConnect** is a microservices-based **insurance claim processing system** built using **Spring Boot (backend)** and **React (frontend)**.  
It provides a scalable and modular architecture with **Eureka Server, Config Server, and API Gateway**, ensuring **service discovery, centralized configuration, and secure API routing**.  

The system enables patients, hospitals, and insurance companies to interact seamlessly for **claim submission, verification, and settlement**.  

---

## 🏗️ Architecture Overview  

1. **React Frontend**  
   - Provides an intuitive UI for claim submission and tracking  
   - Interacts with backend services via API Gateway  

2. **API Gateway (Spring Cloud Gateway)**  
   - Routes client requests to the correct microservice  
   - Provides authentication & load balancing  

3. **Eureka Server (Service Discovery)**  
   - Registers all microservices dynamically  
   - Enables seamless inter-service communication  

4. **Spring Cloud Config Server**  
   - Centralized configuration management  
   - Fetches configs from a GitHub repo for version control  

5. **Microservices**  
   - **Claim-Request Service** → Handles claim submissions, approvals, and processing  
   - **Hospital Service** → Manages hospital records & treatment details  
   - **Patient Service** → Stores and manages patient data  
   - **Insurance Company Service** → Manages policies, verifications, and settlements  

---

## ⚙️ Tech Stack  

**Frontend:** React, Redux, Bootstrap CSS  
**Backend:** Spring Boot, Spring Cloud (Eureka, Config Server, Gateway)  
**Database:** MySQL  
**Service Communication:** REST APIs, Feign Clients  
**Security:** Spring Security, JWT Authentication  
**Deployment:** Docker, Kubernetes  

---

## 🌟 Key Features  
- ✅ **Microservices Architecture** → Modular and scalable  
- ✅ **Secure API Gateway** → Authentication & routing  
- ✅ **Eureka Server** → Service discovery & fault tolerance  
- ✅ **Centralized Config** → Managed via GitHub-integrated Config Server  
- ✅ **React Frontend** → Interactive UI for all stakeholders  
- ✅ **Role-Based Access Control (RBAC)** → Secure access for patients, hospitals, and insurers  

---

## 🚀 Getting Started  

### 🔧 Prerequisites  
- Java 17+  
- Spring Boot 3.x  
- Node.js & npm (for React frontend)  
- MySQL Database 
