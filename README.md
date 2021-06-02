# dreamspace-mini-cnc-plotter-project-
dreamspace-mini-cnc-plotter-project 
How to make Arduino mini CNC plotter machine 
Hello friends, in this post we will see how to make a mini CNC plotter machine using an old scrap DVD drive, Arduino and CNC v3 shield.
In fact in the past I have built some Arduino mini CNC plotter machines or drawing machines in the past.
But those projects are not well documented and unclear so I got many request to make a detail in depth tutorial about how to make Arduino basic mini CNC plotter machine 
So in this post l am going to cover all points like hardware assembly ,code for Arduino, G-code generation etc.
So before moving further let me brief you about what is the CNC plotter machine is 
Overview 
CNC plotter machine is basically a 2.5 axis CNC machine , it has two stepper motors on both X and Y axis and servo motor at Z axis.
A pen is  connected on the Y-axis and Z-axis is used to make pun up and down.
As the name suggests, the plotter machine obviously drows or plots a drawing as per given instruction.
To give instructions to machines to draw a special type of code called G-code is required .
Image will be converted to G-code with the help of special type of software,
Afterwards this  G-code sends to controller and controller commands motors.
How to move 
As a result , the machine will draw images on paper.
Now lets see how to build such a machine. starting with materials list 
MATERIAL LIST
1. Arduino UNO - 1
2. CNC shield - 1
3. a4988 stepper motor driver - 3
4.mini servo motor -1
5.12v - 2amps power supply
6.scrap DVD drive - 3
7.some wires for motor connection
8.Nut and bolts.
SOFTWARE LIST 
1.Arduino IDE
2. Universal G-code controller 
3. Inscape version 
Please download the software from the above link, and install them on your PC.
CODE AND LIBRARY
CNC code for Arduino (GRBL library)
MakerBot G-code inscape extension
“CNC code for Arduino (GRBL library)”
How to do all this? We will see further.
MACHINE ASSEMBLY
