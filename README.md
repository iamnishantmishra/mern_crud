# MERN Demo Project

This repository contains a demo MERN (MongoDB, Express.js, React.js, Node.js) project designed to showcase the fundamental working knowledge of JavaScript, React.js, and Node.js. **The project is actively being updated every day, ensuring you have access to the latest features and improvements.**

## Project Overview

The MERN Demo Project aims to demonstrate the following key technologies and concepts:

- **JavaScript**: The project extensively uses JavaScript, the programming language of the web, to build the frontend and backend components.
- **React.js**: The frontend of the application is built using React.js, a popular JavaScript library for building user interfaces.
- **Node.js**: The backend is powered by Node.js, an open-source, server-side JavaScript runtime environment.
- **Express.js**: The project utilizes Express.js, a fast and minimalist web application framework for Node.js, to handle backend routing and API development.
- **MongoDB**: The application stores and retrieves data using MongoDB, a popular NoSQL database.

## Project Structure

The project follows a structured layout to separate the frontend and backend components:

- **`client`**: (NOT UP-TO-DATE!) This directory contains the React.js frontend application code. It includes components, views, styles, and other frontend-specific files.
- **`server`**: The backend server code resides in this directory. It includes API routes, middleware, database connections, and other server-related files.

## Getting Started

To run the MERN Demo Project locally, follow these steps:

1. **Clone the repository**:

   ```
   git clone <repository_url>
   ```

2. **Install dependencies**:

   Navigate to the project root directory and install the required dependencies for both the frontend and backend:

   ```shell
   cd mern_crud
   npm install
   cd server
   npm install
   cd ..
   ```

3. **Set up the database**:

   Ensure you have MongoDB installed and running locally or provide the appropriate connection details in the backend's configuration file (`server/app.js`).

4. **Start the development server**:

   Start the development server:

   ```shell
   npm start
   ```

