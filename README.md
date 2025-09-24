 Farmty – IoT Smart Farming System

Farmty is an IoT-based smart farming system designed to monitor and control farm parameters in real time.  
This repository contains the KiCad PCB design , schematics , and related files for the Farmty hardware.



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
   https://github.com/mescal6969/FARMTY_pcb
2. Open the project in KiCad.
3. Modify schematics/PCB as needed.
4. Generate Gerber files for manufacturing.
5.Flash ESP32 with firmware to connect to IoT dashboard.

## IoT Integration

Farmty uses the **ESP32 WiFi module** to connect to the cloud.  
It can be integrated with:  
- **Blynk**  
- **ThingsBoard**  
- **Node-RED**  
- **MQTT brokers** (Mosquitto, HiveMQ)  

## License

This project is open-source under the **MIT License**.  
Feel free to use, modify, and share with attribution.

 Author
Allan Ng’ang’a Gacheru
BSc Mechatronics Engineering
Dedan Kimathi University of Technology
