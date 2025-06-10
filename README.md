# 🏨 Hotel Management System

A full-stack Hotel Management System built using **Spring Boot** for the backend and **React.js** for the frontend. The application provides functionality for managing bookings, rooms, customers, payments, and staff.

---

## 🚀 Features

### 🖥️ Frontend (React.js)
- Responsive UI with modern design
- Dashboard with key metrics
- Room listings and availability status
- Customer booking form
- Staff and customer management pages
- Login/Signup with authentication

### ⚙️ Backend (Spring Boot)
- RESTful APIs for rooms, bookings, customers, payments, and users
- JWT-based authentication and role-based authorization
- MySQL/PostgreSQL database integration
- Input validation and error handling
- CRUD operations for all modules

---

## 🏗️ Technologies Used

### 📌 Backend
- Java 17+
- Spring Boot
- Spring Security
- Spring Data JPA
- MySQL / PostgreSQL
- Maven

### 📌 Frontend
- React.js
- Axios
- React Router
- Tailwind CSS / Bootstrap (optional)

---

## 📂 Project Structure

hotel-management-system/
├── backend/
│ └── src/
│ ├── main/
│ │ ├── java/com/bagabo/hotel/
│ │ │ ├── controller/
│ │ │ ├── model/
│ │ │ ├── repository/
│ │ │ ├── service/
│ │ │ └── security/
│ │ └── resources/
│ │ └── application.properties
│ └── pom.xml
└── frontend/
└── src/
├── components/
├── pages/
├── services/
├── App.js
└── index.js

yaml
Copy
Edit

---

## 🛠️ Installation

### 🧩 Prerequisites
- Node.js & npm
- Java 17+
- Maven
- MySQL or PostgreSQL

### 🔙 Backend Setup

```bash
cd backend
# Update DB credentials in src/main/resources/application.properties
mvn clean install
mvn spring-boot:run
🌐 Frontend Setup
bash
Copy
Edit
cd frontend
npm install
npm start
🔒 Authentication
JWT-based login

Roles: ADMIN, RECEPTIONIST, CUSTOMER

Authorization handled via backend filters and frontend route protection

📬 API Endpoints
POST /api/auth/login

GET /api/rooms

POST /api/bookings

GET /api/customers

DELETE /api/bookings/{id}

...and more

(Full documentation in Postman_collection.json)

📸 Screenshots
(Include screenshots of the dashboard, room booking form, customer management, etc.)

📄 License
This project is licensed under the MIT License.
