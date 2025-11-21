🌦️ Weather Dashboard

A modern, responsive Weather Dashboard that shows real-time weather, hourly temperature chart, 5-day forecast, air quality, UV index, wind direction, voice search, and dynamic weather-based backgrounds with sound effects.

🚀 Features

🔍 Smart Search


-Search any city


-Auto-suggestions (GeoDB API)


-Voice search 🎤


-Press Enter or click Search


🌤 Real-Time Weather Card


-Temperature + description


-High/Low


-Humidity, pressure, visibility


-Weather icons


-Dynamic background changes based on weather


-Weather-based sound effects


📊 Hourly Temperature Chart


-Next 24 hours


-Smooth responsive line chart via Chart.js


📅 5-Day Forecast


-Auto-generated from 3-hour interval data


-Scrollable design


-Max/Min temperatures + icons


🌫 Air Quality Index (AQI)


-AQI value (Good → Very Poor)


-Animated semicircle gauge with needle


🌡 UV Index


-UV value + category (Low → Extreme)


🌬 Wind Compass


-Rotating arrow based on wind direction


-Speed + gusts


🌓 Light/Dark Mode


-iPhone-style toggle


-Saves theme in localStorage


🌡 Unit Switch


-°C / °F toggle


-Saves preference


-Auto-refreshes data


📍 Auto Location


-Detects your location (with permission)


-Defaults to Hyderabad otherwise



🧑‍💻 Tech Stack


-HTML, CSS, JavaScript


-Chart.js


-OpenWeather API


-Open-Meteo API


-GeoDB Cities API


-LocalStorage


-Web Speech API



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


🔧 Setup Instructions


Clone repo

git clone https://github.com/Sahithi-a13245/Weather-Dashboard.git



Replace your OpenWeather API key in script.js
const API_KEY = "YOUR_API_KEY";



Open index.html in your browser
or use VS Code Live Server

🔮 Future Enhancements

Radar map

Weekly chart

Alerts

Favorites list

Installable PWA version
