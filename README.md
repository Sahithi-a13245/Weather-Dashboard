🌦️ Weather Dashboard

A modern, fully-responsive Weather Dashboard that displays real-time weather, hourly temperature trends, a 5-day forecast, AQI, UV index, wind direction, voice search, dynamic backgrounds, and weather-based sound effects.

This project delivers a polished and interactive weather experience using HTML, CSS, JavaScript, Chart.js, and live APIs from OpenWeather, Open-Meteo, and GeoDB Cities.

🔗 Live Demo

🚀 https://weather-dashboard-murex-rho.vercel.app/

🖼️ Screenshot

🎥 Live Demo (Video Preview)

https://github-production-user-asset-6210df.s3.amazonaws.com/189539476/517343050-8b0f7164-d262-4def-aa55-95938c8a69a2.mp4

🚀 Features
🔍 Smart Search

Search by city

Auto-suggestions (GeoDB API)

Voice search (Web Speech API)

Press Enter or click Search

🌤 Real-Time Weather

Temperature, description, high/low

Humidity, pressure, visibility

Weather icons

Dynamic weather-based background

Weather sound effects (rain, thunder, wind, etc.)

📊 Hourly Temperature Chart

24-hour temperature trend

Animated Chart.js line graph

Fully responsive

📅 5-Day Forecast

Auto-generated from 3-hour interval data

Max/Min temperatures

Weather icons

Scrollable on mobile

🌫 Air Quality Index (AQI)

AQI value (Good → Very Poor)

Color-coded gauge with rotating needle

🌡 UV Index

UV intensity (Low → Extreme)

Real-time data from Open-Meteo API

🌬 Wind Compass

Animated rotating arrow

Wind speed & gust info

🌓 Light / Dark Mode

iPhone-style slider toggle

Saves preference in localStorage

🌡 °C / °F Unit Switching

Instant unit switch

Saves setting

Auto-refreshes weather data

📍 Auto Location

Uses geolocation to load local weather

Falls back to Hyderabad if denied

🛠️ Tech Stack

HTML5, CSS3, JavaScript

Chart.js

OpenWeather API

Open-Meteo API

GeoDB Cities API

LocalStorage

Web Speech API

Vercel Deployment

📂 Project Structure
WeatherDashboard/
│── index.html
│── style.css
│── script.js
│── sounds/
      ├── clear.mp3
      ├── cloud.mp3
      ├── rain.mp3
      ├── snow.mp3
      ├── thunder.mp3
      ├── wind.mp3

⚙️ Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/Sahithi-a13245/Weather-Dashboard.git
cd Weather-Dashboard

2️⃣ Add API Key

Replace your API key inside script.js:

const API_KEY = "YOUR_API_KEY_HERE";

3️⃣ Run Locally

Open:

index.html


or use VS Code Live Server.

🔮 Future Improvements

Radar/precipitation map

Weather alerts

Weekly temperature chart

Favorite cities

Installable PWA (Add to Home Screen)

👩‍💻 Author

Aditya Sahithi
A modern and interactive Weather Dashboard using real-time APIs and beautiful UI elements.
