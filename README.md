# A2Z Shopping App - Your One-Stop Shop Solution 🛒

![A2Z Shopping App](https://img.shields.io/badge/A2Z%20Shopping%20App-v1.0.0-brightgreen) ![Node.js](https://img.shields.io/badge/Node.js-v14.17.0-green) ![React](https://img.shields.io/badge/React-v17.0.2-blue) ![MongoDB](https://img.shields.io/badge/MongoDB-v4.4.1-orange) ![Express](https://img.shields.io/badge/Express-v4.17.1-yellowgreen) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-v2.1.2-blueviolet)

[Download Latest Release](https://github.com/rizkymilham/A2Z---Shop-App/releases) 

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The A2Z Shopping App is a full-stack application designed for online shopping. It allows users to browse products, manage their cart, and securely make payments. Built with a modern tech stack, this app ensures a smooth and efficient shopping experience.

## Features

- **User Authentication**: Secure login and registration using JWT.
- **Product Management**: CRUD operations for products.
- **Shopping Cart**: Add, remove, and update items in the cart.
- **Order Management**: View and manage past orders.
- **Payment Integration**: Support for Stripe and other payment gateways.
- **Dashboard**: Admin dashboard for managing products and orders.
- **Role-Based Access Control**: Different access levels for users and admins.
- **Responsive Design**: Built with TailwindCSS for a modern look on all devices.

## Technologies Used

- **Frontend**: React, Redux, TailwindCSS
- **Backend**: Node.js, Express
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT
- **Caching**: Redis
- **Cloud Storage**: Cloudinary for image uploads
- **Payment Gateway**: Stripe

## Installation

To set up the A2Z Shopping App locally, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/rizkymilham/A2Z---Shop-App.git
   cd A2Z---Shop-App
   ```

2. **Install Dependencies**:

   For the backend:

   ```bash
   cd server
   npm install
   ```

   For the frontend:

   ```bash
   cd client
   npm install
   ```

3. **Set Up Environment Variables**:

   Create a `.env` file in the `server` directory and add the following variables:

   ```plaintext
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_URL=your_cloudinary_url
   STRIPE_SECRET_KEY=your_stripe_secret_key
   REDIS_URL=your_redis_url
   ```

4. **Run the Application**:

   Start the backend server:

   ```bash
   cd server
   npm start
   ```

   Start the frontend application:

   ```bash
   cd client
   npm start
   ```

The application should now be running on `http://localhost:3000`.

## Usage

Once the application is running, you can access it via your web browser. The following steps outline how to use the app:

1. **Register/Login**: Create an account or log in with existing credentials.
2. **Browse Products**: Navigate through the product listings.
3. **Manage Cart**: Add items to your cart, view, and update quantities.
4. **Checkout**: Proceed to checkout and complete your purchase using Stripe.
5. **Admin Dashboard**: Access the dashboard for managing products and orders (admin role required).

## API Endpoints

The A2Z Shopping App provides several API endpoints for interacting with the backend. Below are some key endpoints:

### User Authentication

- **POST** `/api/auth/register`: Register a new user.
- **POST** `/api/auth/login`: Log in a user.

### Products

- **GET** `/api/products`: Get all products.
- **POST** `/api/products`: Create a new product (admin only).
- **PUT** `/api/products/:id`: Update a product (admin only).
- **DELETE** `/api/products/:id`: Delete a product (admin only).

### Cart

- **GET** `/api/cart`: Get current user's cart.
- **POST** `/api/cart`: Add an item to the cart.
- **PUT** `/api/cart`: Update cart item quantities.
- **DELETE** `/api/cart/:id`: Remove an item from the cart.

### Orders

- **GET** `/api/orders`: Get all orders (admin only).
- **POST** `/api/orders`: Create a new order.

### Payments

- **POST** `/api/payments`: Process a payment.

## Contributing

Contributions are welcome! To contribute to the A2Z Shopping App, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your forked repository.
5. Create a pull request describing your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please reach out:

- **Author**: Rizky Milham
- **Email**: rizkymilham@example.com
- **GitHub**: [rizkymilham](https://github.com/rizkymilham)

For the latest updates and releases, please visit [Releases](https://github.com/rizkymilham/A2Z---Shop-App/releases).