# Autonomous 4WD Robot

A fully autonomous 4-wheeled robot platform powered by Raspberry Pi 5, Arduino Uno WiFi, ROS2 SLAM, Lidar, TF-Luna, and Hailo AI. This repository includes all code, wiring, and setup to build and run the robot.

---

## 🚗 Features
- BLDC 4-wheel PWM motor control via Arduino
- Raspberry Pi 5 for autonomy, sensor fusion, and AI
- ROS2 SLAM Toolbox + Navigation2 for mapping and navigation
- TF-Luna proximity detection
- YOLOv5 object detection with Hailo AI
- Auto-launch with systemd services

---

## 🛠 Hardware Overview

| Component                   | Description                             |
|----------------------------|-----------------------------------------|
| Raspberry Pi 5             | Main compute unit                       |
| Arduino Uno WiFi           | Motor control (PWM + direction)         |
| Hoverboard BLDC Motors x4  | 250W brushless DC wheels                |
| Motor Drivers              | Cytron MDDS30 or equivalent             |
| FHL-LD19 Lidar             | 12m 360° Lidar (USB)                     |
| TF-Luna Rangefinder        | UART-based proximity sensor             |
| Hailo AI Kit               | YOLOv5 inference module                 |
| Power Supply               | 24V for motors, 5V 5A for Pi            |

---

## ⚡ Wiring Diagram
See [Wiring Schematic](#1-wiring-schematic-overview) in guide.

---

## 🧩 File Structure

# autonomous-4wd-robot
autonomous-4wd-robot
