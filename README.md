# ESP32-HomeKit-Temperature-Humidity-Monitor
A smart temperature and humidity sensor based on ESP32, DHT22 and SSD1306 OLED, compatible with Apple HomeKit.

![Preview](Cover.jpg)
![Preview](HomeKit.jpg)

## Features
- Real-time temperature monitoring
- Real-time humidity monitoring
- Apple HomeKit integration
- OLED display
- WiFi support

## Hardware
- ESP32 DevKit
- DHT22
- SSD1306 OLED
- Jumper wires
- Breadboard

## Software
- Arduino IDE

## Libraries
- HomeSpan
- Adafruit SSD1306
- Adafruit GFX
- DHT sensor library

## Wiring

| ESP32 | Device |
|--------|--------|
| GPIO26 | DHT22 Data |
| GPIO32 | OLED SDA |
| GPIO33 | OLED SCL |
| 3.3V | VCC |
| GND | GND |
