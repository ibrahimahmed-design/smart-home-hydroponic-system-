# Smart Home Hydroponic System

This repository contains the design and documentation for a **Smart Home Hydroponic System**, developed as part of the Hack Club - Highway to Undercity hackathon.

## Overview

The system is designed to automate home-based hydroponic farming using sensors, microcontrollers, and real-time monitoring via a mobile app. It includes:

- ESP32 microcontrollers
- Water level, pH, temperature, and EC sensors
- Water and nutrient pumps
- Firebase integration
- A mobile Smart Grow App

---

## System Architecture

### Diagram 1

![Hydroponic Diagram 1](images/hydroponic-diagram-1.jpg)

This diagram illustrates how ESP32 boards are connected to sensors, and how the data flows through Firebase to the Smart Grow App. It also shows the layout of water reservoirs, pumps, and sensor placements.

---

### Diagram 2

![Hydroponic Diagram 2](images/hydroponic-diagram-2.jpg)

This diagram provides a simplified view of the water circulation and nutrient delivery system used in the hydroponic setup.

---

## How it Works

1. Sensors monitor the plant environment (pH, water level, temperature, EC).
2. Data is sent via ESP32 to Firebase in real-time.
3. The Smart Grow App displays this data and allows manual or automatic control.
4. The water and nutrient pumps are activated based on sensor readings and thresholds.
5. The system helps optimize plant growth while minimizing water and nutrient waste.

---

## Goals

- Provide an affordable, smart agriculture solution for homes.
- Promote sustainable food production in urban environments.
- Use IoT and automation to reduce user intervention.

---

## Project Status

- [x] System Design Completed
- [ ] Tinkercad 3D Model In Progress
- [ ] Hardware Assembly
- [ ] App Interface Design
- [ ] Final Testing and Presentation

---

## License

This project is licensed under the MIT License. Feel free to use and modify it with attribution.