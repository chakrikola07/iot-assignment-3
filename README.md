# CIS600 IoT Assignment 3 – Virtual Sensor System

This project is part of the Spring 2025 CIS600 IoT course. It implements a virtual environmental station that simulates temperature, humidity, and CO2 sensor data and publishes the data to ThingSpeak using the HTTP API.

## 📡 System Overview

- **Language:** Python
- **Sensors:** 
  - Temperature (-50 to 50°C)
  - Humidity (0 to 100%)
  - CO₂ (300 to 2000 ppm)
- **Cloud Backend:** ThingSpeak
- **Protocol:** HTTP REST (alternative to MQTT)

## 🚀 How to Run

1. Clone the repo or download the code.
2. Replace `"YOUR_WRITE_API_KEY"` in `virtual_sensor_http.py` with your ThingSpeak Write API Key.
3. Install required library:
   ```bash
   pip install requests
