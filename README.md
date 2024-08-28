## Project Overview

In this lab, I have:

- Built a **server-side online book review application**.
- Integrated the application with a **secure REST API** using **JWT-based session-level authentication**.
- Created APIs to perform **CRUD operations** on an **Express server** utilizing **Session** and **JWT authentication**.
- Employed **Async/Await** or **Promises** with **Axios** in Node.js for handling asynchronous operations.
- Developed **REST API endpoints** and tested them using **Postman**.

## Application Features and Capabilities

The server-side application provides the following features and capabilities for users:

- **Retrieve a list of all books** available in the bookshop.
- **Search for specific books** and retrieve their details based on:
  - ISBN code
  - Author names
  - Titles
- **Retrieve reviews/comments** for specified books.
- **Register as a new user** of the application.
- **Login** to the application to access additional features.
- **Add a new review** for a book (only available to logged-in users).
- **Modify a book review** (logged-in users can modify only their own reviews).
- **Delete a book review** (logged-in users can delete only their own reviews).
- **Concurrent access**: Multiple users can access the application simultaneously to view and manage different book reviews.
