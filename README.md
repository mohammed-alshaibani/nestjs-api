# E-commerce App with NestJS

This is a basic e-commerce application built with NestJS, following the tutorial from [LogRocket's blog](https://blog.logrocket.com/how-build-ecommerce-app-nestjs/). The application demonstrates the foundational setup and functionalities needed for an online store, including user management, product listing, and order processing.

## Features

- **User Authentication**:

  - Register and login with JWT-based authentication.
  - Role-based access control for admin and customers.

- **Product Management**:

  - Add, edit, delete, and list products.
  - Search and filter products by categories or price.

- **Order Management**:
  - Create and view orders.
  - Manage order status.

## Technologies Used

- **NestJS**: Backend framework for building scalable applications.
- **TypeORM**: Database interaction with a structured schema.
- **PostgreSQL**: Database for storing e-commerce data.
- **JWT**: Secure user authentication.

Project Structure
src/
auth/: Handles user authentication and authorization.
users/: Manages user data and roles.
products/: CRUD operations for products.
cart/:Handles products on cart
