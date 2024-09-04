# eCommerce Website

## Project Overview
This is a mini eCommerce website built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The project showcases basic functionalities of an online store, including product listings, shopping cart, user authentication, and order management.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [API Endpoints](#api-endpoints)
- [Folder Structure](#folder-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features
- User authentication (Sign Up, Login)
- Product listings
- Product search functionality
- Shopping cart
- Order placement and management

## Technologies Used

### Frontend
- **React.js**: JavaScript library for building user interfaces.
- **Redux**: State management library for React.
- **React Router**: For navigation within the app.
- **Bootstrap**: For responsive design and styling.

### Backend
- **Node.js**: JavaScript runtime for building the backend.
- **Express.js**: Framework for building APIs and handling server-side logic.
- **MongoDB**: NoSQL database for storing product, user, and order information.
- **Mongoose**: ODM library for MongoDB, used for managing relationships between data.

### Other Tools
- **JWT**: For secure authentication.
- **bcrypt**: For password hashing.
- **Postman**: For API testing.

## Installation

### Prerequisites
- Node.js
- MongoDB
- Git

### Clone the repository
```bash
git clone https://github.com/LokeshS1411/LD-cart.git

```

### Install dependencies for backend
```bash
cd backend
npm install
```

### Install dependencies for frontend
```bash
cd frontend
npm install
```

### Environment Variables
Create a `.env` file in the root of your backend directory and add the following:
```
MONGO_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret_key
```

## Running the Project

### Start the backend server
```bash
cd backend
npm start
```
The backend server will run on `http://localhost:5000`.

### Start the frontend server
```bash
cd frontend
npm run dev
```
The frontend server will run on `http://localhost:3000`.

### Accessing the website
Open your browser and navigate to `http://localhost:3000` to view the eCommerce website.

## API Endpoints

### Authentication
- `POST /api/users/register` - Register a new user
- `POST /api/users/login` - Login a user

### Products
- `GET /api/products` - Get all products
- `GET /api/products/:id` - Get product by ID

### Orders
- `POST /api/orders` - Create a new order
- `GET /api/orders/:id` - Get order by ID

## Future Enhancements
- Add product reviews and ratings
- Implement payment gateway integration
- Add user profile management

##  OutPut
![28 08 2024_21 30 14_REC](https://github.com/user-attachments/assets/b3343d98-1a64-4339-8deb-1ef48eb3d05d)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
