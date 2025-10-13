# note-taker

# Tech Stack - MERN (Mongodb, Express, React, Node)

# Frontend

React.js - frontend library

# Backend

Node.js - JavaScript runtime, allows you to run JS on server

# DB

# Mongodb

# Express (Web framework) - ready to use toolbox for building web apps faster and more easily

We want to use because:

- It saves time
- Makes code clearner and more organized
- Handles common tasks (like routingm error handling, etc.)

# Application Programming Interface

- It allows two different apps to talk to each other

# REST API

- It uses HTTP methods

GET: Get some posts
POST: Create a post
PUT: Update a post
DELETE: Delete a post

# Status Codes

1xx means (Informational)
2xx means (Success)

- 200 OK, Everything worked as expected
- 201 Created, New resource successfully created (e.g., after a POST request).

3xx means (Redirection)

- The 300 status code are for redirection meaning the server is telling the client, "Hey, the thing you're looking for is somewhere else."
- 301 Moved permanently
  - Ex.) Your site changes form http://example.com to https://example.com.
    You set up a 301 redirect so visitors and Google know to go to the new one.

4xx means (Client Errors)

- These happen when the problem is on the user's side meaning your browser or app made a bad request.
- Think of it like: "You (the client) messed up."

400 Bad Request - The request is malformed or invalid.
401 Unauthorized - You must log in (missing or invalid credentials)
403 Forbidden - You're not allowed to access this
404 Not Found - The URL doesn't exist
429 Too Many Requests

5xx means (Server Errors)

- These happen when something goes wrong on the server side even though the client made a valid requests.
- Think of it like: "The server tried, but failed"

500 Internal Server Error - Something broke on the server.
503 Service Unavailable - Server is temporarily overloaded or down.

---

#SQL

- Structured Data

  - Data is stored in tables with rows and columns, like a spreadsheet

- Uses SQL Language

  - You use structured queries (SELECT, INSERT, etc.) to interact with the database

- Best for Complex Queries
  - Ideal when you need relationships between data like orders and customers

#NOSQL

- Flexible Data Format

  - Stores data like JSON or key-value pairs - good for changing data shapes.

- Uses Query Language or API

  - Each NoSQL database has its own way of querying often simplier and faster for certain tasks

- Best for Big Data & Real-Time Apps
  - Great for fast changing or huge amounts of data
