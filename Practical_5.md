# **Practical No-05**  
## **Modeling Data Flow Diagram (DFD) & Control Flow Diagram (CFD)**  

### **Aim**  
To model **Data Flow Diagrams (DFD)** and **Control Flow Diagrams (CFD)** for a given system and analyze the flow of data and control through the system.  

---

## **Introduction**  
A **Data Flow Diagram (DFD)** is a graphical representation that shows how data moves through a system. It helps in understanding the **input, process, and output** of the system.  

A **Control Flow Diagram (CFD)** represents the **logical flow of control** within a system, showing how different processes and decisions are connected.  

In this practical, we will design **DFD and CFD** for a **Weather Forecasting System**.  

---

## **Objectives**  
After completing this experiment, you will be able to:  

- Identify **external entities** and **functionalities** of a system  
- Understand how **data flows** across different components  
- Represent **data movement** using **Data Flow Diagrams (DFD)**  
- Model the **control logic** of a system using **Control Flow Diagrams (CFD)**  

---

## **Theory**  

### **What is a Data Flow Diagram (DFD)?**  
A **DFD** shows the flow of data between different parts of a system. It represents how data is processed, stored, and transferred.  

---

### **Graphical Notations for DFD**  

| **Symbol**           | **Meaning**                                      |
|----------------------|--------------------------------------------------|
| 📦 **Process**       | Represents a function that processes data       |
| 🟡 **Data Store**    | Stores data for future use                      |
| 🔷 **External Entity** | Represents users or external systems interacting with the system |
| ➡ **Data Flow**      | Shows the movement of data                      |

---

### **Explanation of Symbols in DFD**  
1. **Process (Circle or Rectangle)** – Represents operations performed on data.  
2. **Data Store (Two parallel lines)** – Stores data within the system.  
3. **External Entity (Rectangle)** – Represents users or external systems.  
4. **Data Flow (Arrow)** – Shows data movement.  

---

### **Context Diagram & Leveling of DFD**  
- **Context Diagram (Level 0 DFD)**: Represents the **entire system as a single process** interacting with external entities.  
- **Level 1 DFD**: Breaks down the system into **sub-processes** to show detailed data flow.  

---

## **Case Study: Weather Forecasting System**  

### **Data Flow in Weather Forecasting System**  
1. **Users** enter location details.  
2. The system fetches **real-time weather data** from an **external API**.  
3. The data is **processed and stored** in the system database.  
4. The system **analyzes weather trends** and generates predictions.  
5. The **forecast is displayed** to users.  

---

## **Diagrams**  

### **1️⃣ Context Diagram (Level 0 DFD) for Weather Forecasting System**  
![Context Diagram](DFD_Context_Weather.png)  
![Screenshot 2025-03-25 153933](https://github.com/user-attachments/assets/e316c4e5-e1fc-4784-ae24-dc28dfca34bb)


### **2️⃣ Level 1 DFD for Weather Forecasting System**  
![Level 1 DFD](DFD_Level1_Weather.png)  
![image](https://github.com/user-attachments/assets/9a9ec145-a6ca-40e1-a320-b599df2f1bcf)


---

## **What is a Control Flow Diagram (CFD)?**  
A **CFD** shows the **logical flow of control** in a system, illustrating **decisions, loops, and execution order**. It helps in understanding how processes **trigger one another**.  

### **Control Flow in Weather Forecasting System**  
1. User enters location ➡ API fetches weather data  
2. If data is received ➡ Process & store it  
3. If no data is received ➡ Show an error message  
4. Predict & display weather trends  

---

## **Conclusion**  
In this experiment, we modeled the **DFD and CFD** for a **Weather Forecasting System**. The **DFD** shows how **data flows**, while the **CFD** represents the **logical execution order**. These diagrams help in designing **efficient and structured** software systems.  

---

