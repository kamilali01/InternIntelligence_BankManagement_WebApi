# Bank Management System API

This project is a RESTful Web API developed using ASP.NET Core as part of my early backend development experience. It demonstrates the design of a layered architecture for managing banking-related operations such as users, accounts, cards, and orders.

The system focuses on clean separation of concerns, modular design, and basic enterprise-level backend practices.

---

## 🚀 Features

- User management (create, retrieve, manage users)
- Bank account operations
- Card management system
- Order processing functionality
- Layered architecture (API, Business Logic, Data Access)
- RESTful API design principles

---

## 🏗️ Architecture

The project follows a **multi-layered architecture**:

- **Presentation Layer (API)**
  - Controllers handle HTTP requests and responses

- **Business Logic Layer (BLL)**
  - Contains service implementations and business rules
  - Uses interfaces for abstraction

- **Data Access Layer (DAL)**
  - Repository pattern implementation
  - Handles database interactions

- **DTOs & Mappers**
  - Data transfer between layers
  - Object transformation

---

## 🧩 Technologies Used

- ASP.NET Core Web API
- C#
- Entity Framework Core
- SQL Server (or configured database)
- RESTful API principles

---
