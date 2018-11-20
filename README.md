# hc-sr04
Example of using Ultrasonic Sensor HC-SR04 with Cortex-M based microcontroller TM4C

For this example, I used:
- Tiva C series LaunchPad EK-TM4C123GXL
- Display Nokia 5110
- HC-SR04 Sensor
- breadboard and wire connectors (for powering sensor I used old usb cable)

HC-SR04 connection  
Vcc and Gnd connected to usb cable (note that Gnd should be also connected to Tiva's ground)  
Trig    PA4  
Echo    PB6  

Nokia 5110 connection  
Rst     PA7  
CE      PA3  
DC      PA6  
DIN     PA5  
CLK     PA2  
VCC     +3.3V  
BL      not connected (backlight)  
GND     GND  

Keil uVision (evaluation version) is used for compiling/flashing/debugging.
