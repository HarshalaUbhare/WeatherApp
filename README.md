# WeatherApp


## Overview

This is a simple weather application built using Tkinter and the OpenWeatherMap API. It allows users to retrieve weather information for different cities in India.

## Features

- Select a state and city from the dropdown menu.
- Click the "Done" button to fetch real-time weather data.
- Displayed information includes weather climate, weather description, temperature, and pressure.

## Requirements

- Python 3.x
- Tkinter library
- requests library

## Usage

Clone the repository:

   ```bash
   git clone https://github.com/your-username/weather-application.git


**1. Install the required libraries:**


  pip install -r requirements.txt

**2. Run the application:**


  python weather_app.py

**3. Enter the city name, select a state, and click the "Done" button to fetch weather data.**

## Configuration
You need to obtain an API key from OpenWeatherMap and replace the placeholder in the data_get function in weather_app.py with your API key.
data = requests.get("https://api.openweathermap.org/data/2.5/weather?q="+city+"&appid=YOUR_API_KEY").json()


## Acknowledgments
- OpenWeatherMap for providing the weather data API.

Feel free to customize this template based on your specific project details and preferences. Make sure to replace placeholders like your-username and YOUR_API_KEY with your actual GitHub username and OpenWeatherMap API key.

