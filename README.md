🤖 AI Virtual Assistant

Your own smart AI-powered voice assistant — built with Gemini AI, Web Speech API, and the MERN Stack. Talk, listen, and interact like a real assistant ✨

🚀 Live Demo

🔗 Frontend (Render) → https://ai-virtualassistant-fr.onrender.com

🔗 Backend (Render) → https://ai-virtualassistant-b.onrender.com

🧠 Overview

AI Virtual Assistant is a full-stack project that lets users:

🗣 Talk to the assistant using voice input
💬 Get intelligent AI replies via Gemini API
🔐 Login / Signup securely with JWT authentication
🖼 Upload & customize your assistant’s image and name
🎨 Personalize branding and voice
📱 Fully responsive UI built with Tailwind CSS

⚙️ Tech Stack
Layer	Technologies
Frontend	React, Tailwind CSS, Vite, Web Speech API
Backend	Node.js, Express.js
Database	MongoDB Atlas
AI Model	Gemini API (Google Generative AI)
Auth & Security	JWT, bcryptjs
File Uploads	Multer, Cloudinary
Hosting	Render (Frontend + Backend)
🧩 Key Features

✅ Voice Input + Output: Talk and listen like JARVIS
✅ Gemini AI Integration: Smart, contextual conversations
✅ JWT Authentication: Secure login and signup
✅ Custom Assistant: Change image, name, and voice
✅ Responsive UI: Works on all screen sizes
✅ Cloud Uploads: Securely store images on Cloudinary
✅ MongoDB Atlas: Reliable and scalable cloud database

🛠 Setup Instructions
⿡ Clone Repository
git clone https://github.com/nehayadav25-ny/AI_virtualAssistant.git
cd AI_virtualAssistant

⿢ Backend Setup
cd backend
npm install


Create a .env file inside the backend folder:

PORT=8000
MONGODB_URL="your-mongodb-atlas-connection-string"
JWT_SECRET="NEHAYADAV"
GEMINI_API_URL="https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash:generateContent?key=YOUR_GEMINI_API_KEY"
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret


Run the backend:

npm run dev

⿣ Frontend Setup
cd ../frontend
npm install
npm run dev

🧠 How It Works

🎙 User speaks using Web Speech API

🧩 Speech is converted to text

🤖 Text is sent to Gemini AI for smart response

🔊 Assistant replies using Speech Synthesis

💾 All data is stored securely in MongoDB Atlas

🌐 Deployment

Frontend: Render → ai-virtualassistant-fr.onrender.com

Backend: Render → ai-virtualassistant-b.onrender.com

Database: MongoDB Atlas (Cloud Database)

🧑‍💻 Author

👩‍💻 Neha Yadav
🌐 GitHub: @nehayadav25-ny

🪪 License

This project is licensed under the MIT License — free to use, modify, and share.

💬 “Your voice, your assistant, your AI — powered by Gemini.” ✨
