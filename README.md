# 📝 To-Do Application

A simple, interactive To-Do list application built using **Spring Boot**, **MySQL**, and **Thymeleaf**.  
It allows users to add, mark as completed, and delete tasks — with smooth animations like strikethrough and color changes when marking tasks as done.

---

## ✨ Features
- Add tasks with a title.
- Mark tasks as completed ✅.
- Strikethrough animation when task is done.
- Title color changes after completion.
- Delete tasks from the list.
- Stores tasks in MySQL database.
- Responsive and minimal UI.

---

## 📦 Requirements

### **1. Software**
- [Java 17+](https://adoptium.net/)
- [Maven 3+](https://maven.apache.org/)
- [MySQL 8+](https://dev.mysql.com/downloads/)
- [Git](https://git-scm.com/)

### **2. Dependencies (Managed via Maven)**
- Spring Boot Starter Web
- Spring Boot Starter Thymeleaf
- Spring Boot Starter Data JPA
- MySQL Connector/J
- Spring Boot DevTools (Optional, for live reload)

---
## **Configurations

## **1. Create a database in MySQL:
- CREATE DATABASE todo-app;

## **2. Update your application.properties file:
- spring.datasource.url=jdbc:mysql://localhost:3306/todo-app
- spring.datasource.username=YOUR_DB_USERNAME
- spring.datasource.password=YOUR_DB_PASSWORD
- spring.jpa.hibernate.ddl-auto=update

## **3. Build & Run
- mvn spring-boot:run   

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/todo-application.git
   cd todo-application
