# Blog Platform with Comments

A full-stack blogging platform developed for creating, managing, and sharing blog posts with interactive comment functionality.

---

## Features

* User registration and login
* Secure authentication and authorization
* Create blog posts
* Edit and delete blog posts
* Comment section for user interaction
* Responsive design for desktop and mobile
* REST API integration
* Dynamic content management
* Database integration for posts and comments

---

## Tech Stack

### Frontend

* HTML
* CSS
* JavaScript
* React.js

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JWT Authentication
* bcrypt.js

### Deployment

* Vercel
* Render
* Netlify

---

## Project Structure

```bash id="z0e7yb"
blog-platform/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── controllers/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## Installation

### Clone Repository

```bash id="3b5rfc"
git clone <repository-link>
```

### Frontend Setup

```bash id="s0k2h4"
cd client
npm install
npm start
```

### Backend Setup

```bash id="1n7mxt"
cd server
npm install
node server.js
```

---

## Required Packages

```bash id="8fj2rd"
npm install express mongoose cors dotenv bcryptjs jsonwebtoken
npm install nodemon --save-dev
```

---

## Database Setup

Connect MongoDB using:

```javascript id="e6t7hf"
mongoose.connect('YOUR_MONGODB_URL')
```

---

## API Endpoints

| Method | Endpoint              | Description          |
| ------ | --------------------- | -------------------- |
| POST   | /api/auth/register    | Register user        |
| POST   | /api/auth/login       | Login user           |
| GET    | /api/posts            | Fetch all blog posts |
| POST   | /api/posts            | Create blog post     |
| PUT    | /api/posts/:id        | Update blog post     |
| DELETE | /api/posts/:id        | Delete blog post     |
| POST   | /api/comments         | Add comment          |
| GET    | /api/comments/:postId | Fetch comments       |

---

## User Functionalities

### Registered Users

* Create blog posts
* Edit own posts
* Delete own posts
* Add comments
* Interact with other users

### Visitors

* Read blog posts
* View comments

---

## Deployment

### Frontend

* Vercel
* Netlify

### Backend

* Render
* Railway

### Database

* MongoDB Atlas

---

## Expected Outcome

* Learn full-stack web development
* Understand authentication systems
* Gain experience with REST APIs
* Learn database integration
* Handle dynamic content management
* Implement user interaction features
* Deploy scalable web applications

---

## Future Enhancements

* Rich text editor
* Blog categories and tags
* Like and share functionality
* Search and filtering
* User profile pages
* Dark mode
* Admin moderation panel

---

## Author

Aishwarya
AIML Student | Full Stack Developer
