# FizzyCrave

FizzyCrave is a full-stack e-commerce web application for beverages and drinks, built using the MERN stack (MongoDB, Express.js, React, Node.js).

## Project Structure

The project is organized into two main directories:

- **client**: Frontend application built with React, Vite, and TailwindCSS
- **server**: Backend API built with Node.js, Express, and MongoDB

## Features

- 👤 User authentication and authorization
- 🛒 Shopping cart functionality
- 🔍 Product search and filtering
- 💳 Secure payment processing with PayPal
- 📦 Order management and tracking
- 📝 Product reviews and ratings
- 🏠 User address management
- 👑 Admin dashboard for product and order management

## Tech Stack

### Frontend
- React 18
- Redux Toolkit for state management
- React Router for navigation
- TailwindCSS for styling
- Radix UI components
- Axios for API requests
- Vite as the build tool

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- bcrypt for password hashing
- Cloudinary for image storage
- PayPal SDK for payment processing

## Getting Started

### Prerequisites
- Node.js (v16 or later)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
   ```
   git clone https://github.com/chauhan-varun/fizzycrave.git
   cd fizzycrave
   ```

2. Install server dependencies
   ```
   cd server
   npm install
   ```

3. Configure environment variables
   Create a `.env` file in the server directory with the following variables:
   ```
   PORT=5000
   MONGO_DB=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLIENT_URL=http://localhost:5173
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. Install client dependencies
   ```
   cd ../client
   npm install
   ```

5. Create a `.env` file in the client directory:
   ```
   VITE_API_URL=http://localhost:5000
   ```

### Running the Application

1. Start the backend server
   ```
   cd server
   npm run dev
   ```

2. Start the frontend development server
   ```
   cd client
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:5173`

## Deployment

- The frontend can be built using `npm run build` in the client directory
- The backend can be deployed to any Node.js hosting service
- MongoDB should be hosted in a production environment (MongoDB Atlas recommended)

## License

This project is licensed under the ISC License.

## Contributors

- Sangam Mukherjee (Author)
