## Introduction

Introducing Secure Saiyan, our digital lock system. This innovative security solution allows users to input their unique passcode via the keypad, which is processed by the VSD Squadron Mini to verify entry authorization. Upon correct code entry, the VSD Squadron Mini activates the servo motor, rotating the door handle to unlock the door. This system ensures not only security but also offers ease of use, making it suitable for various settings.

## Overview

The Secure Saiyan provides a modern, secure method of entry, integrating technology to improve traditional locking mechanisms. The primary components include a 4x4 matrix keypad for user input, a VSD Squadron Mini for processing and verification, a servo motor to operate the door handle and an LCD screen to display the Status. When a user enters their passcode on the keypad, the VSD Squadron Mini validates the code against stored authorized code. If the passcode is correct, the VSD Squadron Mini triggers the servo motor to rotate the door handle, while the LCD displays UNLOCKED, thereby unlocking the door, else the LCD displays LOCKED, with the servo motor untriggered. This combination of electronic and mechanical elements ensures reliability and user-friendliness.

## Components required
- VSD Squadron Mini
- 4x4 Matrix Keypad
- Servo Motor
- LCD Display
- Breadboard
- Jumper Wires

## Circuit Diagram

![Circuit Diagram](images/Circuit.png)

## Pin Connections

### Matrix Keypad Connections
- Wire 8 -> PD7
- Wire 7 -> PD6
- Wire 6 -> PD5
- Wire 5 -> PD4
- Wire 4 -> PD3
- Wire 3 -> PD2
- Wire 2 -> PD1

### LCD Display with I2C Interface Connections:
- GND (1) -> VSD Squadron Mini GND
- VCC (2) -> VSD Squadron Mini 5V
- SDA (3) -> PC1 (SDA Pin)
- SCL (4) -> PC2 (SCL Pin)

### Servo Motor Connections:
- Servo 5V -> VSD Squadron Mini 5V
- Servo GND -> VSD Squadron Mini GND
- Servo Input -> PC4
