# Open Source Pulse Height Analyzer
This repository contains the hardware designs and software applications of the Open Source Pulse Height Analyzer developed by Scientific Instrumentation Group (GICM) - University of Antioquia

Contents:
.ino file: upload this file to the ESP32 microcontroller (ESP32-DEVKITV1) using the Arduino IDE (Please install first the ESP32 board. Tutorial here: https://www.tutorialspoint.com/esp32_for_iot/installing_the_esp32_board_in_arduino_ide.htm

.pdf file: Circuit schematic with components values.

GUI folder: The python script with the graphical user interface (GUI). Please install the required libraries (pyserial, matplotlib and tkinter), and edit the GUI file changing the COM port number to the one corresponding to the ESP32 board. Finally run the GUI.py, after that the GUI should be displayed.

.zip file: Gerber files that allow you to print the PCB and build the PHA hardware. The gerber files are in the format required by JLCPCB. 
