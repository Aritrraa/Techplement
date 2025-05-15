This is a Weather App. Please enter the city name to view the weather.

🌦️ WeatherNow – Real-Time Weather Forecast App
WeatherNow is a sleek and responsive weather forecasting web app built using HTML5, CSS3, and vanilla JavaScript. It provides real-time current weather data and 3-hour interval forecasts for the next 24 hours, fetched directly from the OpenWeatherMap API. Whether you're planning a trip or just curious about the climate, WeatherNow helps you stay informed with up-to-date meteorological data in a clean and interactive interface.

🌐 Live Demo
[Add your live demo link here, if hosted]

✨ Features
🔍 City Search: Search any city worldwide to get live weather data.

🌡️ Current Weather Info: Displays temperature, weather condition, and an icon representing the current weather.

🕒 Hourly Forecast: View the next 24 hours' forecast in 3-hour intervals, with icons and temperature.

🌤️ Visual Feedback: Weather icons fetched dynamically from OpenWeatherMap.

📱 Responsive Design: Works perfectly on both desktop and mobile screens.

⚡ Real-Time API Integration: Uses fetch() to asynchronously retrieve data without page reload.

🔁 Dynamic DOM Updates: Clear and refresh data upon each search for better UX.

🚀 Getting Started
Prerequisites
A web browser (Chrome, Firefox, etc.)

Internet connection

Free API key from OpenWeatherMap

Setup
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/WeatherNow.git
cd WeatherNow
Add your OpenWeatherMap API key
Edit script1.js and replace the placeholder key:

js
Copy
Edit
const apiKey = 'YOUR_API_KEY';
Run the App
Just open index.html in your browser.

🛠️ Technologies Used
Frontend:

HTML5 – Semantic structure

CSS3 – Custom styling and layout

JavaScript – Core logic and interactivity

OpenWeatherMap API – Weather and forecast data

📁 Project Structure
bash
Copy
Edit
├── index.html           # Main HTML page
├── style1.css           # Custom CSS styles
├── script1.js           # JavaScript logic for fetching and rendering weather
🔐 Privacy
No user data is stored or tracked.

Weather data is fetched securely via OpenWeatherMap API.

📌 Future Improvements
Add support for geolocation-based weather

Include weekly forecast with charts

Add language and unit switching (°C/°F)

Display weather conditions with background animation

📜 License
This project is open-source under the MIT License.
Feel free to use, modify, and share!
