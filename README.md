# 🌦️ Weather App

A modern, responsive weather application built with React, TypeScript, and Tailwind CSS. Get real-time weather information for any city around the world with a beautiful, intuitive interface.

## ✨ Features

- **City Search**: Search for weather in any city worldwide
- **Current Location**: Automatic weather detection using geolocation
- **Comprehensive Data**: Temperature, humidity, wind speed, visibility, and more
- **Unit Toggle**: Switch between Celsius and Fahrenheit
- **Dynamic Backgrounds**: Weather-responsive gradient backgrounds
- **Responsive Design**: Mobile-first design that works on all devices
- **Error Handling**: Graceful error messages and retry functionality
- **Demo Mode**: Works out of the box with mock data

## 🚀 Quick Start

The app runs in demo mode by default, so you can start using it immediately:

```bash
npm install
npm run dev
```

## 🔑 Using Real Weather Data

To use real weather data from OpenWeatherMap:

1. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
2. Create a `.env` file in the root directory
3. Add your API key:
   ```
   VITE_OPENWEATHER_API_KEY=your_api_key_here
   ```

## 🎯 Demo Cities

In demo mode, try searching for these cities to see different weather conditions:
- London (partly cloudy)
- New York (clear sky)
- Tokyo (light rain)
- Paris (overcast)
- Sydney (few clouds)
- Mumbai (thunderstorm)
- Berlin (light snow)
- Moscow (snow)

## 🛠️ Tech Stack

- **React 18** with TypeScript
- **Tailwind CSS** for styling
- **Lucide React** for icons
- **Vite** for development and building
- **OpenWeatherMap API** for weather data

## 📱 Responsive Design

The app is fully responsive and optimized for:
- Mobile phones (320px+)
- Tablets (768px+)
- Desktop computers (1024px+)

## 🎨 Design Features

- Glass-morphism effects
- Dynamic weather-based backgrounds
- Smooth animations and transitions
- Accessible color contrasts
- Modern card-based layout

## 🔧 Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📄 License

MIT License - feel free to use this project for learning or commercial purposes.