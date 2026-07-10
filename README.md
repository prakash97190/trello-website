# Trello Website

A full-stack Trello-inspired task management application built with the **MERN Stack** (MongoDB, Express.js, React.js, and Node.js). The application allows users to create boards, manage tasks, collaborate, and organize projects through a modern drag-and-drop interface.

##  Features

### Authentication

* User registration and login
* JWT-based authentication
* Secure password hashing
* Protected routes
* User profile management

### Boards

* Create new boards
* Edit board details
* Delete boards
* View all personal boards

### Lists

* Create multiple lists within a board
* Rename lists
* Delete lists
* Reorder lists

### Cards

* Create task cards
* Edit card title and description
* Delete cards
* Move cards between lists using drag and drop
* Reorder cards within the same list

### Task Management

* Assign tasks to users
* Set due dates
* Add labels
* Track task progress

### User Experience

* Responsive design
* Clean and modern UI
* Real-time interface updates
* Loading indicators
* Error handling and validation

### Backend

* RESTful API
* MongoDB database
* Express.js server
* JWT authentication
* Modular folder structure
* Secure API endpoints

## 🛠 Tech Stack

### Frontend

* React.js
* React Router
* Axios
* CSS / Tailwind CSS (if applicable)

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* bcrypt
* dotenv
* CORS

##  Project Structure

```text
trello-website/
│
├── client/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── package.json
│   └── server.js
│
├── README.md
└── .gitignore
```

##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/prakash97190/trello-website.git
```

### 2. Navigate to the project

```bash
cd trello-website
```

## ▶️ Running the Backend

Navigate to the server folder:

```bash
cd server
```

Install dependencies:

```bash
npm install
```

Create a `.env` file and add your environment variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:3000
```

Start the backend server:

```bash
npm run dev
```

The backend will run on:

```
http://localhost:5000
```

##  Running the Frontend

Open another terminal.

Navigate to the client folder:

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Start the React application:

```bash
npm start
```

The frontend will run on:

```
http://localhost:3000
```

##  API

The backend provides REST APIs for:

* Authentication
* Users
* Boards
* Lists
* Cards
* Task Management

##  Screenshots

Add screenshots of the application here.

##  Future Improvements

* Real-time collaboration using Socket.IO
* Notifications
* File attachments
* Comments on cards
* Activity history
* Dark mode
* Search and filtering
* Team workspaces
* Email notifications

##  Author

**Prakash Singh**

GitHub: https://github.com/prakash97190

## 📄 License

This project is intended for educational and learning purposes.
