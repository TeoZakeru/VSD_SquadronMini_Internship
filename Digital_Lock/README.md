**Introduction**

**Overview**

**Components required**
- VSD Squadron Mini
- 4x4 Matrix Keypad
- Servo Motor
- LCD Display
- Breadboard
- Jumper Wires

**Circuit Diagram**

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
