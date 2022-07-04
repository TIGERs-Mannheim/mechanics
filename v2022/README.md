# v2022 Mechanics

Compared to the v2020 release major changes have been done to the dribbler unit. The kicker plunger has changed to make it more robust.

Inventor folder contains the complete Inventor project for robot and base station including all parts.

PDF folder contains manufacturing drawings for parts produced by milling or turning. Note that only outer dimensions and important tolerances are given. Other data must be taken from STEP files.

STEP folder contains STEP files for manufacturing of parts produced by milling and turning as well as a file for the whole assembly of the robot.

STL folder contains all parts manufactured by 3D printing. See subfolder for material recommendations.

## Electronic boards
v2022 robots use the following electronics boards which can be found in the electronics open-source repo:
- Ball Detection v4 (Break beam sensor)
- Encoder iC-PX v1b (Encoder IC carrier board)
- Front LEDs v1b
- IR Controller v2 (Additional ball sensor and break beam processor)
- Kicking Device v13b (Capacitor charge/discharge board)
- Mainboard v13 (Primary microcontroller and wireless transmitter board)
- Pattern Ident v2 (Automatic pattern identification system)
- Powerboard v1 (High current power board, motor controllers and power distribution)

## Inventor
To make sure all parts can be found by Inventor open the corresponding project file under `Inventor/TIGERs 2022.ipj`.  
The primary assembly file for the robot is `Inventor/Robot/HBG-Roboter v2022.iam`. You can open sub-assemblies by right-clicking on them and select open.  
The primary assembly file for the base station is `Inventor/Base Station/HBG-Base Station v3.iam`.  
The excel list at `Inventor/Purchased Parts.xlsx` contains all purchased parts, including quantities, online shop URL and order number.  
Some image renderings are available at `Inventor/Renderings`.  
Inventor presentation files and drawings are in `Inventor/Presentations` and `Inventor/Drawings`, respectively.
