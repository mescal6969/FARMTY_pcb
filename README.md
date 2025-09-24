 Farmty – IoT Smart Farming System

Farmty is an IoT-based smart farming system designed to monitor and control farm parameters in real time.  
This repository contains the **KiCad PCB design**, **schematics**, and related files for the Farmty hardware.



##  Features
- ESP32-WROOM-32 microcontroller (with WiFi + Bluetooth)
- RS485 sensor support:
  - Soil moisture
  - pH sensor
  - EC (Electrical Conductivity)
  - Temperature
- BME280 (humidity, pressure, temperature sensor)
- Load cell integration (for smart weighing)
- OLED (SSD1306) display
- Stepper motor driver
- Relay control for automation
- PC817 optocoupler isolation
- USB-to-UART via CH340C
- Modular power supply and terminal blocks

---

##  Software
- **Firmware:** ESP-IDF / Arduino framework
- **Programming language:** Python (for data processing) + C++ (for microcontroller)
- **IoT Dashboard:** Cloud-ready, customizable with MQTT/HTTP

---

##  Hardware
- Designed in KiCad
- Includes hierarchical schematics for modularity
- PCB fabrication-ready


##  How to Use
1. Clone this repo:
   ```bash
   
