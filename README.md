# 🌤️ Weather Forecast Dashboard with Power BI

Welcome to the **Weather Forecast Dashboard** project! This dynamic and interactive dashboard provides real-time and historical weather data analytics across multiple cities using live API integration. Built with **Power BI**, the dashboard delivers insightful **KPIs** including humidity, wind speed, UV index, visibility, pressure, and precipitation, empowering users to understand and visualize weather trends efficiently.

---

## 🚀 Project Overview

This project aims to:

- Connect to a real-time weather API
- Preprocess and model the data using Power Query and DAX
- Visualize multiple **Key Performance Indicators** (KPIs) per city
- Offer users an intuitive way to monitor, compare, and analyze weather patterns across locations
![Dashboard Preview](Images/preview.png)

---

## 📊 KPIs & Features

Each city displays:

- 🌡️ Temperature (Current / Min / Max)
- 💧 Humidity
- 🌬️ Wind Speed
- 🔭 Visibility
- 🌡️ Pressure
- 🌞 UV Index
- ☔ Precipitation
- 📆 7-Day Forecast (Optional depending on API limits)
- 📍 Interactive city selector
- 🧠 Smart filters and drill-down capabilities

---

## 🧪 Data Pipeline

### 1. 📥 API Integration

- **Source:**  WeatherAPI 
- Data fetched via web connector in Power BI (REST API)
- Cities are dynamically selected based on user interaction

### 2. 🧹 Data Preprocessing

- Null handling and type transformation using Power Query
- Unit normalization (e.g., converting wind speed to km/h or pressure to hPa)
- Timezone alignment for forecast accuracy

### 3. 📐 Modeling

- Star schema model: 
  - `Locations table
  - `Forcast_Hours`, `Current`, and `Forcast_Day`
- Measures built using **DAX** for KPIs, e.g., average humidity, max temperature, etc.

---

## 📍 Dashboard Features

- Slicer for city and date
- Heatmaps and trendlines for weather indicators
- Cards and gauges for current conditions
- Forecast visuals for strategic comparison


---

## 🧰 Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **REST API Integration**


