# TODO for Adding Backend with Node.js and MongoDB

## Information Gathered
- Current project is a frontend website with HTML, CSS, and JavaScript files.
- No existing backend code found.
- Frontend includes user sign in, profile creation, courses, quizzes, and payment pages.
- Backend needed to support user authentication, profile management, course data, quiz results, and payment processing.

## Plan

1. ✅ Setup Backend Project
   - ✅ Create a new folder `backend/`
   - ✅ Initialize Node.js project with `package.json`
   - ✅ Install dependencies: express, mongoose, cors, dotenv, bcrypt, jsonwebtoken, body-parser

2. ✅ Database Setup
   - ✅ Connect to MongoDB using Mongoose
   - ✅ Define schemas and models for:
     - ✅ User (profile, authentication)
     - ✅ Course
     - ✅ Quiz
     - Payment (if needed)

3. ✅ API Endpoints
   - ✅ Auth routes: register, login, logout
   - User routes: get profile, update profile
   - ✅ Course routes: list courses, get course details
   - ✅ Quiz routes: submit quiz results, get quiz results
   - Payment routes: process payment (optional, depending on frontend integration)

4. Middleware
   - Authentication middleware using JWT
   - Error handling middleware
   - ✅ CORS setup to allow frontend requests

5. ✅ Integration with Frontend
   - ✅ Modify frontend JavaScript to call backend API endpoints for sign in, profile creation, quiz submission, etc.
   - ✅ Serve frontend static files from backend or keep separate with CORS

6. ✅ Testing
   - ✅ Test API endpoints with Postman or similar tool
   - ✅ Test frontend-backend integration
   - ✅ Verify user data storage in database
   - ✅ Test registration and login flow

## Dependent Files to be Edited
- ✅ New backend files under `backend/`
- ✅ Frontend JavaScript files (e.g., script.js) to add API calls for authentication and data fetching

## Followup Steps
- ✅ Setup MongoDB database (local or cloud)
- ✅ Implement backend server and APIs
- ✅ Update frontend to use backend APIs
- ✅ Test full application flow
- ✅ Install backend dependencies
- ✅ Start the backend server
- ✅ Add sample data to database
- ✅ Test user registration and login
- ✅ Verify data persistence in database
- ✅ Fix course functionality errors:
  - ✅ Add difficulty field to Course model
  - ✅ Update api-client.js to store user info in localStorage
  - ✅ Handle missing difficulty in course.html
