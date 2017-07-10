# Marlin---Tevo-Tarantula-3d-printer

This is repository contains my personal settings for my 3D printer, the Tevo Tarantula.   
This settings should be ok to replace the stock printer firmware but be aware to set "E " in `#define DEFAULT_AXIS_STEPS_PER_UNIT { 79.60,79.44,1576, E }` with the stock value before flashing. I have a Wade extruder and this is why my value is very high. 

Marlin is an Open Source firmware for 3d printers, and it can be found at the github page https://github.com/MarlinFirmware/Marlin; or here http://marlinfw.org/ for more details.


## How to install this firmware: 

* Install Arduino IDE - https://www.arduino.cc/en/Main/Software
* Clone the respository - `git clone git@github.com:akaped/Tevo-Tarantula-Firmware---Marlin1.1.X.git`
* open `Marlin.ino` 
* Edit the settings of the `Configuration.h` file
* Select _Arduino Mega ADK_ from the list of boards. 
* Select the correct port for the connected 3d printer. 
* Upload the firmware.


