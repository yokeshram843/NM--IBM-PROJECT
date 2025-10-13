📝 Blogging Platform

A full-featured blogging web application that allows users to create, edit, and share blog posts easily. This platform provides a clean interface for readers and an intuitive dashboard for authors to manage their blogs.

🚀 Features

✍️ Create, Edit, and Delete Blogs

🧑‍💻 User Authentication (Login/Signup)

📸 Add Images and Rich Text Formatting

🕒 Timestamps for Each Post

💬 Comment Section for Readers

🔍 Search & Filter Blogs

📊 Admin Dashboard to Monitor Activities

🌗 Dark / Light Theme Toggle

📱 Fully Responsive Design

🛠️ Tech Stack

Category Technologies Used

Frontend HTML5, CSS3, JavaScript, Bootstrap / Tailwind CSS Backend Node.js, Express.js Database MongoDB (with Mongoose) Authentication JWT / Passport.js Version Control Git & GitHub Hosting Render / Vercel / Netlify

📂 Project Structure

Blogging-Platform/ │ ├── backend/ │ ├── server.js │ ├── routes/ │ ├── models/ │ └── controllers/ │ ├── frontend/ │ ├── index.html │ ├── styles/ │ ├── scripts/ │ └── pages/ │ ├── package.json ├── .env └── README.md

⚙️ Installation & Setup

Clone the Repository
git clone https://github.com/yourusername/blogging-platform.git

Navigate into the Project Directory
cd blogging-platform

Install Dependencies
npm install

Setup Environment Variables Create a .env file in the root directory:
MONGO_URI=your_mongodb_connection_string JWT_SECRET=your_secret_key PORT=5000

Run the Server
npm start

Visit in Browser
http://localhost:5000

📸 Screenshots

Home Page Blog Editor Dashboard

📖 API Documentation

Method Endpoint Description

GET /api/posts Fetch all blog posts POST /api/posts Create a new blog post GET /api/posts/:id Get a single post PUT /api/posts/:id Update a blog post DELETE /api/posts/:id Delete a blog post POST /api/auth/register Register a new user POST /api/auth/login User login

🧩 Challenges & Solutions

Challenge Solution

Implementing rich text editing Used Quill.js / CKEditor for smooth editor experience Managing authentication securely Used JWT and encrypted passwords using bcrypt Handling multiple user roles Added middleware-based role authorization Responsive UI Used Tailwind CSS / Bootstrap grid system

🧠 Future Enhancements

🪶 Add AI-powered content suggestions

📈 Add analytics for blog performance

💌 Email notifications for comments and followers

🧑‍🤝‍🧑 Multi-user collaboration mode

👨‍💻 Author

Name: yokesh.M Roll No: 822623104055 Institution: Naan Mudhalvan – Computer Science Engineering Project Title: Blogging Platform

⭐ How to Contribute

Fork the repository

Create a new branch: git checkout -b feature-name

Commit your changes: git commit -m "Added new feature"

Push to the branch: git push origin feature-name

Submit a Pull Request
