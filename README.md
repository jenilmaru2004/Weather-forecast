# Weather-forecast

### 🌦️ **Weather Info Fetcher Using OpenWeatherMap API**

This Python script is a **command-line weather app** that fetches and displays current weather details for any city entered by the user. It uses the **OpenWeatherMap API** and performs the following actions:

---

### 🔧 **How it Works**

1. **User Input**  
   The user is prompted to **enter a location** (city name).

2. **API Call Construction**  
   It builds a URL using the **OpenWeatherMap API**, including:
   - City name
   - API key

3. **API Request**  
   Sends a request to the OpenWeatherMap API and receives a **JSON response** with the city's current weather.

4. **Data Processing**  
   It extracts and converts key weather information:
   - Temperature (from Kelvin to Celsius & Fahrenheit)
   - Feels-like temperature
   - Humidity
   - Wind speed
   - Weather description
   - Sunrise and sunset time (converted from UTC to local time using the timezone offset)

5. **Output**  
   The results are printed in a human-readable format.

---

### 📋 **Sample Output**

```plaintext
Enter the location to check the weather: Ontario
Temperature in Ontario: 16.91°C or 62.44°F
Temperature in Ontario feels like: 15.99°C or 60.78°F
Humidity in Ontario: 51%
Wind speed in Ontario: 8.94m/s
General weather in Ontario: broken clouds
Sun rises in Ontario at 2025-04-03 06:34:36 local time.
Sun sets in Ontario at 2025-04-03 19:12:33 local time.
```

---


This is a simple command-line weather app that fetches weather data from the OpenWeatherMap API and runs inside a Docker container.

## 🚀 How to Run Dockerized

```bash
docker build -t weather-app .
docker run -it weather-app
```

---

### ✅ Summary

This is a great beginner-friendly script to:
- Learn about **APIs**
- Handle **JSON data**
- Use **datetime conversions**
- Apply **unit conversions**
- Dockerized app and is avaliable live on Github. 

