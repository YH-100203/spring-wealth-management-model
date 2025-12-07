# Wealth Management Data Model (Spring Boot + JPA)

## 💼 Overview
This project models the core data relationships within a wealth management system.  
It represents how financial advisors manage clients, who own investment portfolios containing securities.

The application uses:
- **Spring Boot**
- **JPA / Hibernate**

---

## 📌 Entity Overview

| Entity | Description | Key Relationships |
|--------|-------------|------------------|
| **Advisor** | Financial advisor | 1 advisor → many clients |
| **Client** | Customer with accounts | many clients → 1 advisor |
| **Portfolio** | Investment accounts owned by clients | many portfolios → 1 client |
| **Security** | Assets (stocks, bonds, etc.) | many securities → 1 portfolio |

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|--------|
| Java 17+ | Language |
| Spring Boot | Core framework |
| Spring Data JPA | ORM layer |
| H2 Database | Testing & dev database |
| Maven/Gradle | Build tool |

---

## 📂 Project Structure
src/main/java/com/wellsfargo/counselor/entity/
│
├── Advisor.java
├── Client.java
├── Portfolio.java
└── Security.java


