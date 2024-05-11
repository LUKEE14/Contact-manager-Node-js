# Contact Manager - NodeJS/Express project

This project is a Contact Manager application built using Node.js and Express. It allows users to manage their contacts by performing CRUD (Create, Read, Update, Delete) operations through a RESTful API.

## Features

Authentication and Authorization
JWT (JSON Web Token) based authentication is implemented to secure the endpoints.
Middleware is used to validate the JWT token sent in the request headers, ensuring that only authorized users can access protected routes.

## Contact Operations

Get All Contacts: Fetches all contacts associated with the authenticated user.
Create New Contact: Allows users to add new contacts by providing their name, email, and phone number.
Get Single Contact: Retrieves details of a specific contact by its ID.
Update Contact: Enables users to update the details of an existing contact.
Delete Contact: Allows users to remove a contact from their list.

## Error Handling

Custom error handling middleware is implemented to provide meaningful error responses for different types of errors, including validation errors, not found errors, unauthorized access errors, forbidden errors, and server errors.
Errors are properly categorized and formatted to provide clear information to the client.

## Usage

Clone the repository: git clone <repository-url>
Install dependencies: npm install
Set up environment variables:
Create a .env file in the root directory.
Define the ACCESS_TOKEN_SECRET variable in the .env file with a secret value for JWT token encryption.
Start the server: npm start
Access the API endpoints using an API client such as Thunder Client, Postman, or cURL.

## Dependencies

express: Web framework for Node.js.
jsonwebtoken: Library for generating and verifying JWT tokens.
mongoose: MongoDB object modeling tool for Node.js, used for interacting with the database.
express-async-handler: Utility middleware for handling asynchronous errors in Express routes.
bcrypt: Library for hashing passwords to enhance security.

## Installation

install the required components and modules
-Nodejs - from official documentary
-nodemon - run command npm install nodemon
-expressJs - run command npm install express
-bcrypt - run command npm install bcrypt
-mongodb - run command npm install mongodb
-mongoose - run command npm install mongoose
-dotenv - run command npm install dotenv
-JWT(javawebtoken) - run command npm install jwt
-express-async-handler - run command npm install express-async-handler

to run the server use the command "npm run dev"
