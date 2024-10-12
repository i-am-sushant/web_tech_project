# Project Title

## Tools and Technologies
- HTML
- CSS
- JavaScript
- Tailwind CSS
- Node.js
- Express.js
- React
- Redux
- MongoDB

## Dependencies
### Major Dependencies
- axios
- react
- react-dom
- react-redux
- react-router-dom
- react-toastify
- redux
- redux-thunk
- bcrypt
- cors
- dotenv
- express
- jsonwebtoken
- mongoose

### Dev Dependencies
- nodemon
- concurrently

## Prerequisites
- Node.js must be installed on your system.
- You should have a MongoDB database.
- You should have a code editor (preferred: VS Code).

## Installation and Setup
1. Install all dependencies:
   ```bash
   npm run install-all
   ```
2. Create a file named `.env` inside the **backend** folder. Add data from `.env.example` file and substitute your credentials there.
3. Start the application:
   ```bash
   npm run dev
   ```
   Go to [http://localhost:3000](http://localhost:3000).

## Backend API
- **POST** `/api/auth/signup`
- **POST** `/api/auth/login`
- **GET** `/api/tasks`
- **GET** `/api/tasks/:taskId`
- **POST** `/api/tasks`
- **PUT** `/api/tasks/:taskId`
- **DELETE** `/api/tasks/:taskId`
- **GET** `/api/profile`

## Frontend Pages
- `/` Home Screen (Public home page for guests and private dashboard (tasks) for logged-in users)
- `/signup` Signup page
- `/login` Login page
- `/tasks/add` Add new task
- `/tasks/:taskId` Edit a task

## npm Scripts
### At Root
- `npm run dev`: Starts both backend and frontend
- `npm run dev-server`: Starts only backend
- `npm run dev-client`: Starts only frontend
- `npm run install-all`: Installs all dependencies and dev-dependencies required at root, frontend, and backend.

### Inside Frontend Folder
- `npm start`: Starts frontend in development mode
- `npm run build`: Builds the frontend for production to the build folder
- `npm test`: Launches the test runner in interactive watch mode
- `npm run eject`: Removes the single build dependency from the frontend.

### Inside Backend Folder
- `npm run dev`: Starts backend using nodemon.
- `npm start`: Starts backend without nodemon.
```
