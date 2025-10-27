# Frontend Mentor - Weather App 🌦️

![Design preview for the Weather app coding challenge](./preview.jpg)

## 🧩 Live Demo  
[🔗 Click here to view demo](https://mohammed-sabrymahdy.github.io/weather-app-main)

---

## 📖 Overview  
This is a **responsive Weather App** built for the [Frontend Mentor](https://www.frontendmentor.io) challenge.  
It allows users to **search for any city** and view **current weather conditions**, **hourly forecasts**, and **7-day forecasts** using the **Open-Meteo API** (or optionally WeatherAPI.com).  

---

## ✨ Features  
✅ Search for weather information by city name  
✅ View current temperature, weather icon, and location details  
✅ See additional metrics like *“feels like”*, *humidity*, *wind speed*, and *precipitation*  
✅ Browse a **7-day forecast** with daily highs/lows  
✅ View an **hourly forecast** for the selected day  
✅ Toggle between **Metric (°C)** and **Imperial (°F)** units  
✅ Responsive design for all screen sizes  
✅ Smooth hover and focus states for all interactive elements  

---

## ⚙️ Technologies Used  
- **HTML5**  
- **CSS3 / Flexbox / Grid / Animations**  
- **JavaScript (ES6)**  
- **Open-Meteo API**  
- *(Optional)* **WeatherAPI.com** for extended features  
- **Google Fonts (Lato 300, 400, 700)**  

---

## 🧠 How It Works  
1. User enters a city name in the search bar.  
2. The app sends a **geocoding request** to fetch latitude & longitude.  
3. Using these coordinates, it requests weather data from **Open-Meteo**.  
4. The app displays current, hourly, and daily forecasts dynamically.  

---

## 🧰 Setup & Installation  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/mohammed-sabrymahdy/weather-app-main.git
cd weather-app-main
