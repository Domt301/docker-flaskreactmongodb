# Three-Tier Web Application using React, Flask, and MongoDB

This repository contains the source code and documentation for a Three-Tier Web Application built using React.js for the frontend, Flask for the backend, and MongoDB as the database. This README provides an overview of the project, installation instructions, and basic usage guidelines.



## Overview

A Three-Tier Web Application is a common architectural pattern for building scalable and maintainable web applications. In this project, we have used the following technologies for each tier:

- **Frontend (Tier 1):** React.js
  - React is a popular JavaScript library for building user interfaces. It allows for the creation of dynamic and interactive web pages.

- **Backend (Tier 2):** Flask
  - Flask is a micro web framework for Python. It is lightweight and provides the necessary tools to build web applications and APIs quickly.

- **Database (Tier 3):** MongoDB
  - MongoDB is a NoSQL database that stores data in a flexible, JSON-like format. It is suitable for handling large amounts of unstructured or semi-structured data.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm (Node Package Manager) installed for React development.
- Python and pip (Python package manager) installed for Flask development.
- MongoDB installed and running locally or on a remote server. You should have the connection details (URI) for your MongoDB instance.
- Docker to run the entire app

## Important commands
- docker exec -it mongo mongosh
- use admin
- db.auth('admin','password');
- use webapp
- db.createUser({user: 'apiuser', pwd: 'apipassword', roles: [{role: 'readWrite', db: 'webapp'}]})
- docker-compose up -d 



