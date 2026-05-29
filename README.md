# weather
# Weather API Integration using Python

## Project Overview

This project is a Python-based Weather Application that fetches real-time weather information for a user-specified city using the OpenWeatherMap API. The application sends an HTTP request to the weather API, receives data in JSON format, and displays important weather details such as temperature, humidity, and weather conditions.

## Objective

To learn API integration, HTTP requests, JSON parsing, and exception handling using Python.

## Technologies Used

* Python 3.x
* Requests Library
* JSON
* OpenWeatherMap API

## Features

* Accepts city name as user input
* Fetches real-time weather data
* Displays temperature, humidity, and weather conditions
* Handles invalid city names and network errors
* Uses JSON data parsing

## Project Structure

```text
Task2_Weather_API/
│
├── weather_app.py
├── README.md
└── screenshots/
```

## Installation

1. Install Python 3.x.
2. Install the Requests library:

```bash
pip install requests
```

3. Create a free API key from OpenWeatherMap.
4. Replace `YOUR_API_KEY` in the code with your API key.

## How to Run

```bash
python weather_app.py
```

Enter a city name when prompted.

## Sample Input

```text
Enter City Name: Hyderabad
```

## Sample Output

```text
Weather Report
--------------
City: Hyderabad
Temperature: 32°C
Humidity: 60%
Condition: Clear Sky
```

## Concepts Demonstrated

* API Integration
* HTTP GET Requests
* JSON Parsing
* Exception Handling
* User Input Processing

## Future Enhancements

* 5-day weather forecast
* GUI using Tkinter
* Weather icons and charts
* Multiple city comparison

## Author

Danush E
