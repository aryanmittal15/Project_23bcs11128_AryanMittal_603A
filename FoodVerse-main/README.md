🍽️ Food Recipe Blog – MERN Stack Application

A full-stack Food Recipe Blog Application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack.
The application allows users to register, log in, add recipes, view recipes, and manage their own content with secure authentication.

🚀 Features
🔐 User Authentication

User Signup / Login

Password hashing using bcrypt

Secure routes using JWT (JSON Web Token)

🍳 Recipe Management

Add new recipe

View all recipes

View single recipe

Delete your recipe

Recipe stored in MongoDB with timestamps

Image upload support (served from /public folder)

🖥️ Frontend (React.js)

Modern responsive UI

Home page showing recipe list

Single recipe view

Add recipe form

Login/Signup pages

API communication using Axios

⚙️ Backend (Node + Express)

RESTful API

Organized MVC structure

Controllers, Routes, Middleware separation

MongoDB connection using Mongoose

Express static file hosting

📂 Project Structure
Food-Recipe/
│── backend/
│     ├── config/
│     ├── controller/
│     ├── middleware/
│     ├── models/
│     ├── routes/
│     ├── public/
│     ├── server.js
│     └── .env
│
└── frontend/
      ├── src/
      ├── public/
      └── package.json

🛠️ Tech Stack
Frontend

React.js

Axios

CSS / Tailwind / Styled Components (optional)

Backend

Node.js

Express.js

JWT Authentication

bcrypt

Multer (if using image upload)

Database

MongoDB

Mongoose ORM

⚙️ Backend Setup
1️⃣ Navigate to backend folder:
cd backend

2️⃣ Install dependencies:
npm install

3️⃣ Create a .env file:
PORT=3000
MONGO_URL=your-mongodb-url
JWT_SECRET=your-secret-key

4️⃣ Start the backend server:
npm start

🖥️ Frontend Setup
1️⃣ Navigate to frontend folder:
cd frontend/food-blog-app

2️⃣ Install dependencies:
npm install

3️⃣ Start the frontend:
npm start


React app usually runs at:

http://localhost:3000/

🔗 API Endpoints
User Routes
Method	Endpoint	Description
POST	/signup	Register user
POST	/login	Login user
GET	/profile	Get user profile
Recipe Routes
Method	Endpoint	Description
POST	/recipe/add	Add recipe
GET	/recipe/all	Get all recipes
GET	/recipe/:id	Get single recipe
DELETE	/recipe/:id	Delete recipe
📦 Folder Details
models/

Contains database schemas for:

User

Recipe

controller/

Contains business logic for:

User authentication

Recipe CRUD operations

middleware/auth.js

Verifies JWT token for protected routes.

routes/

API route definitions.

public/

Stores static files (images).

🚧 Future Improvements

Update recipe feature

User profile page

Add categories & tags

Search and filter options

Like & comment system

Cloud storage for images

🙌 Acknowledgements

This project is part of a MERN stack learning journey, demonstrating full-stack development with authentication, API design, and frontend-backend integration.

📜 License

This project is open-source and free to use under the MIT License.
