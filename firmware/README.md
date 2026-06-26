# Firmware

This folder contains the firmware developed for the ESP32 devices used in the IoT Hydroponics Monitoring System.

## Devices

- ESP32 Sensor
  - Reads environmental and water level data.
  - Publishes telemetry to AWS IoT Core.

- ESP32 Actuator
  - Controls the irrigation pump.
  - Receives MQTT commands.
  - Supports OTA firmware updates.
  - Uses AWS IoT Device Shadow and Jobs.

## Technologies

- ESP32
- Arduino IDE
- MQTT
- AWS IoT Core
- OTA Firmware Updates
