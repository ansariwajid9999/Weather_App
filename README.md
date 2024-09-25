# Live Weather API App
This is a simple live weather app that fetches weather data for any city using the OpenWeatherMap API. Users can input a city name, and the app will display the temperature, humidity, weather description, and an emoji representing the weather condition.

## Features
- Fetches current weather data for any city.
- Displays temperature in Celsius.
- Shows humidity levels and weather description.
- Displays an emoji based on the weather condition (e.g., ☀️ for clear skies, 🌧️ for rain).
- Error handling for invalid inputs or fetch failures.
  
## Demo
![Screenshot 2024-09-25 130237](https://github.com/user-attachments/assets/25d2d387-fbc8-41f5-a2f8-96d6b64c67cf)

## Technologies Used
- HTML, CSS, JavaScript
- OpenWeatherMap API
  
## How It Works
**The user enters a city name in the input field.**
**The app makes an API call to the OpenWeatherMap service using the provided city name and API key.**
**The weather data is fetched and displayed on the screen:**
    - City name**
    - Temperature (in Celsius)
    - Humidity
    - Weather description
    - A corresponding weather emoji
    
## API Endpoint Example:
- bash
- Copy code
`https://api.openweathermap.org/data/2.5/weather?q={city}&appid={apiKey}`

## Where to Add #
- In your weather app code, you can add the # for IDs in the HTML structure. Typically, # is used to target elements by their ID in CSS or JavaScript. Here's an example:

## In the HTML:

- Add an ID to any element you want to style or manipulate with JavaScript.
- html
- Copy code
`<div id="weatherDisplay"></div>`

## In the CSS:
- Copy code from given github repository

## In JavaScript:
- Copy code from given github repository

## Setup Instructions
### Prerequisites
- A valid OpenWeatherMap API key.
 
## Steps to Run:
### Clone the repository:
- bash
- Copy code
`git clone https://github.com/your-username/your-repo-name.git`
- Open the project folder and edit the apiKey variable in the app.js file with your OpenWeatherMap API key.
- javascript Copy code
`const apiKey = "your-api-key";`
- Open index.html in your web browser.
  
### Error Handling
- Displays an error message if the city is not found.
- Handles cases where the user submits an empty input.

## Contact
For any questions or suggestions, feel free to contact me at `ansariwajid9999@gmail.com`.
