# ESP32 CAN Bus LED Control

An ESP32-based LED control project demonstrating CAN bus communication between two ESP32 microcontrollers.

## Project Overview

This project demonstrates communication between two ESP32 microcontrollers using the Controller Area Network (CAN) protocol.

One ESP32 acts as the transmitter and sends LED control commands over the CAN bus. The second ESP32 receives the CAN messages and controls the LED based on the received command.

## System Architecture

- ESP32 #1 – CAN Transmitter
- ESP32 #2 – CAN Receiver
- CAN Transceiver – CAN bus interface
- LED – Output device

## Communication

The transmitter ESP32 sends control data through the CAN bus. The receiver ESP32 interprets the received CAN message and switches the LED ON or OFF accordingly.

## Technologies Used

- ESP32
- CAN Bus Communication
- CAN Transceiver
- Arduino IDE
- Embedded C/C++

## Key Features

- Two-node ESP32 CAN communication
- CAN message transmission and reception
- LED ON/OFF control through CAN commands
- Basic embedded communication architecture

## Project Files

- Project Working video

## Author

CHARAN K
