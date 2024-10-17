# Weather_Monitoring

## Overview
This project is a real-time weather monitoring system that retrieves weather data from the OpenWeatherMap API, processes it to provide daily summaries, and triggers alerts based on user-configurable thresholds.

## Features
- Continuous retrieval of weather data for multiple cities in India.
- Daily weather summary calculations including average, maximum, and minimum temperatures.
- Alerting mechanism for temperature thresholds.
- Visualization of daily weather summaries.

## Setup Instructions

1. *Clone the repository*:
   ```bash
   git clone <repository-url>
   cd weather_monitoring
2. Set up a virtual environment (optional): python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
3. Install required packages: pip install -r requirements.txt
4. Set your OpenWeatherMap API key: Export your API key as an environment variable: export OPENWEATHERMAP_API_KEY='your_api_key_here'  # On Windows use set
5. Initialize the database: python -c "from src.db import init_db; init_db()"
6. Run the application: python src/main.py 
