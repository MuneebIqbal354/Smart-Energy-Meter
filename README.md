# Smart Energy Meter

Welcome to the **Smart Energy Meter** project! This project implements a real-time energy monitoring solution capable of measuring voltage, current, and power consumption. 

By interfacing an **Arduino** with an **ESP8266 Wi-Fi module**, the system collects data from **ACS712** and **ZMPT101B** sensors and transmits it to the **ThingSpeak** cloud for storage and visualization. Users can view energy statistics via a web dashboard or a local LCD screen. The setup includes a test load (bulb) to demonstrate the system's accuracy and response time.

## Features

* **Instantaneous Monitoring:** Captures live data for voltage, current, and total power usage.
* **Cloud Connectivity:** Utilizes the ESP8266 module to bridge local sensor data with the web.
* **Remote Visualization:** Leverages ThingSpeak to create an accessible, graphical dashboard of energy trends.
* **On-Site Display:** Features a LiquidCrystal LCD for immediate, physical data readout.
* **Load Testing:** Includes a controlled bulb setup to demonstrate and verify energy measurements.

## Prerequisites

To replicate this project, ensure you have the following components and software ready:

### Hardware Requirements

- **Arduino**: Microcontroller for data acquisition.
- **ESP8266**: Wi-Fi module for wireless communication.
- **ThingSpeak**: Cloud platform for data storage and visualization.
- **ACS712**: Current sensor for measuring current.
- **ZMPT101B**: Voltage sensor for measuring voltage.
- **LiquidCrystal LCD**: Display module for showing real-time data.
- **Bulb**: Demonstrative load to measure energy consumption.

### Software Environment

* **Arduino IDE** (Integrated Development Environment)
* **Active ThingSpeak Account** (for cloud dashboard setup)

  
![image](https://github.com/Magxtron/Smart_Energy_Meter/assets/157964593/90c55395-e729-4fa4-ae6f-824bf3b29b3d)

<img width="1023" height="1091" alt="341496359-62e52bf0-6ed0-44b8-b98b-1ac521e158d8" src="https://github.com/user-attachments/assets/b373ea17-6545-426d-8502-78f16736d61c" />

