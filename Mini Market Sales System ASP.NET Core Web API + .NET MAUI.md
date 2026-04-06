![.NET](https://img.shields.io/badge/.NET-8-blue)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET-Core-green)
![MAUI](https://img.shields.io/badge/.NET-MAUI-purple)
![SQL Server](https://img.shields.io/badge/Database-SQL%20Server-red)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)
![REST API](https://img.shields.io/badge/API-REST-black)

# Mini Market Sales & Order Management System

Full stack mobile market sales and order management system built with **ASP.NET Core Web API** and **.NET MAUI**.

The project includes authentication, product management, shopping cart, order processing, address management and user profile features.

---

## Technologies

- ASP.NET Core Web API
- .NET MAUI
- SQL Server
- Entity Framework Core
- JWT Authentication
- REST API

---

## Features

- 🔐 User authentication (JWT)
- 📦 Product and category listing
- 🛒 Shopping cart management
- 📑 Order creation and tracking
- 📍 Address management
- 👤 Profile management
- 🔎 Search functionality
- 🎁 Gift card support
---

# Application Screenshots

## Home Page

<p align="center">
  <img src="screenshots/home.jpg" width="250"/>
</p>

The home page displays product categories and allows users to select a delivery address.

---

## Category Listing

<p align="center">
  <img src="screenshots/home2.jpg" width="250"/>
</p>

Users can browse different product categories.

---

## Authentication (Login & Registration)

<p align="center">
  <img src="screenshots/loginorregisterpage.jpg" width="250"/>
  <img src="screenshots/registerpage.jpg" width="250"/>
  <img src="screenshots/otpverify.jpg" width="250"/>
</p>

Users must log in before selecting an address or placing an order.

---

## Search Page

<p align="center">
  <img src="screenshots/searchpage.jpg" width="250"/>
   <img src="screenshots/searchpage2.jpg" width="250"/>
</p>

Users can search for products quickly using the search functionality.

---

## Cart Page

<p align="center">
  <img src="screenshots/cartpage.jpg" width="250"/>
   <img src="screenshots/cartpage2.jpg" width="250"/>
</p>

Products can be added or removed from the cart.

---

## Address Management

<p align="center">
  <img src="screenshots/myadresses.jpg" width="250"/>
</p>

Users can manage their delivery addresses.

---

## Map Address Selection

<p align="center">
  <img src="screenshots/map.jpg" width="250"/>
</p>

Users can select their location using the map.

---

## Order Page

<p align="center">
  <img src="screenshots/orderpage.jpg" width="250"/>
   <img src="screenshots/orderdetailpage.jpg" width="250"/>
</p>

Users can review and create orders.

---

## Payment Page

<p align="center">
  <img src="screenshots/paymentpage.jpg" width="250"/>
   <img src="screenshots/paymentpage5.jpg" width="250"/>
</p>

Users can select their preferred payment method.

---

## Profile Page

<p align="center">
  <img src="screenshots/accountpage.jpg" width="250"/>
   <img src="screenshots/editprofilepage.jpg" width="250"/>
</p>

Users can view and edit their profile information.

---

## API Documentation (Swagger UI)

<p align="center">
  <img src="screenshots/swagger.jpeg" width="850"/>
</p>

Swagger UI is used to explore and test the REST API endpoints of the system.

# API Architecture

The backend is built with ASP.NET Core Web API and follows a layered architecture:

- **Controllers** handle HTTP requests.
- **Services** contain business logic.
- **DTOs** are used for API data transfer.
- **Entities** represent database models.
- **Entity Framework Core** handles database operations.
---

# Database

SQL Server is used as the database.

The project uses **Entity Framework Core with Code First approach** for database migrations and schema management.

---

# Authentication

JWT based authentication is implemented for secure API access.

Users authenticate using **SMS verification (OTP)** and receive a **JWT token** for authorized API requests.

---

# Future Improvements

- Push notifications
- Real payment gateway integration
- Admin panel improvements
- Product image optimization
- Performance improvements

## 
The source code is currently kept private.
It can be shared upon request for review.
