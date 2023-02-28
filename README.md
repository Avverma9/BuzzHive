BuzzHive
BuzzHive is a social media web application that allows users to connect with each other by creating profiles, sharing posts, and commenting on each other's posts. BuzzHive is built using the MERN stack, which includes MongoDB, Express, React, and Node.js.

Features
User registration and login
User profile creation and customization
Ability to create, edit, and delete posts
Ability to comment on posts
Like and unlike posts
Follow and unfollow users
Real-time notifications for new posts and comments
Responsive design for mobile and desktop screens
Installation
Clone the repository: git clone https://github.com/Avverma9/BuzzHive
Install dependencies in both the root folder and client folder:
bash

Copy code
cd buzzhive
npm install
cd client
npm install

Create a .env file in the root folder and add the following variables:
makefile

Copy code
MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-jwt-secret>

Start the server and client concurrently:
npm run dev
Open your browser and navigate to http://localhost:3000 to see the BuzzHive application.
Technologies Used
MongoDB
Express
React
Node.js
Mongoose
JWT
Socket.io
Axios
Material UI
Contributors
Prachi Sharma
Ankush Rai
