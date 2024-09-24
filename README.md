# Crud_app
 This is a simple CRUD (Create, Read, Update, Delete) application built with React, Node.js, Express, and MongoDB. The application allows users to add, view, edit, and delete user data.

## Features
Create User: Add new users with a first name, last name, and email.
Read User: View a list of all users.
Update User: Edit existing user details.
Delete User: Remove a user from the list.

## Demo
![Screenshot 2024-09-24 224826](https://github.com/user-attachments/assets/d395f6ac-3444-4678-b284-286e5f3b1196)

## Prerequisites
[Node.js (v12 or later)](https://nodejs.org/en)
[MONGODB](https://www.mongodb.com/)

## Installation
### Follow the steps below to set up and run the project locally.

1. Clone the Repository: git clone [https://github.com/rashigupta12/Crud_app](https://github.com/rashigupta12/Crud_app)
2. Navigate to the Project Directory : Crud_app
3. Install Server Dependencies
   ```
   cd server
   npm install
   ```
4. Install Client Dependencies
   ```
   cd ../client
   npm install
   ```
5. Set Up MongoDB
   `Make sure MongoDB is installed and running on your machine. You can either use a local instance or a cloud instance like MongoDB Atlas.`
6. Configure MongoDB URL
   ```
   Create a .env file in the server directory with the following content:
   MONGO_URL=mongodb://localhost:27017/your-database-name
   or for MongoDB Atlas
   MONGO_URL=mongodb+srv://<username>:<password>@cluster0.mongodb.net/your-database-name?retryWrites=true&w=majority
   Replace <username>, <password>, and your-database-name with your actual MongoDB credentials.
   ```
7. Run the Server :
   ```
   cd server
   npm start 
   ```
   The server will start on http://localhost:8000.
8. Run the Client
   ```
   cd client
   npm start
   ```
   The server will start on http://localhost:3000.
## Usage
Add User: Click on the "Add User" button to add a new user.
Edit User: Click on the edit icon next to a user to update their details.
Delete User: Click on the delete icon next to a user to remove them.
