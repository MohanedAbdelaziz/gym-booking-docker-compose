# Gym Booking App

A simple gym booking system built with the MERN Stack (MongoDB, Express, React, Node.js).  
This project currently supports user authentication and a basic dashboard.

---

## **Current Features**

- User Registration (Sign Up)
- User Login
- Token stored in `localStorage`
- Display user info on Dashboard

---

## **Tech Stack**

- **Frontend:** React.js
- **Backend:** Node.js + Express
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **HTTP:** REST APIs using `fetch`

---

## **Versions Used**

### **Frontend (React)**
- React: `19.1.0`
- React Router: `7.5.0`
  
### **Backend (Node.js + Express)**
- Node.js: `16.18.0` 
- Express: `5.1.0` 
- JWT: `9.0.2` 
- Bcrypt: `3.0.2` 

### **MongoDB**
- MongoDB Version: `6.15.0` 

### **Development Tools**
- npm: `9.7.1`

---

## Testing Tools

This project uses the following tools for testing and API validation:

- **Postman**: Used for testing RESTful API endpoints during development.
  - Test login, register, and booking functionalities.
  - Check for correct status codes and response data.
  - Simulate requests with different user roles (admin/client).

---

## **Running the Project Locally**

### 1. Run .yaml file
```bash
docker-compose up --build
```


### Make sure to create a .env file inside the backend folder with the following content:
```bash
MONGO_URI=mongodb://localhost:27017/gymdb
```

## **Upcoming Features**

- Admin can create and manage slots
- Users can book available gym slots
- Admin dashboard for user and slot management
- Mobile responsive UI

