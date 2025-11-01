# Node.js REST API with Mongoose

A simple REST API with full CRUD functionality using Express and Mongoose.

## Features

*   CRUD operations for products
*   Multi-folder structure

## Installation

1.  Clone the repository:

    
    git clone <repository_url>
    

2.  Navigate to the project directory:

    
    cd <project_directory>
    

3.  Install dependencies:

    
    npm install
    

4.  Configure environment variables:

    *   Create a `.env` file in the root directory.
    *   Add the following environment variables:

        
        PORT=3000
        MONGO_URI=<your_mongodb_connection_string>
        JWT_SECRET=<your_jwt_secret>
        

5.  Start the server:

    
    npm start
    

## API Endpoints

### Products

*   `GET /api/products`: Get all products
*   `GET /api/products/:id`: Get a product by ID
*   `POST /api/products`: Create a new product
*   `PUT /api/products/:id`: Update a product by ID
*   `DELETE /api/products/:id`: Delete a product by ID

## Authentication Endpoints

*   `POST /api/auth/register`: Register a new user
*   `POST /api/auth/login`: Login a user

