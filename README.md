# Fitness_Tracker_App

## Overview
Habit Tracker is a web application designed to help users log their workouts, track their progress, set Habit goals, and view detailed statistics. Admins can manage user accounts, create Habit programs, and analyze user activity. The application features user authentication and data visualization, providing a user-friendly experience for Habit enthusiasts.



## Features
- User authentication (login and signup)
- Log Habit with details
- Set and manage Habit goals
- View workout history and progress
- Admin dashboard for managing user accounts and programs
- Responsive design with a modern UI

## Tech Stack
- *Frontend:* React.js, Material UI
- *Backend:* Node.js, Express.js
- *Database:* MongoDB (Mongoose for schema management)
- *State Management:* React Context API or Redux
- *Deployment:* Vercel for frontend and backend (if applicable)

## Installation

### Prerequisites
- Node.js and npm installed on your machine
- MongoDB instance (local or cloud-based)


### Backend Setup
1. Clone the repository:
   bash
   git clone https://github.com/MehulGS/Habit-Tracker
2. Navigate to the server folder:
   bash
   cd Fitness_Tracker_App/server
3. Install backend dependencies:
   bash
   npm install
4. Set up environment variables:
- Create a .env file in the server folder and add the following:
   bash
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET="your jwt secret"
5. Start the backend server:
   bash
   npm start

### Frontend Setup
1. Navigate to the client folder:
   bash
   cd Fitness_Tracker_App/client
2. Install frontend dependencies:
   bash
   npm install
3. Start the frontend server:
   bash
   npm start
