# QuadrupedV1-CAD
CAD repository for a Medium-size 3d printed quadruped

<img src="https://github.com/timxuti/QuadrupedV1-CAD/blob/main/0.%20Project%20Documents/1.%20Images/Quadruped%20V1.jpg?raw=true" width="700"/>

## 0: Quadruped
This is a prototype using Xiaomi's Cybergear QDDs. I am in the process of developing my own QDD and FOC ESC, as well as improving on the mechanical and electronic layout of the quadruped.

## 1: Description
This repo does not contain any code or electrical schematics for the robot. There will only be SW, STEP, manufacturing, and image files included. This is also a rough design for a rough quadruped design with the sole objective of standing up and walking. Further major developments will be in a different repo.

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
