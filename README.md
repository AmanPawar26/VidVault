# VidVault Backend

## Table of Contents
1. 📖 [Introduction](#introduction)
2. 🛠️ [Tech Stack](#tech-stack)
3. ✨ [Features](#features)
4. ⚙️ [Installation & Setup](#installation--setup)


## Introduction
VidVault is a backend system for a video-sharing platform that manages user authentication, secure video uploads, and robust session management. Built with Node.js and Express.js, it leverages MongoDB for data storage and Cloudinary for media handling.

## Tech Stack
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT (JSON Web Tokens)
- **File Uploads**: Cloudinary, Multer
- **API Testing**: Postman

## Features
- **User Authentication**: Implements secure authentication using JWT, with refresh tokens for session handling.
- **Video Uploads**: Enables secure video and media uploads through Cloudinary.
- **REST API**: Provides endpoints for managing user data and media content.
- **Error Handling**: Centralized error-handling middleware for consistent API responses.
- **API Security**: Middleware for token validation ensures only authenticated users can access protected routes.

## Installation & Setup

To run VidVault locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/vidvault-backend.git
     ```

   
2. Navigate to the project directory:
  ```bash
   cd vidvault-backend
   ```

   
3. Install dependencies for the backend:
  ```bash
   npm install
   ```

4. Set up environment variables by creating a .env file in the root directory. Example:
   ```bash
   MONGO_URI=your_mongodb_connection_string
   CLOUDINARY_CLOUD_NAME=your_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   JWT_SECRET=your_jwt_secret
   ```
5. Start the backend server:
   ```bash
   npm run dev
   ```

