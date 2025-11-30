# Weather Forecast Web App

A fully responsive weather application built with HTML, CSS, and vanilla JavaScript that uses the OpenWeatherMap API to display current weather for any city.

## Features

- Search for weather by city name
- View current weather conditions (temperature, description, humidity, wind speed)
- Dark/light mode toggle
- Responsive design for all device sizes
- Local storage for saving last searched city and theme preference
- Error handling for invalid cities or network issues
- Loading indicators during API requests

## Setup Instructions

1. Clone or download this repository
2. Get a free API key from [OpenWeatherMap](https://openweathermap.org/api)
3. Replace `YOUR_API_KEY` in `script.js` with your actual API key:
   ```javascript
   const API_KEY = "your_actual_api_key_here";
   ```
4. Open `index.html` in your browser

## How to Run Locally

1. After setting up your API key, simply open `index.html` in any modern web browser
2. Alternatively, you can use a local server:
   - With Python: Run `python -m http.server 8000` in the project directory and visit `http://localhost:8000`
   - With Node.js: Install `http-server` globally and run `http-server` in the project directory

## Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push this project to your repository
3. In your repository settings, go to "Pages"
4. Under "Source", select "Deploy from a branch"
5. Choose the branch (usually main) and folder (usually root /)
6. Click "Save" and your site will be deployed at `https://username.github.io/repository-name`

## Screenshots

![Weather App Light Mode](screenshots/light-mode.png)
*Weather App in Light Mode*

![Weather App Dark Mode](screenshots/dark-mode.png)
*Weather App in Dark Mode*

![Weather App Mobile View](screenshots/mobile-view.png)
*Weather App on Mobile Device*