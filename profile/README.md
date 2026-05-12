# Caprock Autonomous Technologies

**Caprock Autonomous Technologies (CAT)** develops robotics hardware, embedded control systems, power electronics, and autonomous robot platforms from West Texas.

> **American autonomous systems built in West Texas.**

---

## About

Caprock Autonomous Technologies is focused on building practical robotics systems that connect hardware, firmware, power electronics, sensing, control, and autonomy.

The goal is to create modular robot platforms and electronics that are useful for mobile robots, education, research, and real-world prototyping.

CAT projects include robot controller boards, motor-driver boards, smart power systems, mobile rover platforms, ROS 2 software, and embedded robotics experiments.

---

## Focus Areas

- Robot controller boards
- Motor-driver hardware
- Smart robot power systems
- Embedded firmware
- ROS 2 and micro-ROS integration
- Mobile robot platforms
- LiDAR-based mapping and localization
- Camera-based observation systems
- UAV and ground robot simulation
- Robotics education and laboratory platforms

---

## Hardware Ecosystem

| Project | Description |
|---|---|
| **Caprock Core G4** | STM32G474-based robot controller board for motors, encoders, IMU, CAN, and ROS 2 / micro-ROS integration |
| **CAT Core ESP32** | Earlier ESP32-based controller board with display, buttons, LEDs, encoder counters, CAN, IMU, SPI, and I2C expansion |
| **Caprock PowerRock 3S4P** | Smart 3S4P robot power system with fuses, switches, buck converters, switched outputs, and fused power distribution |
| **CAT DriveRock 8H-IFX** | 8-half-bridge motor-driver board based on Infineon IFX007 drivers for up to four bidirectional DC motors |

---

## Rover Platforms

| Rover | Description |
|---|---|
| **CAT Rover R6 Mapper** | Early Mecanum-wheel mapping and localization robot using CAT Core ESP32, CAT DriveRock 8H, 360° LiDAR, and a 3S 18650 battery system |
| **CAT Rover R7 Turtle** | Larger experimental rover with lead-acid batteries, Arduino boards, Jetson AGX Xavier, RealSense D435i, Wi-Fi antennas, fuses, switches, and custom electronics |
| **CAT Rover R8 Observer** | Newer Mecanum-wheel observation rover designed around Caprock Core G4 and Caprock PowerRock 3S4P with camera pan/tilt control |

---

## Product Families

- **CAT Core** — robot controller boards
- **CAT DriveRock** — motor-driver boards
- **CAT PowerRock** — robot battery and power systems
- **CAT Rover** — mobile robot platforms
- **CAT Air** — UAV and drone systems
- **CAT ROS** — ROS 2 software packages
- **CAT Sim** — simulation and modeling tools
- **CAT Edu** — robotics education and lab platforms

---

## Development Story

The CAT ecosystem grew from practical robot-building experience.

Early robots such as **CAT Rover R6 Mapper** and **CAT Rover R7 Turtle** used custom wiring, separate batteries, buck converters, fuses, switches, breadboards, Arduino boards, and embedded computers. These platforms helped reveal the real challenges of robot electronics:

- messy wiring
- difficult power distribution
- multiple voltage rails
- separate fuses and switches
- high-current motor wiring
- sensor and computer power requirements
- controller integration challenges
- need for modular, reusable robot hardware

Those lessons inspired newer CAT hardware such as **Caprock Core G4**, **Caprock PowerRock 3S4P**, and **CAT DriveRock 8H-IFX**.

![CAT Rover R8 Observer](images/Observer_1.jpg)
![CAT Rover R8 Observer](images/Observer_2.jpg)
