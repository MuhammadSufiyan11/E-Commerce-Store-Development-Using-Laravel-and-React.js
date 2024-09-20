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
   
2. **Install Dependencies:**:
    ```bash
    composer install
3. **Set Up Environment Variables:** Copy the .env.example file to .env and update database and mail configurations:
    ```bash
    cp .env.example .env
    
4. **Generate Application Key:**
    ```bash
    php artisan key:generate
    
5. **Run Migrations and Seed the Database:**
   ```bash
   php artisan migrate --seed

6. Start the Laravel Server:
   ```bash
   php artisan serve

### Frontend (React.js Setup)

1. **Navigate to the Frontend Directory:**
   ```bash
   cd frontend
   
2. **Install Dependencies:** Install npm packages:
   ```bash
   npm install

3. **Run the React Development Server:**
   ```bash
   npm start

4. **Access the Application:**
   - Laravel backend: http://localhost:8000
   - React frontend: http://localhost:3000

### Usage Instructions
**1. Login/Register:**
- nVisit http://localhost:3000 to log in or register as a new user.
  
**2. Browse Products:**
- Navigate through the product listings and add items to your shopping cart.

**3. Add to Cart:**
- Add products to your cart and update the quantity or remove items as needed.
  
**4. Place Orders:**
- Complete the checkout process through the payment page and view your order history.
  
**5. Admin Dashboard:**
- Admins can manage products and view all placed orders through the admin dashboard (http://localhost:3000/admin).

### Technologies Used
- Backend: Laravel 9.x (PHP)
- Frontend: React.js, HTML, CSS, JavaScript
- Database: MySQL
- Authentication: JWT (JSON Web Tokens)
- Version Control: Git
- Hosting: Can be deployed on platforms like Heroku, Netlify (for frontend), or other free hosting services.

### Contributing
**If you'd like to contribute to this project:**

1. Fork the repository.
2. Create a new branch for your feature (git checkout -b feature-name).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature-name).
5. Open a pull request.



