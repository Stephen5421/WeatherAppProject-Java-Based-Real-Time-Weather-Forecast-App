# 🌤️ WeatherAppProject: Java-Based Real-Time Weather & Forecast App

## 🚀 Overview
The **WeatherAppProject** is a Java-based application that provides real-time weather updates and multi-day forecasts. It fetches data from the **OpenWeather API** and displays key weather parameters such as temperature, humidity, wind speed, and conditions. The application features an intuitive **Swing-based GUI** for a seamless user experience.

## 🛠 Technologies Used
- **Java (JDK 8+)** - Core programming language
- **Swing** - GUI framework for desktop applications
- **OpenWeather API** - For fetching weather data
- **Gson** - JSON parsing library

## 📌 Features
- **Current Weather & Multi-Day Forecast** - Retrieve real-time weather data and forecasts.
- **Unit Preferences** - Switch between metric (°C, m/s) and imperial (°F, mph) units.
- **Weather Alerts** - Get notifications for high and low temperature thresholds.
- **Persistent Settings** - User preferences (units and notifications) are saved for future sessions.

## 🔧 Installation
### Prerequisites
Ensure you have **Java JDK 8 or higher** installed.

### Setup & Execution
#### Step 1: Compile the Code
**On Windows:**
```bash
javac -cp "lib\gson-2.11.0.jar" -d bin src\*.java
```
**On Linux/macOS:**
```bash
javac -cp "lib/gson-2.11.0.jar" -d bin src/*.java
```

#### Step 2: Run the Application
**On Windows:**
```bash
java -cp "bin;lib\gson-2.11.0.jar" WeatherSwingApp
```
**On Linux/macOS:**
```bash
java -cp "bin:lib/gson-2.11.0.jar" WeatherSwingApp
```

## 🎨 UI Preview
![WeatherApp GUI](https://via.placeholder.com/600x300?text=WeatherApp+GUI)

## ⚙️ Usage
- **Check Current Weather** - Enter a city name and view weather conditions instantly.
- **Get Forecast** - Select a city and number of days to receive weather predictions.
- **Set Preferences** - Adjust units (Celsius/Fahrenheit) and enable/disable weather alerts.

## 💡 Future Enhancements
- **Add Animated Weather Icons** ☀️🌧️
- **Improve GUI Design** with modern themes 🎨
- **Introduce Voice Commands** for hands-free interaction 🎙️
- **Implement Dark Mode** for better UI experience 🌙

## 🔍 Troubleshooting
- Ensure the `gson-2.11.0.jar` file is inside the `lib` folder.
- Check your API key settings in `WeatherAPIManager`.
- Use correct path separators (`;` for Windows, `:` for Linux/macOS) when specifying the classpath.

## 🤝 Contributing
Pull requests and issues are welcome! Feel free to improve the app or report bugs.

---
⭐ If you find this project useful, don't forget to **star** this repository!

