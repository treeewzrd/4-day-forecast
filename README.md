# Weather Dashboard 🌦️

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/node-%3E=18.0.0-green.svg)](https://nodejs.org/)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](#)
[![Vite](https://img.shields.io/badge/vite-%5E5.2.0-blueviolet.svg)](https://vitejs.dev/)

A responsive weather dashboard that allows users to search for current and forecasted weather conditions for cities worldwide. The app saves your search history and provides a seamless user experience.

---

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)

---

## Demo

![Weather Dashboard Screenshot](https://res.cloudinary.com/dswrez3vz/image/upload/v1747648963/screenshot_svhmtg.jpg)  


**Live Site:** [https://your-deployment-link.com](https://four-day-forecast.onrender.com/)  


---

## Features

- 🌍 Search for any city worldwide
- 📅 View current weather and 5-day forecast
- 💾 Search history with quick access and delete options
- ⚡ Fast, responsive, and mobile-friendly UI
- 🔒 Secure API key management

---

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/weather-dashboard.git
   cd weather-dashboard

2. **Install dependencies:**

npm run install

3. **Set up environment variables:**
  Create a .env file in the server/ directory with your OpenWeatherMap API key:

weathermapAPI_KEY=your_open_api_key
API_BASE_URL=https://api.openweathermap.org
PORT=3001

4. **Run the app in development**

npm install concurrently 

npm run start:dev

5. **Build for production:**

npm run build
npm start

## Usage

Enter a city name in the search bar and hit "Search".
View the current weather and 5-day forecast.
Click on a city in the search history to view its weather again.
Remove cities from your search history using the delete button.

## Technologies Used

TypeScript
Node.js
Express
Vite
Day.js
OpenWeatherMap API
UUID

## API Reference

POST /api/weather/
Request body: { "cityName": "City" }
Returns: Weather data for the city.

GET /api/weather/history
Returns: Array of previously searched cities.

DELETE /api/weather/history/:id
Removes a city from search history.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License.
