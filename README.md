# QuadrupedV1-CAD
CAD Repo for version 1 of my quadruped design  
!(https://camo.githubusercontent.com/4e18cf9e868800e5d45909f6e0b3d26a0cf1d6e8d6266fb9230b8f7b6ce6e431/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313031343239393830353238353130353639362f313330333236373532323239363032353132382f494d475f303738352e6a70673f65783d36373266313637362669733d363732646334663626686d3d6135333634326264633939373432353061306535373761643937663039386565353638623930633661353165386139303866313039346665633839316363626326)

## 1: Description
This repo does not contain any code or electrical schematics for the robot. There will only be SW, STEP, and 3MF files included. This is also a rough design for a rough quadruped design with the sole objective of standing up and walking. Further major developments will be in a different repo.

## 2: Subcomponents and File Naming
Custom parts should obey the XXXX YZZ - NAME file number convention:  
XXX: Module ID (Alphabetical)  
Y: File type classifier (Numbers)  
ZZ: Part number (Numbers)  
NAME: Descriptive file name in Title Capitalization Form  

### 2.1: Module IDs
QUAD: Top-level assembly  
CHAS: Chassis  
LEG: Leg  
FTST: Fit test files  

### 2.2: File Classifiers
0: Top-level assemblies (No more than 1)  
1: Subassemblies  
2: Equation.txt files  
3: Drawings  
4: Individual parts  
5: Wiring, piping, and tubing  
6: Weldments  
7: Solidworks FEA Simulation Files  
8: Solidworks VISUALIZE files
9: Manufacturing files (3MF, STL, DXF, GCODE)  
