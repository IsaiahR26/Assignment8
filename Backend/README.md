# Assignment8-Backend-

API APPLICATION

DESCRIPTION

The backend Api uses Nodes.js and Express that works to communicate with the front end and store and recieve data.

The goal of the backend works to send requests to the front end and the database information with it. It also works to recieve responses form the web application.

TABLE OF CONTENTS

1. INSTALLATION AND SETUP
2. API DOCUMENTATION
3. DATABASE SETUP
4. AUTHENTICATION AND SECURITY
5. DEPLOYMENT GUIDE
6. LICENSE AND CONTRIBUTION GUIDELINES


INSTALLATION AND SETUP

Required Dependencies:

- Node.js
- Express.js
- Git
- PostgreSQL (Or PGAdmin4)

Steps to Install: 

1. Download the clone by copying the clone url and going into the terminal in
visual studio code.
2. Type: git clone git@github.com:IsaiahR26/Assignment8.git
3. Install npm: npm install
4. Then start the installation: npm start


API DOCUMENTATION

The Api lets the frontend send and retrieve data from the server. 

- GET: Retrieves data
- POST: Creates New data
- PUT: Updates data
- DELETE: Removes data

Examples:

GET /movies

Returns a list of all movies

POST /movies

Creates a new movie

Example Response:

{
    "id": 1,
    "title": "Inception",
    "year": 2010
}


DATABASE SETUP

The database allows users to store and insert infrormation into a table that can send it between the web application and the Api. It updates the table whenever something has been insereted, removed, or changed.

Example:

CREATE DATABASE assignment8;
CREATE TABLE users (
    id SERIAL PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100)
)


AUTHENTICATION AND SECURITY

Authentication mechanisms make sure that it's really you who are using the correct information. For example, if you're logging in, OAuth will send a number that you need to input to verify that it's you. It'll either sometimes send it to your email, and app, or your phone number.

POST /login

Request Example:

{
    "username: "john",
    "password" "mypassword"
}

Example Response:

{
    "token": "abc123xyz"
}


DEPLOYMENT GUIDE

You can deploy the web application and Api to a live site by uploading the repository.

Services to upload your repository can include:

- RENDER
- NETLIFY
- AWS
- Digital Ocean
- Heroku

Example:

git push origin main

This command can upload the backent to a remote repository. It then connects to a service like Render that can run the application in a live setting.


LICENSE AND CONTRIBUTION GUIDELINES

Example: 

This project is licensed under the MIT license.

People working on the project can create their own fork from the main in the repository. They can create their own pull and push requests.