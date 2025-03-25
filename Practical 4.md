## 📐 Modeling UML Use Case Diagrams

---

### ✅ Identifying Actors

| **Actor**       | **Description**                                                                 |
|------------------|----------------------------------------------------------------------------------|
| **User**         | Accesses weather forecasts and trend visualizations                             |
| **System Admin** | Manages model training, evaluation, deployment, and API configurations          |
| **Weather API**  | External system providing real-time weather data (e.g., OpenWeatherMap API)     |

---

### ✅ Identifying Use Cases

| **Use Case**           | **Description**                                                              |
|------------------------|-------------------------------------------------------------------------------|
| View Weather Forecast  | Users can check localized weather predictions                                 |
| View Weather Trends    | Users can visualize past weather data in graphs/charts                        |
| Train ML Model         | Admin can train models using new data                                         |
| Fetch Real-Time Data   | System fetches updated weather data from external APIs                        |
| Preprocess Data        | Clean and prepare raw weather datasets for model training                     |
| Evaluate Model         | Check performance metrics like RMSE, R² score                                 |
| Deploy System          | Make the forecasting system accessible via UI (web/app)                       |

---

### ✅ UML Use Case Diagram 
![WhatsApp Image 2025-03-25 at 15 28 33_016b3fe5](https://github.com/user-attachments/assets/537c37cd-e7d6-4fae-8ed2-810eb9631b12)

Aim
Modeling UML Use Case Diagrams and Capturing Use Case Scenarios

Introduction
A Use Case Diagram is a graphical representation that shows the interactions between users (actors) and the system. It helps in understanding the basic functionalities of a system and the roles played by different actors. This diagram is useful for developers, end-users, and domain experts to get a common understanding of the system.

A weather forecasting system provides users with weather predictions, real-time data, and weather trend visualizations. It involves different users, including general users who check forecasts and administrators who manage the system.

Objectives
After completing this experiment, you will be able to:
✅ Identify different actors and use cases from a given system
✅ Show the relationships between different use cases
✅ Draw a UML Use Case Diagram for the Weather Forecasting System

Theory
What is a Use Case Diagram?
A Use Case Diagram is a type of Unified Modeling Language (UML) diagram that shows how users interact with a system. It consists of:
1️⃣ Actors – Users who interact with the system
2️⃣ Use Cases – The functionalities the system provides
3️⃣ Relationships – How actors and use cases are connected

Actors in the Weather Forecasting System
There are two main types of actors:

1)Primary Actors (Directly interact with the system)

User: Checks weather forecasts and trends

2)System Administrator: Manages model training, evaluation, and deployment

Supporting Actors (Provide external data or support the system)

Weather API: Provides real-time weather data

Relationships in Use Case Diagram
Association: Shows direct interactions between actors and use cases.
Include: Represents a mandatory relationship (one use case depends on another).
Extend: Represents optional functionality (a use case is extended under certain conditions).



UML Use Case Diagram
Here is the UML Use Case Diagram for your Weather Forecasting System:
![image](https://github.com/user-attachments/assets/ff25e2f2-e536-4d2a-bbf8-044a6857eb8e)


Conclusion
A UML Use Case Diagram helps in understanding the interactions between users and the system. In this experiment, we identified the main actors, use cases, and their relationships in a Weather Forecasting System. This diagram provides a clear and structured way to design and develop the system.

