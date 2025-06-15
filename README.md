 # Flask Weather App 🌥🌥🌥
This is a simple web application built with Flask that displays current weather conditions for a specified city using the OpenWeatherMap API.

# Features :
Current Weather Display: Fetches and displays current temperature, "feels like" temperature, and weather status (e.g., "Clear sky", "Cloudy").

City Search: Allows users to input a city name to get its weather.


 # Prerequisites
Before you begin, ensure you have the following installed:

Python 3.x

An API Key from OpenWeatherMap. You'll need to sign up for a free account to get one.

# Installation 🚀🚀🚀
Follow these steps to get the application up and running on your local machine:

1. Create a virtual environment (recommended):

python -m venv venv

2. Activate the virtual environment:

On Windows:

.\venv\Scripts\activate

On macOS/Linux:

source venv/bin/activate

3. Install dependencies:

pip install -r requirements.txt

 4. Create a .env file:
In the root directory of your project, create a file named .env and add your OpenWeatherMap API key to it:

API_KEY=your_openweathermap_api_key_here

(Replace your_openweathermap_api_key_here with the actual API key you obtained from OpenWeatherMap.)

 # Usage
After completing the installation steps, you can run the application:

python server.py

The application will be accessible in your web browser at http://0.0.0.0:8000 (or http://localhost:8000).

 # Project Structure
requirements.txt: Lists all Python dependencies required for the project.

weather.py: Contains the core logic for fetching weather data from the OpenWeatherMap API.

server.py: The main Flask application file, handling routes and rendering templates.

.env: (Hidden file) Stores environment variables like your API key.

templates/: (Directory) This directory should contain your HTML template files (index.html, weather.html, city-not-found.html).

 
