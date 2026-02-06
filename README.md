# Wells Fargo Data Model Implementation (Task 2)

## 📌 Project Overview
This project implements a financial portfolio management data model using Spring Boot and Java Persistence API (JPA). The system is designed to help financial advisors manage client portfolios and securities efficiently.

This project was completed as part of the Wells Fargo Software Engineering Virtual Experience Program (Forage).

---

## 🛠 Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- Relational Database (H2 / MySQL compatible)

---

## 🧩 Data Model Entities
The following entities were implemented:

### FinancialAdvisor
- Stores advisor details
- One advisor can manage multiple clients

### Client
- Stores client details
- Each client is assigned to one advisor
- Each client has one portfolio

### Portfolio
- Stores client investment portfolio
- One portfolio can contain multiple securities

### Security
- Stores investment/security details
- Linked to portfolio

---

## 🔗 Entity Relationships
FinancialAdvisor → Clients (One-to-Many)  
Client → Portfolio (One-to-One)  
Portfolio → Securities (One-to-Many)

---

## 📂 Project Structure
