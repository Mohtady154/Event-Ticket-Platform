# 🎟️ Event Ticketing Platform — Full-Stack (Spring Boot + React)

A complete **full-stack event ticketing system** that allows organizers to manage events, attendees to purchase tickets, and staff to validate tickets using QR codes.
The project implements real-world production patterns including **authentication**, **role-based access**, **domain-driven design**, and **modular architecture**.

---

## 🚀 Features

### 🎫 Event Management

* Create, update, delete events
* Publish/unpublish events
* Advanced event search & filtering
* Manage ticket types (VIP, Regular, Early Bird)

### 👤 User Flows

* **Organizer:** Manage events
* **Attendee:** Browse events, purchase tickets
* **Staff:** Validate tickets at entry

### 🔐 Security

* Keycloak authentication
* Spring Security with role-based access control
* Automatic user provisioning

### 🎟 Ticketing System

* Ticket purchase flow
* Unique QR code generation
* Real-time ticket validation
* Audit logs for all actions

### 🌐 REST API

* Clean modular controllers
* DTO mapping via MapStruct
* Consistent request/response structure
* Global exception handling

### 🖥 Frontend

* Fully responsive React + Vite UI
* Smooth UX for all user roles
* Clean and modern dashboards
* API integration & error handling

---

## 🏗️ System Architecture

```
Frontend (React + TypeScript + Vite)
        ↓
REST API (Spring Boot)
        ↓
PostgreSQL Database
        ↓
Keycloak Authentication Server
```

Designed with separation of concerns, clean layers, and scalable business logic.

---

## 📦 Tech Stack

### 🔧 **Backend**

* Java 17
* Spring Boot
* Spring Data JPA
* Spring Security
* Keycloak
* MapStruct
* Lombok
* PostgreSQL
* QR Code Generator
* Docker & Docker Compose

### 🎨 **Frontend**

* React
* TypeScript
* Vite
* Axios


