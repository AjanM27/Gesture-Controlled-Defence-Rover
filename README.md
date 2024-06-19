# Gesture Controlled Defence Rover

## Project Overview

The Gesture Controlled Defence Rover is an innovative project designed to enhance remote bomb detection and disposal. The rover features a robotic arm controlled by hand gestures, allowing for precise and safe operation in potentially dangerous environments. This project utilizes a combination of sensors, wireless communication, and microcontrollers to achieve full remote control and operation. This is a project that I made in my school days that helped me win multiple awards.

## Features

- **Gesture Control**: The rover and the robotic arm are controlled by hand gestures. One hand controls the rover's movement, while the other controls the arm.
- **Camera Module**: Equipped with a camera on top of the robotic arm to provide real-time video feed for remote operation.
- **Metal Detector**: Integrated metal detector to identify and locate mines.
- **Wireless Operation**: Completely wireless control using RF433MHz and NRF24L01 transceivers.

## Components Used

- **Microcontrollers**: Arduino Uno and Arduino Nano
- **Sensors**: MPU6050 (Gyroscope and Accelerometer), Flex Sensors
- **Communication Modules**: HT12E, HT12D, RF433MHz Transmitter and Receiver, NRF24L01 Transceiver
- **Power**: LiPo Batteries
- **Camera Module**: For live video feed
- **Other**: Metal Detector

## How It Works

1. **Gesture Control**: 
    - The MPU6050 and flex sensors capture hand movements.
    - These movements are interpreted to control the rover's movement and the robotic arm.
2. **Wireless Communication**: 
    - Data from the hand gestures is transmitted wirelessly using RF433MHz and NRF24L01 modules.
3. **Camera Feed**: 
    - The camera module on the robotic arm provides a live feed, allowing the operator to see the environment and make precise movements.
4. **Mine Detection**: 
    - The metal detector scans the ground for mines, ensuring safe navigation.

## Setup and Installation

1. **Hardware Assembly**: 
    - Assemble the rover chassis, attach the robotic arm, camera module, and metal detector.
    - Connect the sensors (MPU6050, flex sensors) to the Arduino boards.
2. **Software Configuration**: 
    - Upload the Arduino sketches to the Arduino Uno and Nano boards.
    - Ensure the wireless communication modules (RF433MHz and NRF24L01) are correctly configured.
3. **Power Supply**: 
    - Connect the LiPo batteries to power the system.

## Usage

1. **Power On**: 
    - Turn on the rover and the control gloves with the sensors.
2. **Control**: 
    - Use hand gestures to control the rover’s movement and the robotic arm.
    - Monitor the camera feed for navigation and bomb disposal tasks.
3. **Mine Detection**: 
    - Use the metal detector to scan for mines as you navigate the rover.

## Code

The code for this project is divided into several parts:

1. **Rover Control**: 
    - Code for controlling the rover's movement using gestures(receiver & transmitter).
2. **Robotic Arm Control**: 
    - Code for controlling the robotic arm using gestures(receiver & transmitter)

## Future Enhancements

- **Enhanced Stability**: Improve the stability and accuracy of gesture recognition.
- **Obstacle Detection**: Integrate additional sensors for obstacle detection and avoidance.
- **Extended Range**: Increase the range of wireless communication for larger operational areas.

