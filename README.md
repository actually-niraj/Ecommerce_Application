# EcommerceHub — Enterprise Multi-Vendor E-commerce Platform

**EcommerceHub** (repo: `Ecommerce_Application`) is a full-stack, production-grade multi-vendor marketplace built using **Spring Boot (Microservices)**, **React**, and **Redux**.  
It supports separate **Customer**, **Seller**, and **Admin** portals with real-time inventory management, secure payment processing, and scalable database design.

---

## 🚀 Features

### 🏪 Full-Stack Marketplace
- Multi-vendor architecture with modular services  
- Distinct portals for **Customers**, **Sellers**, and **Admins**
- Real-time inventory and product management

### 🔐 Advanced Security
- Enterprise authentication using **Spring Security**
- **JWT Tokens** for sessionless auth
- **Role-Based Access Control (RBAC)** for granular permissions

### 💳 Payment Integration
- Secure payment processing using **Stripe API**
- Handles checkout, payment confirmation, and order flows

### 🗃️ Scalable Database
- Designed complex entity relationships with **JPA/Hibernate**
- Uses **PostgreSQL**
- Supports pagination, sorting, text search, and structured queries

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | Java, Spring Boot, Spring Security |
| Frontend | React, Redux |
| Database | PostgreSQL |
| Authentication | JWT |
| Payment | Stripe API |
| DevOps (optional) | Docker, AWS |

---

## 📍 Project Structure

Ecommerce_Application/
├── backend/ # Spring Boot services
│ ├── customer-service
│ ├── seller-service
│ ├── admin-service
│ └── common-auth
├── frontend/ # React + Redux app
│ ├── customer-portal
│ ├── seller-portal
│ ├── admin-portal
│ └── shared-components
├── scripts/ # Deployment / config scripts
├── .gitignore
├── pom.xml
└── README.md



### Clone the Repository

```bash
git clone https://github.com/actually-niraj/Ecommerce_Application.git
cd Ecommerce_Application
