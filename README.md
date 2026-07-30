# Edge-Intelligent Condition Monitoring System

An Edge AI-based Predictive Maintenance system designed for industrial rotating machinery using TinyML and Industrial IoT.

> **Status:** 🚧 Ongoing Final Year Project (Phase 1 Completed | Phase 2 In Progress)

---

## Overview

This project performs real-time machine health monitoring using multiple sensors and Edge AI running on an ESP32 microcontroller.

The system acquires:

- Vibration
- Motor Current
- Temperature

and performs local signal processing and TinyML inference to detect machine faults without depending on cloud computing.

---

## Features

- Edge AI (TinyML)
- ESP32-based Embedded System
- Real-time Fault Detection
- FFT Signal Processing
- Multi-Sensor Data Fusion
- MQTT Communication
- Industrial IoT Dashboard
- Predictive Maintenance
- Remaining Useful Life (RUL) Estimation (Planned)

---

## Hardware

- ESP32-WROOM-32
- MPU6050 vibration sensor
-  PZEM-004T AC Current Sensor
- DS18B20 Temperature Sensor
- 3-Phase Induction Motor

---

## Software

- Arduino IDE
- Edge Impulse
- Embedded C/C++
- FFT
- TinyML
- MQTT
- Industrial IoT

---

## System Workflow

Sensors
↓

ESP32

↓

FFT Signal Processing

↓

TinyML Model

↓

Fault Classification

↓

MQTT

↓

IoT Dashboard

---

## Machine Faults

- Rotor Imbalance
- Thermal Faults

---

## Project Goals

- Reduce maintenance cost
- Reduce unplanned downtime
- Real-time monitoring
- Edge intelligence
- Improve industrial reliability

---

## Repository Structure

```
Edge-Intelligent-Condition-Monitoring-System/
│
├── README.md
├── Project_Report/
│   └── Phase_1_Report.pdf
│
├── Images/
│
├── Hardware/
│
├── Firmware/
│
├── TinyML_Model/
│
├── Documentation/
│
└── LICENSE
```

---

## Future Work

- CNN-LSTM RUL Prediction
- OPC UA Integration
- Edge Dashboard
- Factory Validation
- Continuous TinyML Learning

---

## Author

Lakshman Shrestha

Final Year B.E. Mechatronics Engineering

Mangalore Institute of Technology & Engineering
