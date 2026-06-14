# Basic Node.js Application

A simple Node.js application built with Express.js.

## Features

- Express.js web framework
- RESTful API endpoints
- JSON request/response handling
- Error handling middleware
- Static file serving

## Installation

```bash
npm install
```

## Running the Application

```bash
npm start
```

The server will run on `http://localhost:3000`

## API Endpoints

- `GET /` - Welcome message
- `GET /api/hello?name=YourName` - Personalized greeting
- `POST /api/echo` - Echo back JSON data
- `GET /api/status` - Server status

## Example Requests

```bash
# GET request
curl http://localhost:3000/api/hello?name=Alice

# POST request
curl -X POST http://localhost:3000/api/echo \
  -H "Content-Type: application/json" \
  -d '{"message":"Hello"}'

# Check status
curl http://localhost:3000/api/status
```

## Project Structure

```
.
├── index.js          # Main application file
├── package.json      # Project dependencies
├── README.md         # This file
└── public/           # Static files directory
```
