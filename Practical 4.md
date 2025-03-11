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

### ✅ UML Use Case Diagram (Text View)

            +--------------------+
            |       User         |
            +--------+-----------+
                     |
   +----------------+-----------------+
   |                                  |
   v                                  v
            +---------------------------+
            |   System Administrator    |
            +------------+--------------+
                         |
   +----------------+--------------------+
   |                                     |
   v                                     v
            +----------------------------+
            |    Weather Data API        |
            +------------+---------------+
                         |
                         v
            +----------------------------+
            |  Fetch Real-Time Data      |
            +----------------------------+
