# Flight Booking App (MERN Stack)

## Overview

This project is a full-stack Flight Booking Application developed as part of the Smart Bridge Internship. It allows users to register, log in, search for flights, book tickets, and manage their bookings. Admins and approved operators can manage flights and users. The application demonstrates real-world skills in authentication, CRUD operations, RESTful APIs, and database management.

---

## Tech Stack

- **Frontend:** React.js
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (with Mongoose)
- **Other Tools:** bcrypt, CORS

---

## Features

- **User Registration & Login:** Secure authentication for users and operators.
- **Operator Approval:** Admins can approve or reject operator accounts.
- **Flight Management:** Add, update, and view flights (admin/operator).
- **Booking System:** Search for flights, book tickets, and manage bookings.
- **Admin Dashboard:** Manage users, operators, and flights.
- **Protected Routes:** Only authorized users can access certain pages.

---

## Directory Structure

```
Flight-Booking-App/
│
├── client/           # React frontend
│   ├── public/
│   └── src/
│       ├── assets/
│       ├── components/
│       ├── context/
│       ├── pages/
│       ├── RouteProtectors/
│       └── styles/
└── server/           # Express backend
    ├── index.js
    └── schemas.js
```

---

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB

### Installation

1. **Clone the repository:**

   ```
   git clone <repository-url>
   cd Flight-Booking-App
   ```

2. **Install server dependencies:**

   ```
   cd server
   npm install
   ```

3. **Install client dependencies:**

   ```
   cd ../client
   npm install
   ```

4. **Configure environment variables:**

   - Set up your MongoDB connection string in the backend as needed.

5. **Run the backend server:**

   ```
   cd ../server
   npm start
   ```

6. **Run the frontend:**
   ```
   cd ../client
   npm start
   ```

---

## Usage

- Register as a user or operator.
- Operators require admin approval before accessing operator features.
- Search for flights, book tickets, and view your bookings.
- Admins can manage users, operators, and flights.

---

## Acknowledgements

- Smart Bridge Internship Program
- MERN Stack
