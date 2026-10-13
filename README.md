# ⛅ OmniWeather

A sleek, high-performance weather application with dynamic animations and interactive charts.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🚀 Key Features

### 🌍 Location & Search
* **Smart Search:** Search for any location worldwide with autocomplete (Geocoding API).
* **Automatic Detection:** Fast location detection via geolocation (GPS).

### 📊 Detailed Current Metrics
* **Core Weather:** Temperature and "Feels Like" index.
* **Atmospherics:** Humidity, dew point, and atmospheric pressure (with automatic conversion to mmHg).
* **Wind & Sun:** Wind speed and direction, UV index with dynamic color-coded hazard levels.
* **Additional Details:** Precipitation probability and amount, cloud cover, sunrise, and sunset times.

### 📈 Interactive Hourly Chart
* **Smooth Infographics:** SVG temperature chart for the upcoming 24 hours.
* **Dynamic Gradients:** Adaptive colors (warm / mild / cool) based on the average temperature.
* **Scrubbing Support (Touch & Mouse):** Swipe or drag across the chart to view a detailed tooltip for any specific hour.

### 📅 5 and 16-Day Forecast
* **Flexible Range:** Toggle seamlessly between 5-day and 16-day forecast views.
* **Visual Scales:** Easy-to-read distribution scale of temperature minimums and maximums.
* **Expandable Cards:** Tap any day to reveal a detailed breakdown (Morning, Day, Evening, Night) and extra parameters.

### ✨ Dynamic Visual Effects
* **Canvas Particles:** Background animated particles (stars, rain, snow, fog) that dynamically adapt to the time of day and current weather conditions.

---

## 🛠️ Tech Stack

* **HTML5 / Single File Solution** — The entire application is fully packed into a single file (or easily separated into modular components), making deployment incredibly simple.
* **Tailwind CSS (CDN)** — Modern UI styling, responsive layout, and Safe Area support for mobile devices (iOS / Android).
* **Lucide Icons** — Beautiful, minimalist vector icons.
* **Canvas API** — High-performance rendering of weather animations with Retina display support (Device Pixel Ratio).
* **Open-Meteo API** — Reliable, free data source for weather forecasts and geocoding (**no API keys required**).

---

## 📦 Quick Start

No installation of Node.js, npm, or project bundlers is required to run the project.

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. Allow location access (optional) and enjoy the forecast!
