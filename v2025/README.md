# v2025 Mechanics

Compared to the v2024 release the following changes have been made:
- The robot case for the black and white hull requirement has been redesigned
- The rear and side dribbler dampers have been updated in shape
- Camera and ball sensor arrays have been removed

Inventor folder contains the complete Inventor project for robot and base station including all parts.

STEP folder contains full step files of the robot assembly and the base station assembly. These files should be compatible with most CAD programs.

The `Purchased Parts.xlsx` file lists all third-party components used in the robot, including quantities, online shop URL and order number.  

## Electronic boards
v2025 robots use the following electronics boards which can be found in the electronics open-source repo:
- Ball Detection v4 (Break beam sensor)
- Encoder iC-PX v1b (Encoder IC carrier board)
- Front LEDs v1b
- IR Controller v2 (Break beam processor)
- Kicking Device v13b (Capacitor charge/discharge board)
- Mainboard v13 (Primary microcontroller and wireless transmitter board)
- Pattern Ident v2 (Automatic pattern identification system)
- Powerboard v1 (High current power board, motor controllers and power distribution)

## Inventor
To make sure all parts can be found by Inventor open the corresponding project file under `Inventor/TIGERs 2025.ipj`.  
The primary assembly file for the robot is `Inventor/Robot/HBG-Roboter v2025.iam`. You can open sub-assemblies by right-clicking on them and select open.  
The primary assembly file for the base station is `Inventor/Base Station/HBG-Base Station v3.iam`.  
