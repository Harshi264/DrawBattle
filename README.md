🎨 Draw Battle – Real-Time Multiplayer Drawing Game
A full-stack, real-time multiplayer drawing and guessing game built with the MERN stack, Socket.io, and HTML5 Canvas. Compete in timed rounds, draw and guess, and climb the leaderboards!

🧠 Table of Contents
✨ Features

🖥 Tech Stack

📦 Project Structure

🚀 Getting Started

🔧 Scripts & Commands

📸 Screenshots

📌 Roadmap

🤝 Contributing

📄 License

✨ Features
🔄 Real-time multiplayer gameplay using Socket.io

🎯 Turn-based and round-based drawing/guessing system

👤 Role management (Drawer & Guessers)

🖌 Live canvas with drawing tools (pencil, eraser, size control)

🏆 Dual leaderboards (recent game - MongoDB, global - JSON)

🔔 Toast notifications for game events

💾 Persistent scoring with LocalStorage & MongoDB

🎉 Custom UI animations (confetti, glow effects, etc.)

📊 Performance monitoring using Web Vitals

🖥 Tech Stack
Frontend
Category	Tech/Library
Core Framework	React.js ^19.1.0
Routing	React Router DOM ^7.7.0
Real-time Communication	Socket.io Client ^4.8.1
Styling	Tailwind CSS ^3.4.3, PostCSS, Autoprefixer
UX Enhancements	React Toastify ^11.0.5
Drawing	Canvas API
Storage	LocalStorage API
Testing	React Testing Library, Jest DOM, User Event
Linting	ESLint (react-app config)

Backend
Category	Tech/Library
Runtime & Framework	Node.js, Express.js ^5.1.0
Real-time Communication	Socket.io ^4.8.1
Database	MongoDB, Mongoose ^8.17.0
Security & Config	CORS ^2.8.5, dotenv ^17.2.0
File Ops & Locking	fs.promises, proper-lockfile ^4.1.2
Dev Tools	Nodemon ^3.1.10

📦 Project Structure
/client (React Frontend)
├── /components         # Reusable UI components
├── /pages              # Game screens (Home, Canvas, GameRoom)
├── /styles             # Tailwind CSS and custom animations
├── /utils              # Helper functions
└── /sockets            # Socket.io client logic

/server (Node.js Backend)
├── /routes             # REST API endpoints (leaderboard)
├── /controllers        # Controller logic
├── /models             # Mongoose schemas
├── /sockets            # Socket.io event handling
├── /utils              # File locking, state mgmt
├── /data               # Global leaderboard JSON
└── server.js           # Entry point
🚀 Getting Started
Prerequisites
Node.js (v18+)

npm or yarn

MongoDB instance (local or cloud)

Setup Instructions
Clone the repo:

git clone https://github.com/your-username/draw-battle.git
cd draw-battle
Install dependencies:

cd client
npm install
cd ../server
npm install
Environment Setup (server/.env):

MONGO_URI=your_mongodb_connection_string
PORT=5000
Run the app:

Start backend:

cd server
npm run dev
Start frontend:

cd client
npm start
Visit: http://localhost:3000

🔧 Scripts & Commands
Frontend
Command	Description
npm start	Starts development server
npm run build	Builds production version
npm test	Runs unit tests

Backend
Command	Description
npm run dev	Starts server with Nodemon
node server.js	Starts server in production

📸 Screenshots
Add images of the gameplay, UI, canvas, and leaderboards.

📌 Roadmap
 Core drawing and guessing logic

 Real-time canvas syncing

 Turn-based rounds

 MongoDB-based leaderboard

 Avatar selection and chat

 Drawing tool upgrades (shapes, colors)

 Private game rooms with invite links

 Admin dashboard

🤝 Contributing
Contributions are welcome! Fork the repo, create a branch, and submit a pull request. Read CONTRIBUTING.md for guidelines.

📄 License
This project is licensed under the MIT License.
