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
