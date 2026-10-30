# Smart Solar Wireless EV Charging Station with IoT Monitoring

## 📌 Overview
This repository contains the complete hardware prototype, firmware, and IoT dashboard for a **Smart Solar Wireless EV Charging Station**. Powered by renewable solar energy, the system uses an ESP32 microcontroller to monitor voltage and current, detect vehicle presence, and transmit real-time telemetry to a cloud dashboard. 

The project aims to demonstrate the feasibility of off-grid, wireless electric vehicle charging with remote monitoring capabilities.

## ✨ Key Features
*   **Solar-Powered:** Utilizes solar energy for sustainable EV charging.
*   **Wireless Power Transfer:** Inductive charging module for cable-free EV battery charging.
*   **Vehicle Detection:** IR sensor automatically detects the presence of an EV.
*   **Real-Time Monitoring:** Voltage and current sensors track power consumption.
*   **IoT Dashboard:** Live telemetry displayed on the Blynk IoT platform via ESP32 Wi-Fi.
*   **Safety Controls:** Relay module for safe power switching.

## 🛠️ Hardware & Technologies
*   **Microcontroller:** ESP32 (Wi-Fi enabled)
*   **Sensors:** IR Sensor, LDR (Light Dependent Resistor), Voltage Sensor, Current Sensor
*   **Actuators:** Relay Module, Wireless Charging Coil
*   **Software:** Arduino IDE (C++), Blynk IoT Platform

📊 Results & Visuals
1. Physical Hardware Prototype
The complete hardware setup featuring the ESP32, solar panel, wireless charging coils, and sensor array.

https://hardware/hardware_prototype_1.jpg

https://hardware/hardware_prototype_2.jpg

2. IoT Dashboard (Blynk)
Real-time monitoring of voltage, current, and charging status displayed on the Blynk mobile app.

https://iot_dashboard/blynk_dashboard_1.png

https://iot_dashboard/blynk_dashboard_2.jpg

🚀 Future Scope

Integration of a battery management system (BMS) for safe charging.

Addition of RFID authentication for user access control.

Solar tracking system to maximize energy harvesting.

Integration with a billing system using cloud databases.

📄 Documentation

The complete project report with circuit diagrams, block diagrams, and code explanation can be found here: Project_Report.pdf

👨‍💻 Author

Kothakonda Subhash
Department of Electronics and Communication Engineering

## 📂 Repository Structure
```text
├── Code/                   # ESP32 Firmware
│   └── esp32_main.ino
├── Hardware/               # Physical Prototype Photos
│   ├── hardware_prototype_1.jpg
│   └── hardware_prototype_2.jpg
├── IoT_Dashboard/          # Blynk App Screenshots
│   ├── blynk_dashboard_1.png
│   └── blynk_dashboard_2.jpg
└── Docs/                   # Full Project Report
    └── Project_Report.pdf
