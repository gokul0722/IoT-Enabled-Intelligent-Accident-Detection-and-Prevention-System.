IoT-Enabled Intelligent Accident Detection and Prevention System

GitHub-ready mini project.

## Features
- ESP32 based accident detection
- Vibration/impact sensor alert
- MQ sensor alcohol/smoke alert
- Buzzer and LED warning
- Node.js backend API
- Web dashboard for incident logs

## Components
- ESP32
- SW-420 vibration sensor
- MQ-3 / MQ-2 sensor
- Buzzer
- LED
- Jumper wires

## Run Backend
```bash
cd backend
npm install
npm start
```

## Run Dashboard
Open `web/index.html` in browser.

## Upload ESP32 Code
Open `hardware/esp32_accident_system.ino` in Arduino IDE and change WiFi name, password, and server URL.
