# Weather App GUI  

## Introduction

The Weather App is a Java-based application that provides users with real-time weather information for a specified location. It fetches weather data from an external API and displays it in a graphical user interface (GUI). Users can enter a location, and the app retrieves and presents weather details, including temperature, weather condition, humidity, and wind speed. This documentation outlines the project's architecture, technologies used, and the functionality of each class within the application.  

![WeatherApp 2024-03-14 17-19-10](https://github.com/gerzson-pszota/WeatherApp/assets/138587246/da256b39-998a-4b92-96b3-247e4e7c961e)

## Technologies Used

The Weather App utilizes the following technologies and libraries:
* Java 17
* JSON Simple - Used to parse and read through JSON data
* HTTPURLConnection: Java's built-in library for making HTTP requests to fetch data from external APIs.

## Class Summaries

* AppLauncher  
The AppLauncher class serves as the entry point for the Weather App. It initializes the GUI and displays the main application window.

* WeatherAppGui  
The WeatherAppGui class represents the graphical user interface (GUI) of the Weather App. It is responsible for displaying weather information for a specified location.  
This class handles the layout and display of GUI components, including text fields, labels, buttons, and images. It also implements the user interface for entering a location and updating the weather information based on user input.

* WeatherApp  
The WeatherApp class contains the backend logic for fetching weather data from an external API. It retrieves geographic coordinates for a location, fetches weather data for that location, and provides methods to convert weather codes.  
This class encapsulates the core functionality of the Weather App. It includes methods to fetch weather data and location coordinates, convert weather codes into readable weather conditions, and manage API requests. This class acts as the bridge between the GUI and the external weather data source, ensuring that weather information is retrieved and displayed accurately.
