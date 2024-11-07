# ToDoApp
 
A To-Do list app built with **Node.js**, **Express**, and **MongoDB**. It allows users to create, edit, and delete tasks, with basic authentication for security.

## Features

- **Create, Edit, and Delete Tasks**
- **Basic Authentication** for access
- **MongoDB** for data storage
- **Responsive UI** with **Bootstrap**

## Tech Stack

- **Backend**: Node.js, Express
- **Database**: MongoDB (Atlas)
- **Frontend**: HTML, Bootstrap
- **Libraries**: Axios, sanitize-html
- **Authentication**: Basic Authentication

## Setup

### Prerequisites

- [Node.js](https://nodejs.org/)
- MongoDB Atlas account

### Steps

1. **Clone the repo**:
   ```bash
   git clone https://github.com/deepaksnk/ToDoApp.git
   cd ToDoApp
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Configure MongoDB**:
   Update the MongoDB connection string in `server.js` with your Atlas credentials.

4. **Run the app**:
   ```bash
   npm start
   ```

   Access the app at [http://localhost:3000](http://localhost:3000).

## Usage

- **Create**: Add a new task.
- **Edit**: Modify existing tasks.
- **Delete**: Remove tasks.

## File Structure

```
/ToDoApp
├── public/        # Frontend files
│   ├── index.html
│   └── browser.js
├── server.js      # Backend API
├── package.json   # Dependencies
├── README.md      # Project details
```

## Acknowledgments

- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for providing cloud-hosted database services.
- [Express.js](https://expressjs.com/) for the fast and minimal backend framework.
- [Axios](https://axios-http.com/) for making HTTP requests on the client side.
- [sanitize-html](https://www.npmjs.com/package/sanitize-html) for ensuring user input is sanitized before saving it to the database.
- [Bootstrap](https://getbootstrap.com/) for the responsive UI design.
