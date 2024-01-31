# PID Line Following Robot

## Introduction
In the EGB 220 project, our interdisciplinary team developed a PID Controlled Line Following Robot, focusing on precision and modularity. My role involved leading the design for the robot chassis as well as the sensor array. I was also responsible for programming an efficient PID line following algorithm. The robot featured a custom IR sensor array and a custom-designed PCB. Overcoming challenges like PCB design, sensor calibration and environmental factors, the final product exemplified a high-performing robotic solution, showcasing smooth, accurate line following capabilities, light weight chassis and fully functional custom PCBs.

![Robot Image](/Images/LineFollower.jpg)

### Demo Video

![Demo Video](/Videos/LF_demoVid.mp4)

## Features

- Input Voltage: up to 7.2V (2S Li-Ion battery)
- 4 Sensor IR array for PID controlled line following (Custom PCB)
- 2 Individual colour sensors for detecting side markers (Custom PCB)
- Voltage regulator for QUT Arduino Dev Board
- Custom main PCB including voltage regulator, H-Bridge motor drivers, status LEDs and buttons.

## Schematic
The robot had design constraints having to be less than 150mmx150mmx100mm.
There was cost constraints on the 3D printing which is why the chassis is minimal utilising the main PCB for structural integrity.

![Schematic](/Images/LF_schematic.jpg)

## Images

![Side](/Images/LF_sideOn.jpg)
![Top](/Images/LF_topDown.jpg)
![Bottom](/Images/LF_bottomUp.jpg)
