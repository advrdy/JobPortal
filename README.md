# Job Portal

A modern, full-stack job portal application that connects job seekers with employers. Built with the MERN stack and styled with Tailwind CSS.

Live Link - https://jobportal-1xf0.onrender.com/

## Features

- 🔐 User Authentication (Job Seeker & Employer)
- 👤 User Profiles
- 💼 Job Listings Management
- 🔍 Advanced Job Search
- 📝 Job Applications
- 📱 Responsive Design
- 🔒 Secure API Endpoints
- 🖼️ Image Upload Support

## Tech Stack

### Frontend

- React.js
- Tailwind CSS
- Vite

### Backend

- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Cloudinary (for image uploads)
- Multer (for file handling)

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/job-portal.git
cd job-portal
```

2. Install dependencies:

```bash
# Install backend dependencies
npm install

# Install frontend dependencies
cd frontend
npm install
cd ..
```

3. Set up environment variables:
   Create a `.env` file in the root directory with the following variables:

```env
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

## Running the Application

### Development Mode

1. Start the backend server:

```bash
npm run dev
```

2. In a new terminal, start the frontend development server:

```bash
cd frontend
npm run dev
```

### Production Mode

To build and run the application in production mode:

```bash
npm run build
npm start
```

## Project Structure

```
job-portal/
├── frontend/                 # React frontend application
│   ├── src/                 # Source files
│   ├── public/              # Static files
│   └── package.json         # Frontend dependencies
├── backend/                 # Node.js backend application
│   ├── controllers/         # Route controllers
│   ├── models/             # Database models
│   ├── routes/             # API routes
│   ├── middlewares/        # Custom middlewares
│   ├── utils/              # Utility functions
│   └── index.js            # Entry point
└── package.json            # Backend dependencies
```
