# Final Submission Dicoding Course Bookshelf API

## Introduction
Bookshelf API is a Node.js-based RESTful API built with the Hapi framework. It provides functionalities for managing a collection of books, including adding, retrieving, updating, and deleting book records. It is built as a final submission project for "Belajar Back-End Pemula dengan JavaScript" course at Dicoding.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [API Endpoints](#api-endpoints)

## Installation
To set up and run the project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/Al-Iskandari/bookshelf-api-hapijs.git

# Navigate to the project directory
cd bookshelf-api

# Install dependencies
npm install

# Start the server
npm start
```

## Usage
1. Start the server using `npm start`.
2. The API will be available at `http://localhost:3000/`.
3. Use a tool like Postman or Curl to test the API endpoints.

## Project Structure
```
bookshelf-api/
│── node_modules/
│── src/
│   ├── books.js       # Book data and operations
│   ├── handler.js     # Request handlers
│   ├── routes.js      # API route definitions
│   ├── server.js      # Main server entry point
│── .gitignore
│── eslint.config.mjs
│── package.json
│── package-lock.json
│── README.md
```

## Features
- RESTful API for book management
- CRUD operations (Create, Read, Update, Delete)
- Built with Hapi.js for scalable server-side development
- Uses JavaScript ES modules (ESM)

## Dependencies
- Node.js
- Hapi.js
- ESLint

## Configuration
- Modify `server.js` to change API settings such as the port.
- Ensure dependencies are installed via `npm install`.

## API Endpoints
| Method | Endpoint        | Description              |
|--------|----------------|--------------------------|
| GET    | `/books`        | Retrieve all books      |
| GET    | `/books/{id}`   | Retrieve a single book  |
| POST   | `/books`        | Add a new book          |
| PUT    | `/books/{id}`   | Update a book           |
| DELETE | `/books/{id}`   | Delete a book           |

