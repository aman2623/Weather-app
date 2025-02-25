# 🌤 Weather App  

## 📌 Overview  
This is a simple Weather App that allows users to check the current weather of any city. The app fetches real-time weather data from the OpenWeather API and displays key information like temperature, weather conditions, humidity, wind speed, and more.  

## 🚀 Features  
- Search weather by city name  
- Displays temperature, humidity, and weather conditions  
- Background changes dynamically based on weather status  
- Responsive design for mobile and desktop  
- Alerts for invalid or empty input  

## 🛠 Technologies Used  
- HTML  
- CSS  
- JavaScript  
- OpenWeather API  
- SweetAlert (for alerts)  

## 🔧 Setup & Installation  
1. Clone this repository:  
   ```sh
   git clone https://github.com/yourusername/weather-app.git
   ```  
2. Navigate to the project directory:  
   ```sh
   cd weather-app
   ```  
3. Open `index.html` in your browser.  

## 📜 Usage  
- Enter a city name in the search box and press "Enter".  
- The app will fetch and display the weather details.  
- If the city is invalid, an alert will appear.  

## 🖼 Screenshots  
_(Add some screenshots here if available)_  

## 📌 API Configuration  
This project uses OpenWeather API. Replace the `weatherApi.key` in `script.js` with your own API key:  
```js
const weatherApi = {
    key: 'YOUR_API_KEY_HERE',
    baseUrl: 'https://api.openweathermap.org/data/2.5/weather'
}
```  

## 📜 License  
This project is licensed under the MIT License.  
