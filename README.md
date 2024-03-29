### [OpenWeatherMap API](https://openweathermap.org/api) App

### Description

This app uses the OpenWeatherMap API to retrieve the current weather and five-day forecast for a given city.
For the current weather forecast, the [Built-in Geocoding](https://openweathermap.org/current#builtin) API is used.
For the five-day forecast, OpenWeather's [Geocoding API](https://openweathermap.org/api/geocoding-api) instead. This API retrieves the weather data based on the user's
geographical location and is responsible for more accurate results. The app is built with Node.js, Express, and EJS. MongoDB Atlas is used to store the user's search history.

### Tech Stack

-   [Node.js](https://nodejs.org/en/)
-   [Express](https://expressjs.com/) framework
-   [EJS](https://ejs.co/) templating
-   [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) cloud database
-   [MongoDB Charts](https://www.mongodb.com/products/charts) data visualization
