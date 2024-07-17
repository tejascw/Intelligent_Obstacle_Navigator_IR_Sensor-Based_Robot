# Obstacle Detection and Navigation Robot


## Project Overview

This project involves the design and development of an obstacle detection and navigation robot. The robot is equipped with infrared (IR) sensors to detect obstacles and navigate through its environment by avoiding them. The project encompasses hardware assembly, sensor integration, and software programming to achieve autonomous navigation.

## Table of Contents

- [Introduction](#introduction)
- [System Requirements and Specifications](#system_requirements_and_specifications)
- [Methodology](#methodology)
- [Implementation](#implementation)
    - [Hardware Assembly](#hardware_assembly)
    - [Component Connections](#component_connections)
    - [Logical Programming](#logical_programming)
- [Testing and Debugging](#testing_and_debugging)
- [Results](#results)
- [Applications and Future Scope](#applications_and_future_scope)

## Introduction

The Obstacle Detection and Navigation Robot is designed to autonomously navigate its environment while avoiding obstacles. The robot uses IR sensors to detect obstacles and adjusts its path accordingly.

## System_Requirements_and_Specifications

The robot system includes:

- Arduino Uno R3 microcontroller
- L298 motor driver module
- N20 motors with rubber wheels
- Infrared (IR) sensors
- 12V power supply
- Robot chassis

## Methodology

The methodology includes the following steps:

1. Assembling the robot hardware
2. Connecting components to the microcontroller and power supply
3. Programming the Arduino to process sensor data and control the motors
4. Calibrating the IR sensors for reliable obstacle detection
5. Testing and debugging the system for optimal performance

## Implementation

### Hardware_Assembly

The assembly involves mounting the sensors, motors, and microcontroller onto the robot chassis. Key components are strategically placed to ensure balance and functionality.

### Component_Connections
|        |               
|--------|
| All components are interconnected using male-female jumper wires. The motor driver is connected to the power supply and the Arduino, which processes sensor data and controls the motors. | 
| <img align="centre" alt="coding" width="500" hight="500" src="https://github.com/user-attachments/assets/4b3ae8a9-5125-4cee-86b3-31959b03460a"> |

### Logical_Programming

The Arduino is programmed using the Arduino IDE. The code involves:

- Reading sensor data
- Calculating errors based on sensor readings
- Adjusting motor speeds and directions to avoid obstacles
|  **Flow-chart**      |  **Code** |             
|--------|--------|
| <img align="centre" alt="coding" width="500" hight="500" src="https://github.com/user-attachments/assets/2f229a44-5d1b-4269-880a-75688ad1b721"> |  |



## Testing_and_Debugging

The robot is tested in different environments to ensure reliable obstacle detection. Various materials (wood, metal, glass, etc.) are used to test the response time and detection range of the IR sensors.

## Testing_&_Observation

| Testing with White Surface Object  | Testing with Black Surface Object |Testing with Glass Object |     
|--------|---------------|---------------|
| <img align="right" alt="coding" width="300" hight="400" src="https://github.com/tejascw/Intelligent_Obstacle_Navigator_IR_Sensor_Based_Robot/blob/main/ASSET/WHITE_SURFACE_OBJECT2-ezgif.com-video-to-gif-converter.gif"> | <img align="right" alt="coding" width="300" hight="400" src="https://github.com/tejascw/Intelligent_Obstacle_Navigator_IR_Sensor_Based_Robot/blob/main/ASSET/BLACK_OBJECT1-ezgif.com-video-to-gif-converter.gif"> | <img align="right" alt="coding" width="300" hight="400" src="https://github.com/tejascw/Intelligent_Obstacle_Navigator_IR_Sensor_Based_Robot/blob/main/ASSET/GLASS_OBJECT-ezgif.com-video-to-gif-converter.gif">
|**Observtion:**
During robot testing on a white surface, the IR sensor promptly detected objects as they approached, enhancing collision avoidance. The effectiveness of the IR sensor is due to the more reflective & very less Absorbtive nature of white materials in the infrared spectrum. Due to dense reflection of IR rays to IR sensor's receiver it will help the robot to detect the white surface very quickly and easly.                 |          **Observtion:**       |             **Observtion:**    |
|                 |                 |                 |
|**Testing with Metal Object** |      **Testing with Rubber Object**          |    **Testing with Wood Object**             |   
| <img align="right" alt="coding" width="300" hight="400" src="https://github.com/tejascw/Intelligent_Obstacle_Navigator_IR_Sensor_Based_Robot/blob/main/ASSET/METAL_OBJECT-ezgif.com-video-to-gif-converter.gif"> |<img align="right" alt="coding" width="300" hight="400" src="https://github.com/tejascw/Intelligent_Obstacle_Navigator_IR_Sensor_Based_Robot/blob/main/ASSET/RUBBER_OBJECT-ezgif.com-video-to-gif-converter.gif">| <img align="right" alt="coding" width="300" hight="400" src="https://github.com/tejascw/Intelligent_Obstacle_Navigator_IR_Sensor_Based_Robot/blob/main/ASSET/WOOD_OBJECT-ezgif.com-video-to-gif-converter.gif"> | <img align="right" alt="coding" width="300" hight="400" src="https://github.com/tejascw/Intelligent_Obstacle_Navigator_IR_Sensor_Based_Robot/blob/main/ASSET/WOOD_OBJECT-ezgif.com-video-to-gif-converter.gif"> |
| **Observtion:**                |    **Observtion:**             |      **Observtion:**           |
|                 |                 |                 |

## Results

The robot successfully navigates its environment by detecting and avoiding obstacles. It demonstrates reliable performance in both bright and dark conditions.

## Applications_and_Future_Scope

The Obstacle Detection and Navigation Robot can be used in various applications, including:

- Autonomous vehicles
- Industrial automation
- Smart home systems
