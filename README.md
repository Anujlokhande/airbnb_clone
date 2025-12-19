# Airbnb Clone

A full-stack Airbnb-inspired web application built using Node.js, Express, MongoDB, and EJS.  
The application supports user authentication, property listings, reviews, and secure CRUD operations.

---

## Project Overview

This project replicates core Airbnb functionalities such as listing properties, user authentication, reviews, and access control.  
It demonstrates backend development using Express.js, MongoDB with Mongoose, and server-side rendering with EJS.

---

## Features

- User authentication (Sign up, Login, Logout)
- Role-based access control
- Create, edit, and delete property listings
- Review and rating system
- Authorization for listings and reviews
- Server-side rendering using EJS templates
- Input validation and error handling
- RESTful routing structure
- Clean MVC architecture

---

## Tech Stack

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose

**Frontend**
- EJS
- HTML, CSS, JavaScript

**Other Tools**
- Express middleware
- Session-based authentication
- MVC design pattern

---

## Application Routes

### Authentication Routes

| Method | Route | Description |
|------|------|------------|
| GET | `/signup` | User registration page |
| POST | `/signup` | Register new user |
| GET | `/login` | Login page |
| POST | `/login` | Authenticate user |
| GET | `/logout` | Logout user |

---

### Listing Routes

| Method | Route | Description |
|------|------|------------|
| GET | `/listings` | View all listings |
| GET | `/listings/new` | Create new listing |
| POST | `/listings` | Add listing |
| GET | `/listings/:id` | View listing details |
| GET | `/listings/:id/edit` | Edit listing |
| PUT | `/listings/:id` | Update listing |
| DELETE | `/listings/:id` | Delete listing |

---

### Review Routes

| Method | Route | Description |
|------|------|------------|
| POST | `/listings/:id/reviews` | Add review |
| DELETE | `/listings/:id/reviews/:reviewId` | Delete review |

---

## Architecture

- MVC (Model-View-Controller) architecture
- RESTful routing
- Middleware-based authorization
- Modular controller structure

---

## Author

Anuj Lokhande  
Full Stack Developer
