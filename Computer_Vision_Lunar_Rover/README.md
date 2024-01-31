# OpenCV Lunar Rover

## Introduction
In my Mechatronics 2 class, our teams task was to develop a mock lunar rover designed to collect samples (Orange golf balls) on a mock lunar surface.

![Robot Image](/Images/LineFollower.jpg)

### Demo Video
The demo for the assignment was to drive 3 laps around the unseen course, stopping for at least 2 seconds at the start stop markers and lowering the speed between the red and green markers. The robot also had to indicate if it was on a straight or curve, we did this via an LED on the robot as well as lowering the speed of the robot depending on the curve. This video shows the first lap of our final demo which we completed perfectly.

https://github.com/Ac3inSpac3/josh_roe_portfolio/assets/60162987/1e8995d0-dcbe-4ed4-aca4-634ed054e4e2


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

