# 🛒 ShopEase Fullstack E-Commerce Project

![ShopEase Banner](https://github.com/user-attachments/assets/d623b68b-023e-420f-90c4-143a9285780e)

--live link (-https://shop-ease-theta.vercel.app/)

Welcome to **ShopEase**, a fullstack e-commerce web application built with **React.js** on the frontend and **Spring Boot** on the backend. The app delivers a complete online shopping experience — product browsing, cart, user authentication, order processing, and more.

---

## 🛠️ Technologies Used

- **Frontend**: React.js, Redux, Tailwind CSS, Axios  
- **Backend**: Spring Boot, Spring Security, Spring Data JPA  
- **Database**: PostgreSQL  
- **Authentication**: JWT (JSON Web Tokens)  
- **Payment Gateway**: (Optional: Stripe / PayPal)  
- **Build Tools**: Maven (backend), Webpack (frontend)

---

## 🚀 Features

- 🏠 Home Page with product sections  
- 🔍 Category and Filter pages  
- 🛍️ Shopping Cart and Product Details  
- 🔐 User Authentication (Login/Register)  
- 💳 Secure Checkout with Order Summary  
- 🛠 Admin Dashboard (Product & Order Management)  
- 💾 PostgreSQL integration  
- 📦 REST APIs with Spring Boot  
- ✅ JWT-based Security and Role-based Access  

---


## 📦 Installation & Setup

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Java JDK (17 or above recommended)
- PostgreSQL (with a database created)
- Maven

---

### 🔧 Backend Setup (Spring Boot)

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/shopease.git
   cd shopease/backend
2. **Configure PostgreSQL**  
   Edit `src/main/resources/application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/shopease_db
   spring.datasource.username=your_db_username
   spring.datasource.password=your_db_password

   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect

   spring.security.jwt.secret=your_jwt_secret_key
3. cd ../frontend

4. npm install

-- folder structure
shopease/
├── backend/
│   └── src/
│       └── main/java/com/shopease/
│           ├── config/
│           ├── controller/
│           ├── model/
│           ├── repository/
│           └── service/
├── frontend/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── redux/
│       └── api/

