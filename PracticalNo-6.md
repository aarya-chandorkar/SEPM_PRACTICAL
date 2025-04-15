📘 Theory
✅ Structural and Behavioral Aspects
UML helps to model both the structure and behavior of a system.

Structural aspects deal with the static parts of the system, like classes, objects, and their relationships.

Behavioral aspects deal with the dynamic behavior, such as interactions and workflows within the system.

In a weather forecasting system, structure includes entities like User, WeatherService, and WeatherData, while behavior covers how data is fetched, processed, and displayed to users.

📦 Class Diagram
A Class Diagram is a fundamental UML diagram that represents the blueprint of the system. It shows:

Classes and their attributes and methods

Relationships between classes

For a weather forecasting system, the class diagram helps to define how components like data sources, forecast engines, and display modules interact.

🧩 Elements in Class Diagram
Each class diagram generally includes the following elements:

Class: Represented as a rectangle divided into three parts:

Class name

Attributes (variables)

Operations (methods)

Attributes: Properties that define the state of a class (e.g., temperature, location, humidity).

Methods: Functions that define the behavior (e.g., getWeather(), displayForecast()).

Visibility:

+ Public

- Private

# Protected

🔗 Class Relationships
Common types of relationships used in class diagrams:

Association: General connection (e.g., User uses WeatherService)

Aggregation: Weak ownership (e.g., WeatherService has multiple WeatherData)

Composition: Strong ownership (e.g., ForecastReport contains TemperatureDetails)

Inheritance (Generalization): One class inherits from another (e.g., CurrentWeather and WeeklyForecast inherit from WeatherData)

Dependency: One class depends on another for some functionality (e.g., WeatherService depends on APIClient)

⚙️ Composition
Composition is a form of strong association where one class is part of another and cannot exist independently.
In the weather forecasting project, for example:

ForecastReport composes WeatherMetrics (if the report is deleted, its metrics are too).

UserDashboard composes WeatherCard (each card depends on the dashboard view).

📚 Case Study: Weather Forecasting System
Main Classes:

User: Represents the person using the system

WeatherService: Handles API calls and data processing

WeatherData: Stores weather information like temperature, humidity, wind speed

ForecastReport: Displays the final weather report to the user

Location: Stores geographical data

Relationships:

User interacts with WeatherService

WeatherService depends on WeatherData

ForecastReport composes WeatherData and Location

WeatherService aggregates multiple ForecastReport

![image](https://github.com/user-attachments/assets/da3563e3-bf02-4b93-b18f-316e61f41e49)


