# Servo Motor Angle Control in Automated and Manual Tollgate Control Systems

## Project Overview
An Arduino Uno-based tollgate control system designed to demonstrate automated and manual barrier operation using IR sensors and a servo motor.

## Components Used
- Arduino Uno
- IR Sensors (Entry and Exit)
- SG90 Servo Motor
- Breadboard
- Jumper Wires
- Power Supply

## Working Principle
1. The Entry IR sensor detects an approaching vehicle.
2. Arduino Uno processes the sensor signal and controls the servo motor.
3. The servo rotates from 0° to 180° to open the gate.
4. The Exit IR sensor detects the vehicle after it passes.
5. The servo returns to 0° to close the gate.
6. Manual operation can also be performed through the manual control mechanism.

## Servo Motor Angle Control

| Angle | Gate Status |
|---|---|
| 0° | Closed |
| 180° | Open |

## Hardware Demonestration Video

[Hardware Demonstration Video](https://github.com/suhasiniperabattula24-stack/Servo-Motor-Angle-Control-in-Automated-and-Manual-Tollgate-Control-Systems/commit/b5748a93631a17ad89b1093dbe0ffc6f88f75618#diff-fa1ecc4431263a4c24692b12dd2c91d7b6ae016c8eda1fb7c5cf1876765df910)

## Key Features
- Automated vehicle detection
- Manual and automatic gate operation
- Servo motor angle control
- Simple and cost-effective design

## Future Enhancements
- IoT-based remote monitoring
- Automatic toll payment integration
- Vehicle number plate recognition

## Technologies Used
Arduino Uno | Embedded C | IR Sensors | Servo Motor

## Conclusion
This project demonstrates automated and manual tollgate barrier control using Arduino Uno, IR sensors, and a servo motor, helping improve vehicle movement and reduce manual effort.
