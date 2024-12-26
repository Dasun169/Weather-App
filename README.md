# Weather App 🌦️

## Overview
This is a simple **Weather App** built with **HTML**, **CSS**, and **JavaScript**. The app allows users to input a city name and get real-time weather data, including:

- **Weather type** (e.g., sunny, rainy, cloudy)
- **Humidity level** 🌫️
- **Wind speed** 🌬️

The app fetches weather data from the **OpenWeatherMap API** and displays it in a clean, user-friendly interface.

---

## Features
- Real-time weather information based on the city name.
- Displays the weather type, humidity, and wind speed.
- Powered by the **OpenWeatherMap API** for accurate weather data.
- Simple and responsive user interface.

---

## Technologies Used
- **HTML** for the structure of the webpage.
- **CSS** for styling and making the app visually appealing.
- **JavaScript** for interacting with the OpenWeatherMap API and dynamically updating the weather information.
- **OpenWeatherMap API** to fetch real-time weather data.

---

## How to Use

### 1. Clone the Repository:
To get started, clone this repository to your local machine using the following command:

```bash
git clone https://github.com/Dasun169/Weather-App.git
```
### 2. Create an Account on OpenWeatherMap:
Go to OpenWeatherMap and create a free account.
Once logged in, navigate to your API keys section and generate a new API key.
### 3. Get the API Key:
After generating the API key, you will have a unique string that you can use to access OpenWeatherMap's weather data. It will look something like this:
```bash
your_api_key_here
```
### 4. Edit the JavaScript File:
Open the project folder and navigate to script.js.
Replace the placeholder API_Key with your own API key that you generated in the previous step.
Example URL:
```bash
const api_url = `https://api.openweathermap.org/data/2.5/weather?q=${city_name}&units=metric&appid=${API_Key}`;
```
### 5. Open the HTML File:
Open index.html in your browser, and the app will prompt you to enter a city name to see the weather data.
## Screenshot

## Contributing
If you'd like to contribute to this project, feel free to fork the repository, create a branch, and submit a pull request. Any contributions or suggestions are welcome!
