# expixo-app

A full-stack mobile application with React Native frontend and Node.js/Express backend, featuring user authentication and profile management.

## Features

- **Frontend**: 
  - React Native with navigation (Drawer, Bottom Tabs, and Profile Tabs)
  - Clean UI with Profile Overview and Settings screens
- **Backend**:
  - Node.js/Express REST API
  - MongoDB database
  - JWT authentication
  - CRUD operations for user profiles

## Tech Stack

- **Frontend**: React Native, React Navigation, Axios
- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Authentication**: JWT, bcryptjs

## Installation

### Backend Setup
```bash
cd backend
npm install
node server.js

### Frontend Setup
cd frontend
npm install
npx react-native start
# In another terminal:
npx react-native run-android # or run-ios


### Project Structure
erpixo-app/
├── backend/
│   ├── server.js         # Main server file
│   ├── models/           # MongoDB models
│   └── routes/           # API routes
└── frontend/
    ├── src/
    │   ├── screens/      # App screens
    │   ├── components/   # Reusable components
    │   ├── navigation/   # Navigation setup
    │   └── services/     # API service
    └── App.js           # Main app entry
