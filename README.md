# Assignment4
In this Weather App, we use the OpenWeatherMap API to fetch the current weather data. Here is an explanation of the code:

In the main method, we create an instance of WeatherApp and call the createGUI method.

The createGUI method creates the GUI components and adds them to the frame. It includes a search text field, search button, and weather data labels.

The searchTextField allows the user to input a location to fetch the weather data for.

The searchButton retrieves the weather data by calling the WeatherApp.getWeatherData method with the location provided by the user.

The WeatherApp.getWeatherData method is a utility method that takes the location as a parameter and uses the OpenWeatherMap API to fetch the weather data for that location. It then returns a map containing the weather data.

In the actionPerformed method of the searchButton, the weather data is fetched using the WeatherApp.getWeatherData method. The weather data map is then used to update the text of the various labels that display the weather data.

The loadImage method is used to load the images used in the GUI components. It takes the file path of the image as a parameter and reads the image from the path using the ImageIO.read method.

Please note that the code uses a separate WeatherApp class for fetching the weather data, which is not included in this response. The WeatherApp class should contain the logic for interacting with the OpenWeatherMap API.

In summary, this Weather App provides a user-friendly interface for fetching and displaying the current weather data for a specified location. It utilizes the OpenWeatherMap API to retrieve the weather data and presents it in a visually appealing manner.



