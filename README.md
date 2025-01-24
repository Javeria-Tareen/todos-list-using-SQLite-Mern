# todos-list-using-SQLite-Mern


# MERN Todo App

A simple Todo application built using the MERN stack (MongoDB, Express, React, Node.js). This app allows users to manage their tasks by adding, updating, and deleting Todos. It stores data locally using SQLite.

## Features
- Add a new Todo with a title and description.
- Mark a Todo as completed or incomplete.
- Delete a Todo.
- Fully responsive and user-friendly interface.

## Technology Stack
- **Backend:**
  - Node.js
  - Express.js
  - SQLite (for database)
- **Frontend:**
  - React
  - Axios (for API requests)
- **Styling:**
  - Plain CSS for styling

## Setup Instructions

### 1. Clone the Repository
Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/mern-todo-app.git
```

### 2. Backend Setup

Navigate to the `backend` directory:

```bash
cd backend
```

- Install the backend dependencies:

```bash
npm install
```

- Start the backend server using `nodemon`:

```bash
npm run dev
```

This will start the backend server on `http://localhost:5000`.

### 3. Frontend Setup

Navigate to the `frontend` directory:

```bash
cd frontend
```

- Install the frontend dependencies:

```bash
npm install
```

- Start the React development server:

```bash
npm start
```

This will start the frontend server on `http://localhost:3000`.

### 4. Access the App
- Open your browser and visit `http://localhost:3000` to use the Todo app.

## Endpoints
The backend provides the following API endpoints:

- `GET /api/todos`: Fetch all Todos.
- `POST /api/todos`: Create a new Todo.
- `PUT /api/todos/:id`: Update a Todo (mark as completed or incomplete).
- `DELETE /api/todos/:id`: Delete a Todo.

## Folder Structure

```
mern-todo-app/
├── backend/
│   ├── config/               # Database connection setup
│   ├── controllers/          # Logic for handling routes
│   ├── models/               # Database schema/models
│   ├── routes/               # API route definitions
│   └── server.js             # Main server entry point
├── frontend/
│   ├── public/               # Static assets (index.html)
│   ├── src/                  # Source code for React components
│   ├── App.js                # Main React component
│   └── index.js              # React entry point
└── README.md                 # Documentation
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### Contributing
Feel free to fork the repository, make changes, and create pull requests.
