# E-Commerce Platform

## Overview

 online food delivery app, seamlessly connecting hungry users with a diverse array of local culinary delights. Built with MongoDB, Express, React, and Node.js, our platform ensures a user-friendly interface for browsing, ordering, and tracking deliveries in real-time. Enjoy a hassle-free experience with secure authentication, interactive menus, and efficient payment processing. Elevate your dining experience with our MERN-powered app, combining cutting-edge technology and mouthwatering options for the ultimate convenience in food delivery.

## Backend

### Technologies Used

- **Node.js/Express**: Powerful backend framework.
- **MongoDB/Mongoose**: Efficient database management.
- **Json Web Tokens (JWT)**: Secure authentication and authorization.
- **OAuth2**: Integration for user authentication.
- **Nodemailer**: Handles email functionalities.
- **Multer**: Middleware for smooth file uploads.
- **Cloudinary**: Cloud-based media storage service.
- **Socket.io**: Enables real-time order notifications.
- **Bcrypt**: Library for password encryption.

### Environment Variables

Make sure to set the following environment variables:

- `HOST`
- `MONGODB_URI`
- `JWT_SECRET_KEY`
- `JWT_EMAIL_CONFIRMATION_KEY`
- `JWT_RESET_FORGOTTEN_PASSWORD_KEY`
- `OAUTH_USER`
- `OAUTH_CLIENT_ID`
- `OAUTH_CLIENT_SECRET`
- `OAUTH_REFRESH_TOKEN`
- `CLOUDINARY_NAME`
- `CLOUDINARY_KEY`
- `CLOUDINARY_SECRET`

### Features

- JWT-based user authentication.
- Password encryption using bcrypt.
- Account validation and functional contact form with Nodemailer and Googleapis OAuth2.
- Route access control based on user authorization.
- Media storage with Multer and Cloudinary.
- Real-time new orders and order updates through Socket.io.
- RESTful API supporting GET, PUT, POST, and DELETE.
- Pre-configured Mongoose setup with default categories, roles, and admin/moderator users.

### Routes

- USERS
- PRODUCTS
- CATEGORIES
- ORDERS
- NEWSLETTER
- CONTACT
- AUTH (Login/Sign Up/Forgot Password/Reset Password)

## Frontend

### Technologies and Tools

- **React.js**: Frontend library for dynamic UIs.
- **Style-Components**: Flexible styling solution for React components.
- **React-hook-form**: Streamlines form validation in React.
- **React-router-dom**: Facilitates routing in React applications.
- **React hooks**: Manages state and lifecycle efficiently.
- **Swiper**: Feature-rich slider library for custom carousels.
- **Socket.io-client**: Client-side implementation for real-time communication.

### Features

- Interaction with the backend through API Rest .
- Unit test examples.
- Lazy Load components and code splitting.
- Products and orders section skeletons.
- Custom Auto-played sliders with dot indicators and controls.
- Latest products carrousel using swiper.js library.
- Navbar responsive and animated .
- Complete authentication system width signup/email validation/login/ forgot password support.
- Access to Public and Private routes base on roles.
- Functional contact section with form validation.
- Loading modal and loading form indicators.
- Shopping cart.
- Editable User profile.
- Products and orders section with sorter, filter and search bar.
- URL able to storage the user search
- pagination.
- User orders tracker page.
- Real time order notifications.
- Dashboard with users, categories, orders and products management system.

## Getting Started
 
1. Clone the repository.
2. Install dependencies using `npm install` for both the backend and frontend.
3. Set up the required environment variables.
4. Run the backend server using `npm start`.
5. Run the frontend application using `npm start`.
6. Access the application in your browser at `http://localhost:3000`.

