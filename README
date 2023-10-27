WeatherData Class: Represents weather data for a location, including attributes like location, temperature, and condition. It has a constructor to initialize these attributes and an overridden toString method to provide a string representation of the weather data.

WeatherProvider Interface: Defines the contract for classes that provide weather data. It includes a single method, getWeather, which takes a location as an argument and returns a WeatherData object.

OpenWeatherMapProvider Class: Implements the WeatherProvider interface and fetches weather data from the OpenWeatherMap API. It uses a Map to simulate the data, and the getWeather method maps the data to a WeatherData object.

WeatherAPIProvider Class: Similar to OpenWeatherMapProvider, it implements the WeatherProvider interface but simulates weather data from a different source.

OpenWeatherMapAdapter and WeatherAPIAdapter Classes: These classes are adapters that implement the WeatherProvider interface and wrap the respective provider classes. They delegate the getWeather method to the corresponding provider.

MobileApp Class: Represents the mobile weather application. It has a constructor that takes a WeatherProvider and a displayWeather method to fetch and display weather data for a specified location.

In the main method of the MobileApp class, two instances of the mobile app are created: one using the OpenWeatherMap provider and another using the WeatherAPI provider. Each instance fetches and displays weather data for a specific location.

This code demonstrates a basic use of interfaces, adapters, and composition to fetch and display weather data from different providers. It can be extended to support additional providers or features.
