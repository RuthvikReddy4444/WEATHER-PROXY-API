🌤️ Weather Proxy API – Full-Stack Weather Application

This project is a full-stack weather application that provides real-time weather information using a secure Weather Proxy API.

Instead of calling the external OpenWeather API directly from the browser (which exposes the API key), the project uses a Node.js Express backend as a proxy layer to securely fetch and reformat weather data.

🚀 Features

Secure backend proxy (API key is never exposed)

Real-time weather updates

Clean, responsive frontend UI

Error handling for invalid city names

Modern API structure

📂 Project Structure
weather-app/
│
├── backend/
│   ├── src/
│   │   ├── index.js
│   │   ├── weatherClient.js
│   │   └── routes/weather.js
│   ├── package.json
│   └── .env
│
└── frontend/
    ├── index.html
    ├── style.css
    └── script.js

⚙️ Backend Setup
cd backend
npm install


Create a .env file:

OPENWEATHER_API_KEY=your_api_key
PORT=3001


Run backend:

npm run dev

🌐 Frontend Setup

Open frontend/index.html in browser or use Live Server.

🔗 API Endpoint

Example request:

http://localhost:3001/weather?city=Hyderabad

👥 Team Members

Thokala Srivalli – 2403A510B2

Aidulapuram Vamshi Krishna – 2403A510B3

Jaitaram Ruthvik Reddy – 2403A510B5
