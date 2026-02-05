---
title: Module's Block Diagram
tags:
- tag1
- tag2
---

## Overview

The block diagram shows the basic electrical layout of the rover and how its main components are connected. Power is supplied by a 12 V battery or an external source through a barrel jack, then regulated down to 3.3 V to power the ESP32 and its supporting circuitry. The ESP32 acts as the main communication controller and provides standard digital interfaces such as UART, SPI, and I²C for connecting sensors and actuators developed by different teams. Sensor data is sent to the ESP32 for processing and wireless communication, while control signals are sent back to the subsystems using the same interfaces. Overall, the diagram outlines the available power and communication connections to support consistent integration across the rover system. 

## Block Diagram: Wireless Communication Subsystem
![Block Diagram: Wireless Communication Subsystem](DraftCommsCGE.png)

> Block Diagram: view as a PDF [here](WirelessCommunicationSubsystem.pdf)
