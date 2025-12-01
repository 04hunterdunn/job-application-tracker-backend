# Job Application Tracker — Legacy Spring Boot Backend

**🚨 Status: Archived – Replaced by Supabase + PostgreSQL architecture.**  
This repository contains the original backend API for my Job Application Tracker project, built using **Java**, **Spring Boot**, **Hibernate/JPA**, and a **MySQL** database.

As of late 2025, this backend is no longer used in production.  
The application has been fully migrated to a modern **React + Supabase** stack that provides:

- Built-in authentication  
- Row-Level Security (RLS)  
- Managed PostgreSQL  
- Direct frontend ↔ database access  
- No custom API server required  

---

## ✅ What This Backend Used To Do

This Spring Boot backend originally powered the full job tracking application and handled:

### ✔ REST API Endpoints  
- Create job applications  
- Get job applications  
- Update job applications  
- Delete job applications  

### ✔ Database Integration (MySQL)  
- Spring Data JPA + Hibernate  
- Entity relationships  
- Schema managed through JPA  
- Local development via MySQL

### ✔ Deployment / Operations  
- Multi-stage Dockerfile for container builds  
- Deployable to Render / Railway / Fly.io  
- CORS configuration for the frontend  

---

## 📦 Project Structure
```
src/
 ├── main/java/...  (controllers, repositories, services)
 └── main/resources/
      ├── application.properties
      └── other config files
Dockerfile
pom.xml
```

---

## 📌 Why This Repo Is Archived

The current version of the Job Application Tracker uses:

### 🚀 **Supabase Backend**
- Authentication  
- Row-Level Security  
- Postgres  
- Lightning-fast CRUD  
- No server maintenance required  

### 🎨 **React Frontend**
- Deployed on Vercel  
- Direct communication with Supabase  
- Clean UI and responsive layout  

The Spring Boot backend is preserved here as a **portfolio artifact** showing backend development experience.

---

## 🔗 Related Repositories

👉 **Current Production Frontend (React + Supabase)**  
(Insert your real frontend repo URL here)

👉 **Supabase configuration and client code**  
Stored in `/src/supabaseClient.js` in the frontend repo.

---

## 🛑 Security Notice

All real credentials and MySQL passwords have been removed or invalidated.  
This repository is safe to keep public.

---

## 🧰 Tech Stack (Legacy)

- Java 17  
- Spring Boot  
- Spring Web  
- Spring Data JPA  
- Hibernate  
- MySQL  
- Maven  
- Docker  

---

## ⚠️ Status

> **This repository is no longer maintained.**  
> It remains public to demonstrate backend architecture work and the evolution of the project.
