# E-Commerce Store - Laravel & React.js

## Project Overview

This is a full-stack **e-commerce application** developed using **Laravel** for the backend and **React.js** for the frontend. The application includes functionalities such as user authentication, product listings, shopping cart management, order processing, and payment simulation. This project aims to deliver a fully functional online store with an intuitive interface and responsive design.

## Project Structure

- **Backend (Laravel)**: 
  - Handles the API for user management, product handling, orders, and payments.
  - Models such as `Product`, `Order`, `User`, and `Cart` represent the key entities.
  - Routes are set up to handle API requests for managing the products, orders, and user login.

- **Frontend (React.js)**:
  - Components handle the product listings, cart interactions, and order confirmation pages.
  - Routing is done using `react-router-dom` for navigation across pages like login, products, and payments.
  - State management is done using React's `useState` and `useEffect` hooks.

- **Database (MySQL)**:
  - Stores user data, products, orders, and shopping cart information.
  - Managed using Laravel’s **Eloquent ORM** and migrations for creating and updating database structures.

## Key Features

- **Product Management**: 
  - Display products with images, prices, and details.
  - Admins can add, update, or remove products from the store.
  
- **Shopping Cart**: 
  - Users can add products to the cart, update quantities, and view the total price.
  
- **User Authentication**: 
  - Secure user registration and login using JWT.
  - Admin and customer roles for managing store functionalities.

- **Order Processing**: 
  - Users can place orders and view their order history.
  - Admins can track and manage all orders.

- **Payment Simulation**:
  - Mock payment integration to simulate payment processes.
  
- **Responsive Design**: 
  - Fully responsive design for mobile, tablet, and desktop using Flexbox and Grid.

## Installation Instructions

### Backend (Laravel Setup)

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/ecommerce-laravel-react.git
   cd ecommerce-laravel-react/backend
