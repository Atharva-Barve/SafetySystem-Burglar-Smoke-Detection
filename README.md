# Safety System: Burglar & Smoke Detection

## Overview
This project is a **Burglar & Smoke Detection System** that alerts users through buzzers, LEDs, and a LabVIEW SCADA screen when an intrusion or smoke is detected. The system enhances security by providing real-time alerts for unauthorized access and potential fire hazards.

## Features
- **Intrusion Detection:** Uses IR sensors to detect unauthorized movement.
- **Smoke Detection:** Employs a smoke sensor to identify potential fire threats.
- **Multi-Alert System:** Notifies the user through:
  - **Buzzer & LED** for immediate local alerts.
  - **LabVIEW SCADA Interface** for real-time monitoring from distant location(eg: a control or surveillance room).
- **Wi-Fi Connectivity:** Capable of sending alerts over TCP using an ESP8266.

## Hardware Used
- **ESP8266, Arduino** (Microcontrollers)
- **IR Sensor** (For burglar detection)
- **MQ-2 Smoke Sensor** (For smoke detection)
- **Buzzer & LEDs** (For local alerts)

## Software & Tools
- **LabVIEW SCADA** (For visualization & remote alerts)
- **Arduino IDE** (For programming ESP8266)

## Working Principle
1. **Intrusion Detection:** When motion is detected, the ESP8266 triggers the buzzer and LED and alerts about the event in LabVIEW.
2. **Smoke Detection:** If smoke levels exceed a threshold, an alarm is triggered, and a warning LED is activated in LabVIEW.
3. **Remote Monitoring:** The system can send real-time alerts over Wi-Fi to a LabVIEW SCADA dashboard.

## Setup & Installation
1. **Connect Sensors & Components:** For this project, I interfaced ESP8266 for intrusion detection & arduino for smoke, however only ESP is also enough.
2. **Upload Code:** Flash the ESP8266 & Arduino with the Arduino sketches provided.
3. **LabVIEW Configuration:** Open the provided LabVIEW VIs.
4. **Test the System:** Simulate motion and smoke to verify functionality.

## Project Files
- **LabVIEW VI's:**
- **ESP8266 code**

Arduino is to be flashed with LIFA_Base code available in LIFA package from VIPM
---
Let me know if you need any modifications or additional details! 🚀

