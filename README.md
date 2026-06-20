Smart Baby Room IoT Monitoring System
Overview

The Smart Baby Room IoT Monitoring System is a real-time mobile application designed to monitor and control environmental conditions in a baby room. The system integrates IoT sensors, ESP32, Firebase Realtime Database, and an Android application to provide live monitoring and remote control features.

This project aims to improve child safety, comfort, and parental awareness by enabling real-time access to environmental data such as temperature, humidity, light level, motion, and tilt detection.

Features
Real-time sensor data monitoring
Temperature tracking
Humidity monitoring
Motion / distance detection
Tilt detection for safety alerts
Light intensity monitoring
Remote lamp (LED) control via mobile app
Firebase Realtime Database integration
User-friendly Android dashboard interface
System Architecture

The system is composed of three main components:

1. Hardware Layer (IoT)
ESP32 microcontroller
Sensors (temperature, humidity, motion, light, tilt)
LED/Lamp control module
2. Cloud Layer
Firebase Realtime Database
Stores and synchronizes sensor data in real time
3. Application Layer
Android application (Java)
Displays live sensor data
Sends control commands (ON/OFF lamp)

How It Works
Sensors collect environmental data from the baby room
ESP32 sends data to Firebase in real time
Android app listens to Firebase updates
Data is displayed instantly on the dashboard
User can control the lamp remotely from the app

Technologies Used
Java (Android Development)
Firebase Realtime Database
ESP32 (IoT microcontroller)
Arduino IDE
XML (UI Design)

Android App Features
Live dashboard for all sensors
Real-time Firebase synchronization
Smart lamp ON/OFF control button
Clean and simple UI designed for usability

Project Goals
Enhance baby safety and comfort using IoT
Provide real-time environmental monitoring
Integrate hardware and mobile systems seamlessly
Demonstrate full-stack IoT development skills

