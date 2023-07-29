# Weather Detector
This is a Python script that serves as a weather detector, using the OpenWeatherMap API to retrieve weather information for a given city. The script fetches data such as temperature, weather description, humidity, wind speed, and date/time. Additionally, it creates a text file to store the retrieved weather data for future reference.

## How the Script Works
The script first imports necessary modules and sets up the API key required for making requests to the OpenWeatherMap API.

It prompts the user to enter the name of the city for which they want to obtain weather information.

The script constructs the API URL with the city name and the API key, then makes a request to the OpenWeatherMap API using the requests.get() method.

The API response is obtained in JSON format, and the relevant weather information is extracted from it.

The weather data is printed to the console, displaying the current temperature, weather description, humidity, wind speed, and the date and time of the request.

The script creates a text file named "textfile.txt" and writes the weather data into it in a structured format.

## Usage
When prompted, enter the name of the city for which you want to get weather information.

The script will display the weather stats on the console.

It will also create a "textfile.txt" containing the same weather information.

Note: Make sure you have an active internet connection and the required requests module installed before running the script.

## Important Note
To use this script, you need to have a valid API key from OpenWeatherMap. If you don't have one, you can sign up on their website (https://openweathermap.org/) to get an API key. Replace the api_key variable with your actual API key in the script before running it.

## Example Output

Weather Stats for - CITY_NAME  || 29 Jul 2023 | 10:30:45 AM

Current temperature is: 25.87 deg C

Current weather desc  : Clear sky

Current Humidity      : 58 %

Current wind speed    : 4.5 kmph
