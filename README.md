# Wireless Sensor Network-Based Data Logger with Data Security

## Project Overview
This project implements a wireless sensor network for real-time data logging in data centers with basic XOR encryption for secure communication between nodes.

## Problem Statement
Data centers require continuous monitoring of environmental parameters such as temperature, humidity, air quality, voltage, and current. Without secure and reliable logging, these values can be tampered with or lost.

## Features
- Multiple Arduino-based sensor nodes
- Sensors: DHT22, MQ-135, ZMPT101B, ACS712
- Wireless communication via nRF24L01
- XOR encryption for basic security
- Data logging on a central receiver (PC storage)

## Hardware Components
- Arduino Uno
- DHT22
- MQ-135
- ZMPT101B
- ACS712
- nRF24L01
- USB cable

## Software
- Arduino IDE
- Python 3.x (for PC receiver)
- PySerial library

## How to Run
1. Upload transmitter code to Arduino with sensors.
2. Upload receiver code to Arduino connected to PC.
3. Run Python receiver script to log data.
4. Observe logged data in CSV format.
