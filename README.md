# Smart Automated Irrigation System using IoT

An ESP32-based, fully automated, solar-powered smart irrigation system that pumps water automatically based on soil moisture. It is designed for farmers with limited technical knowledge, so it needs no manual switches or mobile apps.

## Features
- Automatic water pumping based on soil moisture level
- Solar-powered, works without grid electricity
- OLED display to show soil moisture and pump status
- Crop-specific configuration using a push button
- 3-step audio-visual alerts using a buzzer and LEDs

## Components Used
- ESP32 microcontroller
- Soil moisture sensor
- OLED display
- Water pump
- Solar panel and battery
- Buzzer and LEDs
- Push button

## How It Works
1. The soil moisture sensor continuously reads the soil condition.
2. The ESP32 compares the reading with the threshold set for the selected crop.
3. When the soil is dry, the pump turns on automatically and stops once the soil is wet enough.
4. The OLED display shows the status, and the buzzer and LEDs give alerts.

## Technologies
- C++ (Arduino IDE)
- IoT, Embedded Systems

## Author
Thilagavathi K
BCA Graduate | MCA Pursuing
LinkedIn: https://www.linkedin.com/in/thilagavathi-k09
