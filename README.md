# Fitness Tracker Website | MERN Project

A Fitness Tracker Web Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) to help users track and manage their fitness activities efficiently.

## Features

- User registration and authentication
- Track workouts, exercises, and progress
- Responsive UI with React.js
- RESTful API built with Express.js
- MongoDB database for storing user data
- Error handling and secure API routes

## Tech Stack

- Frontend: React.js, HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Other: dotenv, CORS, Mongoose

## Project Structure
```
FItnessTrack-master/
├── client/           # React frontend
├── server/           # Node/Express backend
│   ├── routes/       # API routes
│   ├── models/       # Database models
│   └── index.js      # Server entry point
├── package.json
└── README.md
```
## Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/FitnessTrack.git
cd FItnessTrack-master
```

2. Install backend dependencies:
```
cd server
npm install
```

3. Install frontend dependencies:
```
cd ../client
npm install
```

4. Create a .env file in the server folder with your MongoDB connection string:
```
MONGODB_URL=your_mongodb_connection_string
```
## Running the Project
### Backend
```
cd server
node index.js
```
Server runs on http://localhost:8080 by default.

### Frontend
```
cd client
npm start
```
Frontend runs on http://localhost:3000.

### API Routes

- User Routes: /api/user/ (register, login, update user data)
- Error Handling: Custom error handler for all API requests

## Screenshots:
<img width="647" height="374" alt="fi" src="https://github.com/user-attachments/assets/838e8d9b-6748-4154-b7d3-1abaf7f96acc" />
<img width="1139" height="586" alt="s" src="https://github.com/user-attachments/assets/9e619a46-5cdf-45d1-a98f-8f6af21fac3a" />
<img width="524" height="344" alt="f" src="https://github.com/user-attachments/assets/60c17550-df8c-4ded-a7c2-76f31cc19efd" />
<img width="1141" height="582" alt="2" src="https://github.com/user-attachments/assets/aff962c9-8051-4455-ade4-0d1c753ae11e" />
