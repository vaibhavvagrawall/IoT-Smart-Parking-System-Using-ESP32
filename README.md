# IoT-Based Smart Parking System

This project is an IoT-based smart parking system using ESP32, ultrasonic sensors, a servo motor, and ThingSpeak for real-time data communication. It enables monitoring of parking availability and controls a gate servo motor based on parking status. The system also displays the available slots on an LCD screen and sends data to ThingSpeak for remote monitoring.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)

## Introduction
The IoT-based smart parking system improves the efficiency of managing parking lots by automating the parking entry and exit process. The system utilizes ultrasonic sensors to detect vehicles and controls a servo motor to open and close a gate. Real-time parking slot availability is displayed on an LCD screen, and data is pushed to ThingSpeak for remote access via a mobile app.

## Features
- Real-time parking slot availability monitoring.
- Automatic gate control based on sensor input.
- Live display of available parking slots using an LCD.
- Sends data to ThingSpeak for remote monitoring.
- Alerts when parking is full.

## Hardware Requirements
- ESP32 Microcontroller
- Ultrasonic Sensors (HC-SR04)
- Servo Motor (SG90)
- LiquidCrystal I2C 16x2 LCD Display
- Jumper Wires
- Breadboard
- USB Cable
- Power Supply

## Software Requirements
- Arduino IDE (with ESP32 board support)
- ThingSpeak API Key
- WiFi connection
