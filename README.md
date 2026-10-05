# AI-Based Smart EV Battery Health Monitoring and Predictive Maintenance System

An AI and IoT-based system for monitoring EV battery parameters, visualizing battery health data, and supporting predictive maintenance.

## Project Overview

This project uses an ESP32-based IoT system to collect battery and environmental parameters and transmit the data using MQTT.

The collected data can be visualized through a Node-RED dashboard and can be used as a foundation for AI-based battery health monitoring and predictive maintenance.

## Current Features

- Monitor ambient temperature
- Monitor humidity
- Monitor battery temperature
- Monitor battery voltage
- Monitor battery current
- Display real-time information on OLED
- MQTT-based real-time communication
- Node-RED dashboard visualization
- SQLite-based data storage
- ESP32-based hardware system
- Wokwi simulation support

## Hardware Components

- ESP32
- DHT22 temperature and humidity sensor
- NTC thermistor
- Voltage sensor
- Current sensor
- OLED display (SSD1306)
- Relay module
- Buzzer
- Green, Yellow and Red LEDs

## Software & Technologies

- Python
- ESP32
- PlatformIO
- Arduino
- MQTT
- Node-RED
- SQLite
- Wokwi
- AI / Machine Learning

## System Architecture

```text
EV Battery
    |
    v
Sensors
    |
    v
ESP32
    |
    v
MQTT Broker
    |
    v
Node-RED
    |
    +----> Dashboard
    |
    +----> SQLite Database
    |
    v
AI / ML Models
    |
    v
Battery Health Monitoring
    |
    v
Predictive Maintenance