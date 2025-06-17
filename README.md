# Smart-Service-Desk_Sprint1
 Sprint 1 sets up the backend foundation for the Smart Service Desk system with database modeling, Java OOP classes, JDBC integration, and basic ticket management using Oracle XE.

# 💡 Smart Service Desk - Cloud-Based Customer Support Platform

This project is a part of **Sprint 1** for the SmartInternz Talent Program. It focuses on backend development using Java and Oracle XE for a hypothetical company, **QuickHelp Inc.**, which provides IT support services.

## 🎯 Sprint 1 Goal
To design and implement the backend foundation of a smart ticketing system with support for:
- Java-based object-oriented design
- Oracle XE database with normalized tables
- JDBC integration for ticket and user operations
- Exception handling and queue simulation
- Auto-generated timestamps using Java's date/time API

## 📦 Features Implemented
- 🗂️ **Entity Classes**: `User`, `Agent`, `Category`, and `Ticket`
- 🛢️ **Normalized Oracle Tables** with foreign key constraints
- 🔁 **CRUD Operations** for Users and Tickets
- 🔌 **JDBC Integration** (Oracle thin driver)
- ⚠️ **Exception Handling** for SQL and invalid input
- ⏱️ **Auto Timestamping** for Ticket creation
- 🧾 **Ticket Queue Simulation** using Java Collections

## 🗃️ Technologies Used
- Java 21
- Oracle Database XE (21c)
- JDBC
- SQL*Plus / SQL Developer
- Git & GitHub

## 📁 How to Run
1. Clone the repository
2. Import Java files and ensure Oracle JDBC driver is added to classpath
3. Create Oracle tables using provided SQL scripts
4. Run `Main.java` to create users, agents, categories, and tickets
5. Observe ticket processing queue and update ticket status dynamically

## 📊 ER Diagram
Included in the `/docs` folder along with normalization report.

## ✅ Deliverables (Sprint 1)
- ✔️ Normalized ER Diagram
- ✔️ Java classes with proper structure and validation
- ✔️ SQL scripts and sample data
- ✔️ JDBC program for ticket creation and management

---



