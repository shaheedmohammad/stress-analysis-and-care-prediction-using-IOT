# Stress Analysis and Care Prediction System for Online Workers Using IoT

## Project Overview

The Stress Analysis and Care Prediction System is an IoT-based real-time monitoring system developed to analyze and classify stress levels of online workers using physiological sensor data.

The system uses a GSR (Galvanic Skin Response) sensor connected to Arduino Uno for stress signal acquisition. ESP8266 NodeMCU is used for wireless data transmission to a web-based dashboard for real-time monitoring, visualization, and stress analysis.

The project classifies stress levels into Low, Medium, and High categories based on sensor response values and provides a live monitoring platform using MySQL and XAMPP.

This research work was presented at the 8th International Conference on Information Systems and Management Science (ISMS 2025), IIT Patna and published in Springer LNNS proceedings.

---

# Features

- Real-time stress monitoring
- GSR sensor-based physiological signal acquisition
- Arduino Uno and ESP8266 integration
- Wireless IoT communication
- Live web dashboard visualization
- MySQL database integration
- Stress classification system
- Real-time data storage and monitoring
- HTTP-based communication
- Embedded hardware-software integration

---

# Technologies Used

## Hardware
- Arduino Uno
- ESP8266 NodeMCU
- GSR Sensor
- Breadboard
- Jumper Wires

## Software
- Arduino IDE
- Embedded C
- PHP
- MySQL
- XAMPP Server
- HTML
- CSS
- JavaScript

## Communication Protocols
- UART
- HTTP

---

# System Architecture

The system consists of three major modules:

1. Sensor Data Acquisition Module  
   - GSR sensor collects physiological stress signals.
   - Arduino Uno processes analog sensor values.

2. Wireless Communication Module  
   - ESP8266 NodeMCU transmits sensor data to the server using HTTP requests.

3. Monitoring and Visualization Module  
   - Web dashboard stores and visualizes stress data using MySQL and XAMPP.

---

# Working Principle

1. The GSR sensor detects changes in skin conductivity related to stress levels.

2. Arduino Uno reads the sensor values and processes the physiological signal.

3. ESP8266 NodeMCU sends sensor data wirelessly to the local server.

4. PHP scripts receive and store the incoming data into the MySQL database.

5. The dashboard fetches real-time data and displays stress levels dynamically.

6. Stress values are categorized into:
   - Low Stress
   - Medium Stress
   - High Stress

---

# Stress Classification Logic

| Stress Level | Sensor Range |
|---|---|
| Low Stress | Less than 100 |
| Medium Stress | 100 – 700 |
| High Stress | Greater than 700 |

---

# Folder Structure

```text
Stress-Analysis-and-Care-Prediction-System-Using-IoT/
│
├── Source_Code/
├── Circuit_Diagram/
├── Images/
├── Output_Screenshots/
├── Documentation/
├── Components_Used/
└── README.md
```

---

# Components Used

1. Arduino Uno  
2. ESP8266 NodeMCU  
3. GSR Sensor  
4. Breadboard  
5. Jumper Wires  
6. USB Cable  
7. Laptop/System  
8. XAMPP Server  

---

# Circuit Diagram

Add the circuit diagram image inside:

```text
Circuit_Diagram/
```

Example:

```markdown
![Circuit Diagram](Circuit_Diagram/circuit_diagram.png)
```

---

# Dashboard Screenshots

## Web Dashboard

```markdown
![Dashboard](Output_Screenshots/dashboard_output.png)
```

## Serial Monitor Output

```markdown
![Serial Monitor](Output_Screenshots/serial_monitor.png)
```

## Hardware Setup

```markdown
![Hardware Setup](Images/hardware_setup.jpg)
```

---

# How to Run the Project

## Step 1 — Hardware Setup
- Connect GSR sensor to Arduino Uno.
- Connect ESP8266 NodeMCU for wireless communication.

## Step 2 — Upload Arduino Code
- Open Arduino IDE.
- Upload Arduino code to Arduino Uno.

## Step 3 — Configure ESP8266
- Update WiFi credentials.
- Upload ESP8266 code using Arduino IDE.

## Step 4 — Setup XAMPP Server
- Start Apache and MySQL services.
- Import database.sql into phpMyAdmin.

## Step 5 — Run Dashboard
- Place PHP files inside htdocs folder.
- Open localhost/project-folder in browser.

---

# Applications

- Stress monitoring for online workers
- Employee wellness systems
- Healthcare monitoring
- Remote health tracking
- IoT-based physiological monitoring systems

---

# Future Enhancements

- Cloud integration
- AI-based stress prediction
- Mobile application support
- Real-time alert notifications
- Multi-sensor integration
- Data analytics and reporting

---

# Research Publication

Presented at:
- 8th International Conference on Information Systems and Management Science (ISMS 2025), IIT Patna

Published in:
- Springer Lecture Notes in Networks and Systems (LNNS)

---

# Author

Mohammad Shaheed

GitHub: https://github.com/shaheedmohammad

LinkedIn: https://linkedin.com/in/shaheed-mohammad-9859b3249
