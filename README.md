# Matilda Restoration

## Description

A restoration of a derelict emergency response robot. This was accomplished as part of an undergraduate thesis course for Toronto Metropolitan University's N-CART division.

### Hardware Components

* 1x DROK Buck converter
* 1x Raspberry Pi
* 1x LCD I2C Display
* 1x ESP32 Microcontroller
* 1x ESP32 Servo Driver Expansion Board
* 2x USB Webcams
* 1x Sabertooth Motor Driver
* 2x 5200 mAh 3-cell LiPo batteries
* 1x 12V 3000mAh Lithium-Ion battery bank

### Software Components

* RPi-hosted NodeJS Web App as the orchestration server for starting WebRTC connections
* RPi-hosted Python script to connect and act as the robot client
* Operator client webpage to connect and see robot POV
* Operator client Python script to send gamepad input to chassis and arm ESP32s
* ESP32 code for controlling chassis from operator input
* ESP32 code for controlling servo arm from operator input

## Project Demonstration Video - YouTube 

[<img src="https://img.youtube.com/vi/3SzwsqPXLCs/hqdefault.jpg" width="600" height="300"
/>](https://www.youtube.com/embed/3SzwsqPXLCs)
