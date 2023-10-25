# Weather App

This Weather App is a web application that provides real-time weather information for a specific location using external APIs. It allows users to search for weather data for any city and, with their permission, provides weather information for their current location.

## Features

- **City Weather Search:** Users can search for weather information in any city worldwide by entering the city name into the search bar.

- **Geolocation:** With user permission, the app detects the user's current location and displays the weather information for that location.

- **Current Weather Data:** The app provides up-to-date weather data, including temperature, humidity, wind speed, and weather conditions.

## Technologies Used

- **HTML, CSS, and JavaScript:** The frontend is built using these web technologies to create a responsive and user-friendly interface.

- **API Integration:** The app integrates with external weather APIs to retrieve real-time weather data for the specified city and the user's current location.

## Getting Started

1. Clone this repository to your local machine.

2. Open the `index.html` file in your preferred web browser.

3. Allow location access when prompted to enable geolocation-based weather data.

4. Use the search bar to enter a city and retrieve weather information.

## API Usage

This app uses the following weather API to retrieve weather data:

- [OpenWeatherMap API](https://openweathermap.org/api)

To use the API, you will need to sign up for an API key from OpenWeatherMap and replace the placeholder in the code with your own key.

```javascript
const apiKey = 'YOUR_API_KEY_HERE';
```
## Contributing
If you'd like to contribute to this project, please follow the standard guidelines for contributing to open-source projects. Fork the repository, create a new branch for your feature or bugfix, and submit a pull request.


