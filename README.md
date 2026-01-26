🌦️ Weather App

A simple and responsive Weather Application built using HTML, CSS, and JavaScript that fetches real-time weather data using the OpenWeatherMap API.

🚀 Features

🔍 Search weather by city name

🌡️ Displays temperature (°C)

💧 Shows humidity

💨 Shows wind speed

🌤️ Dynamic weather icons (Clear, Clouds, Rain, Mist, Drizzle)

❌ Error handling for invalid city names

📱 Fully responsive design (mobile-friendly)

🛠️ Tech Stack

HTML5 – Structure

CSS3 – Styling & Responsive Layout

JavaScript (ES6) – API handling & DOM manipulation

OpenWeatherMap API – Live weather data

📂 Project Structure
Weather-App/
│
├── index.html        # Main HTML file
├── style.css         # Styling and responsiveness
├── script.js         # Weather API logic
├── img/              # Weather icons & assets
│   ├── clear.png
│   ├── clouds.png
│   ├── rain.png
│   ├── drizzle.png
│   ├── mist.png
│   ├── humidity.png
│   ├── wind.png
│   └── search.png
└── README.md         # Project documentation

⚙️ How It Works

User enters a city name

App sends a request to OpenWeatherMap API

Weather data is fetched asynchronously using fetch()

UI updates dynamically with:

Temperature

City name

Humidity

Wind speed

Weather icon

If city name is invalid → error message is shown

🧠 JavaScript Concepts Used

async / await

Fetch API

DOM manipulation

Event listeners

Conditional rendering

Error handling

🖥️ Preview

Minimal and clean weather card UI
Real-time weather data with responsive layout

(You can add screenshots or live demo link here)

🔑 API Used

OpenWeatherMap API

https://api.openweathermap.org/data/2.5/weather


⚠️ Note:
Replace the API key in script.js with your own key for production use.

📌 How to Run Locally

Clone the repository

git clone https://github.com/itadi02/weather-app.git


Open index.html in your browser

Search any city 🌍

📚 Learning Outcomes

Working with real APIs

Handling async JavaScript

Dynamic UI updates

Responsive design techniques

Error handling in real projects

🚧 Future Improvements

7-day weather forecast

Location-based weather (GPS)

Temperature unit toggle (°C / °F)

Loading animation

Better error messages

⭐ Support

If you like this project, don’t forget to star ⭐ the repository
It motivates me to build more real-world projects 🚀
