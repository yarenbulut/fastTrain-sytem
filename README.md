# 🚄 FastTrain System — Full Stack High-Speed Train Ticket Reservation Platform

**FastTrain System** is a full-featured web application for booking high-speed train tickets.  
It features a modern frontend built with **React + TypeScript + TailwindCSS**, and a robust backend powered by **Spring Boot (Java)** and **MySQL**.

This project simulates a real-life ticket booking system, with role-based access for **users**, **admins**, and **managers**.

---

## 🧩 Key Features

### 👤 User Module
- Homepage with login and sign-up redirection
- Login & Forgot Password functionality
- User Dashboard including:
  - **My Tickets**: View and manage personal tickets
  - **Available Journeys**: Browse all upcoming journeys with time & price
  - **Seat Selection**: Interactive seat picking interface
  - **Payment Screen**: Complete the transaction securely

### 👮 Admin Module
- Admin login and welcome screen
- **Pending Users**: View and approve registered users
- **Edit Tickets**: Modify journey details (time, price, etc.)
- **Add Journey**: Add new journeys with schedule and pricing

### 👔 Manager Module
- Manager Dashboard
- **Employee Management**: Hire or fire staff members

---

## 🧱 Project Structure

train-system-main/ ├── train-app-1/ # Frontend (React + TypeScript) │ ├── src/pages/ # Screens for each role (User, Admin, Manager) │ ├── src/components/ # Shared UI components │ ├── App.tsx / main.tsx # Routing and app entry │ └── tailwind.config.js # Tailwind configuration ├── bbackend/ # Backend (Spring Boot + Java) │ ├── src/main/java/... # Controllers, Services, Entities │ ├── src/main/resources/ # Application configs │ └── application.properties # MySQL DB configuration ├── fast_train_system.sql # MySQL schema + seed data └── README.md # Project documentation


---

## 🚀 Getting Started

### 📦 Prerequisites

- [Node.js](https://nodejs.org/)
- [Java 17+](https://adoptium.net/)
- [MySQL Server](https://www.mysql.com/)
- [Maven](https://maven.apache.org/)
- Optional: IntelliJ IDEA (for backend), VSCode (for frontend)

---

### 🔧 Backend Setup (Spring Boot)

```bash
cd bbackend
./mvnw spring-boot:run


