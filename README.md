![Repo Size](https://img.shields.io/github/repo-size/00ayushsingh/admin-user-management?style=for-the-badge)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-18.x-green?style=for-the-badge&logo=node.js)

A Task Management System where an Admin can add users to a portal, and users must upload authentication documents for verification. The project includes Swagger API documentation, Docker support, and a MongoDB database.

## Features:
- Admin can add, update, delete users.
- Users must upload authentication documents.
- Admin can view analytics of user activities.
- Users can update their qualifications.
- API documentation using Swagger UI.
- Dockerized backend with MongoDB as the database.

## Installation & Setup
### Clone the repository
- `git clone https://github.com/00ayushsingh/admin-user-management.git`
- `cd admin-user-management`

### Install dependencies
- `npm install`

### Setup environment variables
- Create a .env file in the root directory and add:
```
PORT=4000
MONGO_URI=mongodb://localhost:27017/admin-user-management
DATABASE_NAME=admin-user-management
```

### Run the server
- `npm run dev`
- The server will start at `http://localhost:4000`.

## Docker Setup
### Build & Run the Docker Containers
- `docker-compose up --build`
- This will start:
  - Backend API : `http://localhost:5000`
  - MongoDB : `mongodb://mongo:27017`

### Stop Containers
- `docker-compose down`