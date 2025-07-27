# 🌤️ Weather App

Welcome to the **Weather App**! This project provides real-time weather updates for any city worldwide using the **OpenWeatherMap API**, presented through a clean and responsive UI built with HTML, CSS, and JavaScript.

---

## 📸 App Screenshots

### 🔍 1. Default Weather UI (Before Search)
![Default UI](https://github.com/PrashantKumar026/Weather-App/blob/main/Screenshot%202025-07-27%20180917.png?raw=true)

---

### 🌧️ 2. Weather Data for a Valid City (e.g., Mumbai)
![Mumbai Weather](https://github.com/PrashantKumar026/Weather-App/blob/main/Screenshot%202025-07-27%20181006.png?raw=true)

---

### ❌ 3. Invalid Location Error Handling
![Location Not Found](https://github.com/PrashantKumar026/Weather-App/blob/main/Screenshot%202025-07-27%20181151.png?raw=true)

---

## 🚀 Features

- 🌎 Get real-time weather updates for any city
- 📅 5-day forecast support (optional extension)
- 🌡️ Temperature, condition, humidity, and wind speed display
- ⚠️ Error handling for invalid city names
- 💻 Fully responsive and modern UI

---

## 🔧 Technologies Used

- **HTML** – Structure of the application
- **CSS** – Styling and layout using Flexbox
- **JavaScript** – Weather data fetching and DOM manipulation
- **OpenWeatherMap API** – Real-time weather data

---

## 💡 Core Functionality

**HTML**  
-> Defines the structure of the app including search input, weather display, and error section  
-> Includes input field, buttons, and containers for weather information display

**CSS**  
-> Adds modern styling with background colors, spacing, hover effects, and responsive layout  
-> Provides layout, colors, fonts, spacing, and Flexbox alignment  
-> Makes the app mobile-friendly

**JavaScript**  
-> Fetches data asynchronously from OpenWeatherMap  
-> Dynamically updates the DOM with real-time weather info  
-> Handles error messages if location is not found  
-> Maps weather conditions to appropriate icons

---

## ❌ Smart Error Handling

When a user types an invalid city (e.g., "Lll"), the app returns:

> **"Sorry, Location not found!!!"**

With a custom illustration, the error screen provides clear, friendly feedback, helping users understand what went wrong and try again.

---

## 📦 Getting Started

### Prerequisites
- A modern web browser
- An API key from [OpenWeatherMap](https://home.openweathermap.org/api_keys)

### Installation

```bash
git clone https://github.com/PrashantKumar026/Weather-App.git
cd Weather-App
