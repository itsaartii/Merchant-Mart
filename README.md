# Merchant-Mart: B2B E-Commerce Platform

**Merchant-Mart** is a scalable, microservices-based B2B e-commerce platform designed to seamlessly connect merchants, suppliers, and buyers. With a modular architecture, this platform allows flexibility, scalability, and easier management of various business processes. The platform facilitates bulk buying, product catalog management, real-time transactions, and secure business interactions.

---

## Features

- **Microservices-Based Architecture**  
  Each service (User Management, Product Management, Order Management, etc.) is encapsulated as an independent microservice, ensuring modularity and scalability.

- **User Management**  
  Secure user login, registration, and role-based access (Admin, Merchant, Customer).

- **Product Management**  
  Easy addition, editing, and categorization of products for bulk sales.

- **Order Management**  
  Real-time order processing, tracking, and history.

- **Payment Gateway Integration**  
  Seamless and secure payment processing through integrated gateways.

- **Dashboard & Analytics**  
  Comprehensive business intelligence tools for merchants and admins.

- **Supplier/Buyer Interactions**  
  Instant messaging and negotiation features between buyers and suppliers.

- **Inventory Management**  
  Real-time stock updates and alerts for merchants.

---

## Tech Stack

- **Backend**: Spring Boot 
- **Microservices Communication**: REST APIs, Kafka 
- **Frontend**: React.js 
- **Database**: MySQL, MongoDB 
- **Authentication**: JWT, OAuth 2.0, Spring Security  
- **Payment Integration**: Razorpay, Stripe  
- **Containerization**: Docker  
- **API Gateway**: Spring Cloud Gateway or Zuul  
- **Service Discovery**: Eureka (Spring Cloud)  
- **Configuration Management**: Spring Cloud Config  
- **Deployment & Scaling**: Docker Swarm  

---

## Microservices Structure

The platform is divided into multiple microservices, each handling a specific aspect of the application:

1. **User Service**  
   Manages user authentication, registration, and profiles.

2. **Product Service**  
   Handles product catalogs, categorization, and inventory.

3. **Order Service**  
   Manages order creation, tracking, and history.

4. **Payment Service**  
   Integrates with payment gateways for processing transactions.

5. **Inventory Service**  
   Manages stock levels and alerts for low inventory.

6. **Notification Service**  
   Handles email/SMS notifications for users (order updates, payment status, etc.).

7. **Analytics Service**  
   Gathers data from different services and provides insights for business intelligence.

---

## Installation

### Prerequisites

- Java 1.8 or above
- MySQL (for relational data)
- MongoDB (for some microservices)
- Docker (optional for containerization)
- Maven (for building the project)

### Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/merchant-mart.git
