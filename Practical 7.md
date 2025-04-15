Practical 7
Modeling Sequence Diagrams
Sequence Diagram
A sequence diagram is a type of UML diagram used to represent the interaction between objects in a time sequence. It shows how objects communicate with each other using messages and how these messages are ordered. It is mainly used in system design to understand and visualize the logic of complex functionalities.

In a weather forecasting system, a sequence diagram can help to model the process of a user requesting weather information and the system responding by fetching data from APIs and displaying the results.

Elements in Sequence Diagram
Object:
An instance of a class that interacts in the scenario. For example: User, WeatherApp, WeatherAPI, Database.

Life-line Bar:
A vertical dashed line that represents the life span of the object during the interaction. It starts when the object is active and ends when the object is no longer participating.

Messages:
Communication between objects, represented by arrows. Messages can be of two types:

Synchronous Message:
The caller waits for the response before continuing.
Example: WeatherApp → WeatherAPI: fetchWeatherData()

Asynchronous Message:
The caller doesn’t wait for the response.
Example: WeatherAPI → Logger: logRequest()

Example Sequence Diagram (for Weather Forecasting System)
Participants:

User

WeatherApp Interface

WeatherAPI Service

Database

Flow:

User enters a city name and clicks "Get Weather".

WeatherApp sends a synchronous request to WeatherAPI: getWeather(cityName)

WeatherAPI checks the cache/database for existing data.

If not found, WeatherAPI fetches data from external weather service API.

WeatherAPI sends the weather data back to WeatherApp.

WeatherApp displays the data to the user.

![image](https://github.com/user-attachments/assets/60c483f2-77e3-461c-9c3e-4e9e3afe6af1)
