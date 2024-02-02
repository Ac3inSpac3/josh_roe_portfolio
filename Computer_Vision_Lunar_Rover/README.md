# OpenCV Lunar Rover

## Introduction
For my Mechatronics 2 class, our projects objective was to design and develop a Technology Readiness Level (TRL) 3 prototype capable of autonomously locating, approaching, and retrieving lunar rock samples represented by orange golf balls. The project aims to pitch autonomous robotic exploration concepts to secure funding and enhance Australia's space exploration capabilities.
![Robot Image](/Images/LunarRobot.jpg)

## Design Highlights:

Mobility: Utilises high torque micro geared motors and rubber Pololu tracks.
Sample Collection: Employs a split wedge design for efficient rock flipping and sample collection.
Vision System: Features a high-mounted camera using OpenCV for environmental interpretation, guiding navigation by identifying objects' bearing and distance.
Navigation: Integrates complex vector fields for object avoidance, weights varying depending on if the robot is search under rocks for samples or for free samples.
Size: Fits within a Cubesat U1.5 form factor (150mm cubed) with a weight limit of 800 grams.
Performance: The design includes a cooling fan for the Raspberry Pi to minimize thermal throttling, enhancing performance of the OpenCV code allowing it to run at 30+ fps consistently.

## Demo Video

### Rock flipping and sample collection
https://github.com/Ac3inSpac3/josh_roe_portfolio/assets/60162987/97058c62-8094-453e-bc05-9aa4faa02795

### Rock flipping and sample collection
https://github.com/Ac3inSpac3/josh_roe_portfolio/assets/60162987/e5302c60-0233-4f46-8ce6-ad5c992e547d

## Images
### Schematic
![Schematic](/Images/LunarSchematic.jpg)
![Schematic 2](/Images/LunarSchematic2.jpg)

### Lunar Vision Process
![Lunar Vision Process](/Images/LunarVision.jpg)
### Lunar Vision Input, Masking and Output
![Lunar Vision Process](/Images/LunarVision2.png)

