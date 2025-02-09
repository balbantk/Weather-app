# Weather App

A simple weather application that fetches real-time weather data using the OpenWeatherMap API.

## Features
- Search for any city to get the current weather conditions
- Displays temperature, humidity, and wind speed
- Shows weather condition icons (Cloudy, Clear, Rain, Drizzle, Mist)
- Handles errors for invalid city names

## Technologies Used
- HTML, CSS, JavaScript
- OpenWeatherMap API

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/balbantk/weather-app.git
   ```
2. Open the project folder and locate `index.html`.
3. Run the file in a browser.

## Usage
1. Enter a city name in the search box.
2. Click the search button.
3. The weather details will be displayed.

## API Key Configuration
Replace the `apiKey` in `script.js` with your own API key from [OpenWeatherMap](https://openweathermap.org/api):

```js
const apiKey = "your_api_key_here";
```

## Folder Structure
```
/weather-app
│-- index.html
│-- style.css
│-- script.js
│-- images/
    │-- clouds.png
    │-- clear.png
    │-- rain.png
    │-- drizzle.png
    │-- mist.png
```

## License
This project is open-source and available for modification.