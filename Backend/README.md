# Assignment8-FrontEnd-

API APPLICATION

DESCRIPTION

The backend Api uses Nodes.js and Express that works to communicate with the front end and store and recieve data.

The goal of the backend works to send requests to the front end and the database information with it. It also works to recieve responses form the web application.

TABLE OF CONTENTS

1. PROJECT TITLE AND OVERVIEW
2. INSTALLATION AND SETUP
3. API DOCUMENTATION
4. DATABASE SETUP
5. AUTHENTICATION AND SECURITY
6. DEPLOYMENT GUIDE
7. LICENSE AND CONTRIBUTION GUIDELINES


INSTALLATION AND SETUP

Required Dependencies:

- Node.js
- Express.js
- Git
- PostgreSQL (Or PGAdmin4)

Steps to Install: 

1. Download the clone by copying the clone url and going into the terminal in
visual studio code.
2. Type: git clone ENTERYOURURLHERE
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