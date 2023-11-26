The ChatGPT Weather App is a web application built with Flask that allows users to obtain current weather details for a specific city, state, and country combination. 
It utilizes the OpenWeatherMap API to fetch real-time weather information based on user-provided location data.


Features
Weather Information: Fetches current weather data including temperature, description, and weather icon.
User Input: Provides a simple form for users to input city, state, and country details.
Interactive Interface: Presents weather details in a user-friendly manner.

Technologies Used
Flask: Python-based web framework for building the application.
OpenWeatherMap API: External API used to fetch real-time weather data.
HTML/CSS: Frontend for presenting weather information to users.

Prerequisites
Python: Ensure Python 3.x is installed on your system.
Dependencies: Install required packages listed in requirements.txt.
OpenWeatherMap API Key: Obtain an API key from OpenWeatherMap and set it as an environment variable named (API_KEY).

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/chatgpt-weather-app.git
cd chatgpt-weather-app
Create a virtual environment:

python3 -m venv venv
source venv/bin/activate  # For Windows, use venv\Scripts\activate

Install dependencies:
pip install -r requirements.txt
Usage
Run the application:
python app.py

Enter the city, state, and country to fetch current weather details.

Contributing
Contributions are welcome! Feel free to open issues or pull requests for any enhancements or bug fixes.

License
This project is licensed under the MIT License. See the LICENSE file for details.



