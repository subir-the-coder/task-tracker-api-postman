# Task Tracker API

![API](https://img.shields.io/badge/API-REST-blue)
![Status](https://img.shields.io/badge/Status-Stable-success)
![Postman](https://img.shields.io/badge/Tested%20With-Postman-orange)
![Version](https://img.shields.io/badge/version-v1.0.0-blue)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

## Overview
Task Tracker API is a lightweight mock REST API designed to help developers practice and demonstrate basic CRUD (Create, Read, Update, Delete) operations. It’s perfect for learning API fundamentals, testing frontend integrations, and prototyping task-based workflows without any complex setup.

This project is implemented as a Postman collection, making it easy to explore and test endpoints instantly.

## Features
- CRUD operations for tasks
- Fetch user data
- Clean and predictable JSON responses
- No authentication required
- Ideal for learning, demos, and interviews

## Versioning
Current version: **v1.0.0**

Versioning follows a simple approach:
- **Major** – Breaking changes
- **Minor** – New features
- **Patch** – Fixes and improvements

Future releases may include authentication, pagination, and database-backed persistence.

## Base URL
Set the `baseURL` variable in Postman to your mock server or API host.

## Available Endpoints

### Get All Tasks
**GET** `/tasks`  
Fetches a list of all tasks.

### Create New Task
**POST** `/tasks`  
Creates a new task using a JSON request body.

### Update Task
**PUT** `/tasks/:id`  
Updates an existing task by its ID.

### Delete Task
**DELETE** `/tasks/:id`  
Deletes a task using its ID.

### Get All Users
**GET** `/users`  
Returns a list of users.

## Authentication
This API does not require authentication. All endpoints are publicly accessible for learning and testing purposes.

## How to Use
1. Import the Postman collection into Postman.
2. Set the `baseURL` environment variable.
3. Start testing the endpoints using the provided requests.

## Use Cases
- Learning REST API basics
- Practicing frontend-backend integration
- Mock API for demos and prototypes
- Interview preparation

## License
This project is intended for educational and demonstration purposes.
