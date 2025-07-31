# Weather Widget

Weather Widget is a React-based web app that allows users to get the current weather information for any city globally. It fetches data from the OpenWeatherMap API and displays it with a dynamic background and user-friendly interface.

## Features
- Search and view current weather details (temperature, humidity, etc.) for any city.
- Responsive UI built with Material-UI components.
- Dynamic weather background images based on the weather conditions (sunny, rainy, cold).
- Error handling for invalid city names.

## Technologies Used
- **React**: A JavaScript library for building user interfaces.
- **Material-UI**: A React component library for UI components.
- **OpenWeatherMap API**: Provides real-time weather data like temperature, humidity, and weather conditions.
- **CSS**: For styling the components.
- **PropTypes**: Used for prop validation in React components.
- **Axios/Fetch**: For making API requests.

## Installation

### Clone the Repository
1. First, clone the repository to your local machine:
2. git clone https://github.com/yourusername/weather-widget.git
3. cd weather-widget

## Install Dependencies
  Make sure you have Node.js installed, then run the following command to install the necessary dependencies:
--> npm install

## API Key Setup
To fetch weather data, you need an API key from OpenWeatherMap.

1. Go to OpenWeatherMap and create an account if you don't have one.
2. Obtain your API key from the dashboard.
3. Replace the API_KEY value in SearchBox.js with your own API key.(const API_KEY = "your_api_key_here")

## Folder Structure
/weather-widget
  ├── src
      ├── components
          ├── WeatherApp.js          # Main app component
          ├── SearchBox.js           # Component for the search bar
          ├── InfoBox.js             # Component to display weather info
      ├── App.js                      # Entry point of the app
      ├── index.js                    # Renders the app to the DOM
      ├── index.css                   # Global styles
      ├── SearchBox.css               # Styles for the SearchBox component
      ├── InfoBox.css                 # Styles for the InfoBox component
  ├── package.json
  ├── README.md                      # Project documentation

## Usage
1. Search for a City: Enter the city name in the input field and press the "Search" button to view the weather for that city.
2. Weather Information: The app displays information like the current temperature (in Celsius), humidity, feels-like temperature, and weather description.
3. Dynamic Background: Based on the weather data, the background image updates to reflect the weather conditions (e.g., sunny, rainy, cold).

## Code Overview
1. App.js: The main entry point of the app. It renders the WeatherApp component.
2. WeatherApp.js: This component manages the state of the weather data and renders both SearchBox and InfoBox.
3. SearchBox.js: A functional component for the user input. It fetches weather data based on the city name entered and passes the data to the parent component (WeatherApp).
4. InfoBox.js: Displays the weather data in a Material-UI Card format and changes the background image depending on weather conditions.
5. index.js: The entry point for rendering the React app to the DOM.


