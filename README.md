# Multi-Servo Sweep with Arduino

This project demonstrates how to control four servo motors simultaneously using an Arduino board. The servos perform a smooth, synchronized sweep from 0° to 180° and back.

## Features

- Controls 4 servo motors using the Servo library
- Smooth and continuous motion
- Easy to adapt for more or fewer servos

## Hardware Required

- 1 × Arduino board (Uno, Mega, etc.)
- 4 × Servo motors
- Jumper wires
- Breadboard (optional)
- External power supply for servos (recommended)

## Pin Configuration

| Servo  | Arduino Pin |
|--------|--------------|
| Servo 1 | D5 |
| Servo 2 | D3 |
| Servo 3 | D6 |
| Servo 4 | D9 |

> Ensure that all servo motors share a common ground with the Arduino. If you're using more than one or high-torque servos, use an external power supply.

## Setup Instructions

1. Connect each servo signal wire to the corresponding Arduino pin.
2. Connect VCC and GND of all servos (consider external power).
3. Open the Arduino IDE and paste the code into a new sketch.
4. Upload the sketch to your Arduino board.
5. All servos will start sweeping in sync.

## Dependencies

- [Servo Library](https://www.arduino.cc/reference/en/libraries/servo/) – Comes pre-installed with the Arduino IDE.


