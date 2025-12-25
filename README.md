📚 My Book Store — MERN Stack Application

My Book Store is a full-stack MERN web application that allows users to explore books, authenticate securely, and access content based on their login status. The project demonstrates end-to-end development using React, Node.js, Express, and MongoDB, with modern UI styling and secure authentication.

🚀 Features
🔹 Frontend

📖 Book listing with category-based display

🔍 Search functionality for books

🔐 Authentication UI (Signup / Login)

🛒 User-specific access control:

Non-logged-in users can view free books only

Logged-in users can access paid, entertainment, and sports books

🎨 Responsive UI using Tailwind CSS + daisyUI

⚡ Built with Vite for fast development

🔹 Backend

🧠 RESTful APIs built with Node.js & Express

🔑 Secure authentication using JWT

🔐 Password hashing with bcrypt

🗄️ MongoDB Atlas integration using Mongoose

👤 User signup and login APIs

🛠️ Tech Stack
Frontend

React,
Vite,
Tailwind CSS,
daisyUI

Backend

Node.js,
Express.js,
MongoDB (Atlas),
Mongoose


JWT Authentication

bcrypt


📁 Project Structure

bookStoreApp/

├── Frontend/    
├── Backend/     
└── README.md


⚙️ Setup & Installation

1️⃣ Clone the repository
git clone https://github.com/your-username/my-book-store.git
cd bookStoreApp

2️⃣ Backend Setup
cd Backend
npm install

Create a .env file inside Backend and add:

PORT=4001
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_jwt_secret

Start backend server:

npm start

3️⃣ Frontend Setup
cd ../Frontend
npm install
npm run dev


Frontend will start on:

http://localhost:5173

🔐 Authentication Flow

User passwords are securely hashed using bcrypt

JWT tokens are generated on login

Access to paid book categories is restricted to authenticated users

👨‍💻 Author & Contribution

Kuldeep Patidar

Designed and developed the entire full-stack application

Implemented frontend UI, backend APIs, authentication, and database integration

Managed complete project structure and version control independently

📌 Project Status

🚧 Deployment: Not deployed yet


📄 License

This project is for learning, practice, and portfolio purposes.
