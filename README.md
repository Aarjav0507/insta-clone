

##Features Implemented

### User Authentication
- User Signup
- User Login
- Password hashing using **bcrypt**
- JWT-based authentication
- Token stored on frontend

### Follow System
- Follow a user
- Unfollow a user
- Maintains followers and following lists

### Posts
- Create a post (Image URL + Caption)
- Posts linked to authenticated users

### Likes
- Like a post
- Unlike a post

### Comments
- Comment on posts
- Each comment stores user and text

### Feed
- Personalized feed
- Displays posts only from followed users
- Sorted by recent posts

---

## Tech Stack

### Frontend
- React (Vite)
- TypeScript
- Axios
- React Router DOM

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (jsonwebtoken)
- bcryptjs
- CORS

---

## How to Run the Project

```bash
cd backend
npm install
node server.js

**### Backend Runs on**
http://localhost:5000

### Frontend setup
cd frontend
npm install
npm run dev

### Frontend Runs on
http://localhost:8085

