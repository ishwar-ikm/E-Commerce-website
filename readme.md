# E-Commerce website

E-Commerce website is a web application that provides an online shopping platform with features for user authentication, product management, cart functionality, and order processing. The application is built using Node.js, Express.js, and EJS templates.

## Features

### User Authentication

- **Signup:** Users can create an account by providing their email and password.
- **Login:** Existing users can log in using their credentials.
- **Logout:** Authenticated users can log out securely.

### Product Management

- **Product Listing:** View a list of products with details such as title, price, and description.
- **Product Details:** Click on a product to view detailed information.
- **Add to Cart:** Authenticated users can add products to their shopping cart.

### Cart Functionality

- **View Cart:** Users can see the products in their cart along with the quantity.
- **Delete from Cart:** Remove items from the cart.
- **Order Now:** Place an order with the items in the cart.

### Order Processing

- **Order History:** Users can view their order history.
- **Invoice:** Access detailed invoices for each order.

### Navigation

- **Main Navigation:** Navigate through different sections of the application, including shop, products, cart, and user-specific sections.
- **Mobile Navigation:** Responsive design with a mobile-friendly navigation menu.

## Project Structure

- **Controllers:** Handle the application's logic, such as user authentication and authorization.
- **Models:** Define the structure of the MongoDB documents, including the User model.
- **Routes:** Define the application's routes, including login, registration, and password reset routes.
- **Views:** Utilize EJS templates to render the HTML views for different pages.
- **Public:** Contains static assets like stylesheets and client-side scripts.
- **Includes:** Reusable EJS partials for the head and end of HTML documents.
- **Middleware:** Custom middleware functions, such as authorization checks.
- **Data:** Contains the PDFs for the invoice.
- **Images:** Contains the images of the products.

## Setup

1. Clone the repository
2. Install dependencies: `npm install`
3. Configure MongoDB: Update the MongoDB connection URI in the `app.js` file.
4. Configure Nodemailer: Update email and app password for sending emails in controller/login.js in transporter function on line 8
5. Run the application: `npm start`
6. Open the application in your browser: `http://localhost:3000`

## Dependencies

The project relies on the following npm packages:

- **bcryptjs (^2.4.3):** Used for password hashing.
- **body-parser (^1.18.3):** Middleware to parse incoming request bodies.
- **connect-flash (^0.1.1):** Middleware for flash messages.
- **connect-mongodb-session (^2.0.3):** MongoDB session store for Express.
- **csurf (^1.9.0):** Middleware for CSRF protection.
- **ejs (^2.6.1):** Embedded JavaScript templates for rendering views.
- **express (^4.16.3):** Web framework for Node.js.
- **express-session (^1.15.6):** Session management middleware for Express.
- **express-validator (^5.3.0):** Middleware for input validation in Express.
- **mongodb (^3.1.6):** Official MongoDB driver for Node.js.
- **mongoose (^5.2.17):** MongoDB object modeling tool for Node.js.
- **multer (^1.4.0):** Middleware for handling `multipart/form-data`.
- **nodemailer (^4.6.8):** Library for sending emails.
- **pdfkit (^0.14.0):** PDF generation library.

## Technologies used

- Node.js
- Express.js
- EJS templates
- MongoDB
- CSS


