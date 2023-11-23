# Gesture Controlled Robot using Arduino

## Overview
This project involves the development of a Gesture Controlled Robot using Arduino technology. The system is divided into two main parts: the transmitter and the receiver.

### Transmitter
The transmitter circuit is mounted on a glove worn by the user, featuring an Arduino Nano board, a MEMS (Accelerometer) sensor, ZigBee transmitter, and power supply connections. The MEMS sensor senses hand motion in three axes and sends the data to the Arduino Nano. The Arduino Nano interprets predefined actions and transmits commands via ZigBee to the receiver.

### Receiver
The receiver circuit is placed on the robotic car and includes an Arduino Uno board. It receives commands from the transmitter, processes the data, and sends control signals to the motor driver circuit. The motor driver circuit, based on the received commands, powers the DC gear motors to move the robot in four directions based on hand gestures.

## Hardware Requirements
1. MEMS Technology (Accelerometer)
2. Arduino Uno (Receiver) and Arduino Nano (Transmitter)
3. ZigBee Module (Wireless Communication)
4. DC Gear Motors
5. L293D Motor Driver
6. 7805 Regulated Power Supply
7. 12V Battery

## Software Implementation
The system is programmed using the Arduino IDE software. The code interprets the accelerometer data, processes hand gestures, and sends corresponding commands to control the robotic car's movement.

## How to Use
1. Wear the transmitter glove containing the Arduino Nano and MEMS sensor.
2. Move your hand in different directions to control the robot (forward, backward, left, right).
3. The ZigBee module wirelessly transmits commands to the receiver on the robotic car.
4. The receiver processes commands and controls the DC gear motors through the L293D motor driver.

## Project Advantages
- Easy to control with intuitive hand gestures.
- Beneficial for physically challenged individuals.
- Enhances safety by isolating electric shock risks.

## Project Limitations
- Control limited to four directions.
- Lack of feedback for verifying the robot's direction.
- Line of sight control (15 to 20 meters).

## Conclusion
The Gesture Controlled Robot project demonstrates the successful integration of gesture recognition technology with robotics, providing a secure and user-friendly means of controlling a robot through hand movements.

Feel free to contribute to the project and share your ideas for improvements!

*Note: Add any additional information, acknowledgments, or troubleshooting tips as needed.*
