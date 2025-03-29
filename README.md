# YouTube Clone

A full-stack YouTube clone application built with modern web technologies. This project replicates core YouTube features including video upload, viewing, and user authentication.

## Features

- User Authentication (Sign up, Login, Logout)
- Video Upload and Management
- Video Playback
- Modern and Responsive UI
- Secure API Endpoints
- MongoDB Database Integration

## Tech Stack

### Frontend
- React.js
- Vite
- TailwindCSS
- React Router DOM
- Axios for API calls
- React Icons
- React Toastify for notifications
- SweetAlert2 for alerts

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT for authentication
- Multer for file uploads
- Bcrypt for password hashing
- CORS enabled

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn package manager

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Shraddha2421/YouTube_Clone.git
cd youtube-clone
```

2. Install Backend Dependencies:
```bash
cd backend
npm install
```

3. Install Frontend Dependencies:
```bash
cd ../frontend
npm install
```

4. Set up environment variables:
   - Create a `.env` file in the backend directory with the following variables:
   ```
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

## Running the Application

1. Start the Backend Server:
```bash
cd backend
npm run dev
```

2. Start the Frontend Development Server:
```bash
cd frontend
npm run dev
```

The application will be available at:
- Frontend: http://localhost:5173
- Backend API: http://localhost:5000

## Project Structure

```
youtube-clone/
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── middleware/
│   ├── config/
│   └── package.json
└── README.md
```

## API Endpoints

- POST /api/auth/register - User registration
- POST /api/auth/login - User login
- POST /api/videos/upload - Upload video
- GET /api/videos - Get all videos
- GET /api/videos/:id - Get video by ID
- PUT /api/videos/:id - Update video
- DELETE /api/videos/:id - Delete video

