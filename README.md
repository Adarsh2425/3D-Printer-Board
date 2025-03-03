# 3D-Printer-Board
Check out my [3DP Tech You Tube channel](https://www.youtube.com/playlist?list=PLOfiVhkRK3Go6M8yRqPx5GOqqJWyXBp_2). This repository contains support files for the "Build a 3D Printer Control Board" series.

In this video series I explore the electronics of a 3D printer. I review the components that make up the control board and explain how they interact with the firmware to control a 3D printer. Finally, I show you how to build a complete control board for a 3D printer on a solderless breadboard.
## Episode Index
### Episode 1 - Introduction
In this episode I review the electronic components found in a 3D printer and give a high-level description of the role each plays to accomplish the task of printing a 3D model. I give an overview of the remaining episodes and state the objectives of the series.
### Episode 2 - Arduino Core
In this episode I demonstrate how to build a basic Arduino microcontroller on a breadboard. I guide you through the minimum circuit components required to get an ATMEGA1284P based Arduino up and running.
### Episode 3 - Flashing the Bootloader
In this episode I demonstrate how to flash a bootloader to the Arduino core circuit built in episode 2. This will allow firmware to be flashed easily from the Arduino IDE using a serial port.
### Episode 4 - Adding USB Support
In this episode I demonstrate a few ways to connect to the microcontroller using the USB port on a computer. I also demonstrate how to add a permanent USB port to the breadboard.
### Episode 5 - Power Supply
In this episode I demonstrate how to add a 5V regulator to the breadboard so that the control board can be run from a 12V or 24V power supply. I discuss the various ways to power the board while building it and cover the reason why a 12V or 24V power supply is necessary.
### Episode 6 - Stepper Motors
In this episode I review the basics of a stepper motor and demonstrate how to drive a stepper motor from an Arduino. I walk through adding the four necessary stepper motor drivers needed for the 3D printer.
### Episode 7 - Hot End, Bed Heater and Fan
In this episode I demonstrate how to control high voltage and high current devices through a MOSFET and an Arduino PWM pin. I discuss the basic principle of PWM and add the circuits to our breadboard that will control the fans, the hot bed heater the hot end heater cartridge.
### Episode 8 - Thermistors
In this episode I describe the basic operation of a thermistor and show how to read temperature. I walk through adding the necessary thermistor circuits to read temperatures on the 3D printer.
### Episode 9 - End Stops
In this episode I review the basics of monitoring a push button. I demonstrate how to add the end stop circuits to the printer control board.
### Episode 10 - LCD
In this episode I walk through the LCD used on the 3D printer and demonstrate how to add it to the control board.
### Episode 11 - Encoder & Piezo Buzzer
In this episode I demonstrate the basic function of the rotary encoder used to make menu selections on the LCD. I'll also show how to wire it into the breadboard along with the piezo buzzer (or beeper) to add (very) basic sound.
### Episode 12 - MicroSD Card
In this episode I demonstrate how to add a MicroSD card reader to the control board.
### Episode 13 - Flashing Marlin
In this episode I walk through configuring Marlin firmware for the control board and demonstrate how to flash it through the Arduino IDE. I also demonstrate the firmware operation on the control board using a virtual/demo 3D printer.
### Episode 14 - Connecting a Printer
In this episode I will connect the breadboard based control board to an actual 3D printer and print a 3D model.
### Episode 15 - Expanding the Board
In this episode I demonstrate ways to expand the board to offer more options that are readily supportable in the Marlin firmware.