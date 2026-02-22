# Node.js Lab Project

A Node.js project demonstrating core concepts including file operations, HTTP servers, HTTP requests, promises, async/await, and custom modules.

## Project Structure

```
├── app.js          # Main application file
├── my-module.js    # Custom module
├── file.txt        # Output file created by fs.writeFile
├── package.json    # Project configuration
└── README.md
```

## Features

### 1. Initial Node Setup
- Created `app.js` as the main entry point for the project.

### 2. File Operations
- **Write File:** Uses the `fs` module to write `"Hello World!"` to `file.txt`.

### 3. Custom Module
- Created `my-module.js` that exports a reusable function returning `"Hello from my module!"`.

### 4. HTTP Web Server
- Creates a basic HTTP server using `http.createServer()` that listens on port **8080** and responds with `"Hello World!"`.

### 5. HTTP Request
- Makes an HTTPS GET request to `https://jsonplaceholder.typicode.com/posts/1` using the built-in `https` module and parses the JSON response.

### 6. Promises
- Demonstrates JavaScript Promises with `.then()` and `.catch()` chaining for handling asynchronous results.

### 7. Async/Await
- Implements an `async` function using `try/catch` to `await` a Promise, providing cleaner asynchronous code flow.

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) installed

### Installation
```bash
npm install
```

### Run
```bash
node app.js
```

## Change Log

| Commit | Description |
|--------|-------------|
| `838868f` | Initial Node setup with app.js |
| `9de167b` | Added read file feature |
| `248a605` | Change file content |
| `14c8526` | Create basic web server |
| `14bc50c` | Added HTTP request feature |
| `66b3871` | Added custom module feature |
| `037d2fc` | Added promises feature |
| `885502b` | Added async/await feature |