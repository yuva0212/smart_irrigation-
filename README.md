Smart Irrigation System
This Smart Irrigation System is designed to help optimize water usage for irrigation by monitoring soil moisture, temperature, and humidity levels. The system uses an ESP32 microcontroller to collect sensor data and control a motor for irrigation.

Table of Contents
Introduction
Features
Hardware Requirements
Software Requirements
Setup Instructions
Running the Server
ESP32 Code
API Endpoints
Contributing
License
Introduction
The Smart Irrigation System uses an ESP32 microcontroller to monitor soil moisture, temperature, and humidity. Based on the sensor readings, the system decides whether to activate a water pump for irrigation. The sensor data is sent to a server, where it can be monitored and analyzed.

Features
Real-time monitoring of soil moisture, temperature, and humidity
Automated irrigation based on sensor data
Data logging and analysis
Predictive water requirement calculations
Hardware Requirements
ESP32 microcontroller
DHT11 sensor (for temperature and humidity)
Soil moisture sensor
5V water pump
Relay module
Connecting wires
Breadboard or PCB
Software Requirements
Arduino IDE
Node.js and npm
