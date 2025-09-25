# 🎭 ActorsDetail Management Portal  

## 📌 Project Overview  
**ActorsDetail Management Portal** is a Java-based web application that allows users to manage actor records efficiently. It showcases real-world implementation of **CRUD operations**, **soft deletion**, and **pagination** using **Spring Boot, Spring MVC, Spring Data JPA, JSP, and Hibernate**.  

This project is developed as part of **Java Full Stack Development training**.  

---

## ✨ Features  
- ➕ **Add New Actor** – Register actors with details (Name, Address, Category, Fee).  
- 📋 **View Actors List** – Display records in tabular format with pagination.  
- ✏️ **Update Actor** – Edit existing actor details.  
- ❌ **Soft Delete** – Records are not permanently deleted; instead marked as inactive.  
- 📄 **Pagination** – View data page by page for better readability.  
- 🏠 **Navigation** – Easy access to Home, Register, and Reports.  

---

## 🛠️ Tech Stack  
- **Backend:** Spring Boot, Spring MVC, Spring Data JPA, Hibernate  
- **Frontend:** JSP, JSTL, HTML, CSS  
- **Database:** MySQL / Oracle (configurable)  
- **Build Tool:** Maven  
- **Server:** Apache Tomcat (embedded)  

---

## 📂 Project Structure  
- **Entity Layer:** `ActorEntity` → Maps to DB table (`actors_details2`).  
- **VO Layer:** `ActorVO` → Data transfer object between layers.  
- **Repository Layer:** `IActorRepository` → Extends JPA repository.  
- **Service Layer:** `IActorMgmtService`, `ActorMgmtServiceImpl` → Business logic.  
- **Controller Layer:** `ActorOperationsController` → Handles HTTP requests.  
- **Views:** JSP pages  
  - `home_page.jsp`  
  - `register_actor_form.jsp`  
  - `edit_actor_form.jsp`  
  - `show_report.jsp`  
  - `show_report_pagination.jsp`  

---
