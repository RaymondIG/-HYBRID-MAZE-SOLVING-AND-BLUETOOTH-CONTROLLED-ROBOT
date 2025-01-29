# Hybrid Maze-Solving and Bluetooth-Controlled Robot

## Overview
This project presents the development of a hybrid robotic system capable of both autonomous maze-solving and manual control via Bluetooth. The robot integrates various sensors, including ultrasonic and line-tracking modules, to navigate efficiently. Additionally, a Bluetooth module allows for user intervention when necessary, providing a seamless transition between manual and autonomous modes.

## Features
- **Autonomous Maze-Solving:** Uses line-tracking and ultrasonic sensors to navigate mazes.
- **Bluetooth Control:** Allows manual control via a smartphone application.
- **Dynamic Mode Switching:** Seamlessly transitions between autonomous and manual operation.
- **Real-Time Feedback:** Mini display provides system status updates.
- **Obstacle Avoidance:** Ultrasonic sensors detect and avoid obstacles.
- **User-Friendly Interface:** Intuitive Bluetooth control for non-technical users.

## Components
- Keyestudio V4.0 Board (Arduino Uno compatible)
- Keyestudio Motor Driver Expansion Board
- Bluetooth Module
- Ultrasonic Sensor
- Line Tracking Sensor
- Keyestudio 8x16 LED Board
- 6 AA Battery Holder
- Motors & Wheels
- Servo Motor

## System Specifications
- **Microcontroller:** ATmega328P
- **Operating Voltage:** 5V
- **Input Voltage:** 6-9V
- **Max Output Current:** 2A
- **Motor Speed:** 200 RPM @ 5V
- **Bluetooth Control Range:** 50m

## Installation & Usage

2. Upload the Arduino code to the Keyestudio V4.0 Board (arduino Uno).
3. Connect the hardware components as per the circuit diagram.
4. Pair the robot with a smartphone via Bluetooth.
5. Use the mobile app to control the robot manually or switch to autonomous mode.

## Testing & Performance
- **Autonomous Navigation:** Successfully solved 72% of test mazes.
- **Obstacle Avoidance:** 80% efficiency in avoiding collisions.
- **Manual Control Delay:** 0.2 seconds average response time.
- **Mode Switching:** <1 second transition time.
- **System Uptime:** 1 hour continuous operation.

## Potential Improvements
- Enhance sensor accuracy for small or transparent obstacles.
- Optimize the navigation algorithm for complex mazes.
- Extend battery life for prolonged use.

## Contributors
- Ibrahim Abdullah Olalekan
- Raymond Igunma Nosakhare
- Ntia Kokomma Hope
- Famadewa Mojetoluwa
- Matthew-Awari Increase
- Kazeem Zainab Feyisara

## License
This project is licensed under the MIT License. See the LICENSE file for details.

