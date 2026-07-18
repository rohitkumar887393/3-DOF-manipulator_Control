# 3-DOF Manipulator Control

## Description
Controlling 3DOF robotics arm with ESP32 and integrated PID control system

## Project Structure

- **enc_controller/** - Encoder-based feedback control module
- **pid_controller/** - PID control system for the manipulator

## Hardware
- ESP32 Microcontroller
- 3-DOF Robotic Arm
- Encoders for position feedback
- Motor drivers(MD10C)
- Planetry geared DC motor

## Features
- PID control algorithm for smooth and precise arm movements
- ESP32-based real-time control
- Encoder feedback for position tracking
- Multi-axis control

## Getting Started

### Prerequisites
- PlatformIO IDE
- ESP32 board support
- Arduino IDE (if using Arduino framework)

### Installation

1. Clone the repository
2. Open each project folder in PlatformIO
3. Configure your board and upload the firmware

### Project Folders

#### enc_controller
Encoder feedback control system for the manipulator

#### pid_controller  
PID-based control system with integrated closed-loop feedback

## License
MIT

## Author
Rohit Kumar
