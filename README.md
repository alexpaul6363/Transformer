# Transformer Health Monitoring System (IoT-based)

This project monitors key parameters of a power transformer such as temperature, current, oil level, and humidity using ESP32 and sends the data to ThingSpeak for remote monitoring. This helps in predictive maintenance of distribution transformers.

## 📌 Features
- Real-time sensor data collection (Temp, Current, Oil Level)
- Data visualization on LCD
- Remote monitoring via ThingSpeak IoT dashboard
- ESP32-based firmware written in Embedded C

## 🛠️ Components Used
- ESP32 microcontroller
- DHT11 sensor (Temperature and Humidity)
- SCT-013 CT Sensor (Current)
- Float switch / Oil level sensor
- 16x2 LCD with I2C
- ThingSpeak Cloud (for IoT data logging)

## 📷 System Overview

![Wiring Diagram](Schematics/wiring_diagram.png)

## 🔧 Setup Instructions
1. Open the `Code/transformer_monitor.ino` file in Arduino IDE.
2. Install the required libraries:  
   - `DHT sensor library`
   - `LiquidCrystal_I2C`
   - `ThingSpeak`
3. Replace Wi-Fi credentials and ThingSpeak API key in the code.
4. Connect the hardware as shown in the diagram.
5. Upload the code to ESP32.
6. Visit your ThingSpeak channel to monitor real-time data.

## 💡 Live Dashboard Example
👉 _[Insert your ThingSpeak link here once set up]_

## 🔗 Related Technologies
- Embedded C / Arduino IDE
- IoT and Cloud Communication
- Electrical transformer health monitoring

## 🪪 License
MIT License
