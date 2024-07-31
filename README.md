# Shopio Backend

This is the backend service for the Shopio e-commerce web application. It is built using Node.js, Express.js, and MongoDB. The backend handles user authentication, product management, and order processing.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Running the Server](#running-the-server)
- [API Endpoints](#api-endpoints)
- [Project Structure](#project-structure)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication and authorization with JWT
- CRUD operations for products
- Shopping cart and order management
- Role-based access control for admin functionalities

## Technologies Used

- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- Bcrypt for password hashing

## Getting Started

Follow these instructions to set up and run the backend server locally.

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed and running locally or a MongoDB Atlas account

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/NandishM0618/shopio-backend.git
   cd shopio-backend
   ```
2. Install dependencies
   ```bash
   npm install
   ```
3. Set up environment variables
   ```bash
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
4. Run Development Server
   ```bash
   node index.js

   ```
