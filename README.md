Here is a **clean GitHub README.md** you can directly paste into your repository for the **Radar / Smart Detection System project** based on your uploaded document.

# Arduino Radar System using Ultrasonic Sensor

## Project Overview

This project implements an **Arduino-based Radar System** that detects objects using an **ultrasonic sensor and a servo motor**. The servo motor rotates from **0° to 180°**, scanning the surroundings while the ultrasonic sensor measures the distance of nearby objects.

The detected distance and angle are displayed on an **LCD screen**, and a **buzzer and LEDs** alert when an object is detected within a specified range. 

## Features

* 180° radar scanning using a servo motor
* Real-time distance measurement using ultrasonic sensor
* LCD display for distance and angle
* LED indicators for object detection
* Buzzer alert system
* Automatic scanning and detection

## Components Required

* Arduino Uno
* Ultrasonic Sensor (HC-SR04)
* Servo Motor
* LCD Display (16x2)
* Buzzer
* LEDs (2)
* Jumper Wires
* Breadboard
## Technologies Used

* Arduino IDE
* C/C++ Programming
* Embedded Systems
* Sensor-based Object Detection
## System Working

### 1. Servo Motor Scanning

The servo motor rotates continuously between **0° and 180°**, scanning the surrounding environment.

### 2. Ultrasonic Distance Measurement

The ultrasonic sensor sends a signal and waits for the echo to return. The distance is calculated using the speed of sound. 

### Distance Formula

Distance is calculated using:

Distance = (Duration × Speed of Sound) / 2

Where:

* Speed of sound = **0.034 cm/µs**
* Division by 2 accounts for the signal traveling to the object and back. 

## Display Output

The LCD shows:

* **Distance from object**
* **Current servo angle**

Example:

Distance: 15 cm
Angle: 90 deg

## Alert System

The system provides alerts based on object distance:

| Distance | Action                       |
| -------- | ---------------------------- |
| ≤ 10 cm  | Buzzer ON (1000 Hz), LED2 ON |
| 10–20 cm | Buzzer ON (1500 Hz), LED1 ON |
| > 20 cm  | No alert                     |

This helps detect obstacles within the radar scanning range. 

## Workflow

Servo Motor Rotates
        ↓
Ultrasonic Sensor Sends Pulse
        ↓
Echo Signal Received
        ↓
Distance Calculated
        ↓
Distance Displayed on LCD
        ↓
LED & Buzzer Alert if Object Detected

## Applications

* Obstacle detection systems
* Security monitoring systems
* Robotics navigation
* Smart parking detection
* Surveillance radar prototypes

## Future Enhancements

* Add graphical radar display using Processing
* Integrate with IoT for remote monitoring
* Mobile app notifications
* AI-based object classification


## Conclusion

This project demonstrates a **simple radar-based object detection system using Arduino**. By combining a **servo motor, ultrasonic sensor, LCD display, and alert system**, it creates an efficient and cost-effective solution for real-time obstacle detection. 


