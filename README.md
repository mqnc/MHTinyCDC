# MHTinyCDC
Copy of the DigiCDC library, added configurations to work with the MH-ET LIVE Tiny88 board

## DOESN'T WORK
Please check out this issue: https://github.com/mqnc/MHTinyCDC/issues/3

## Installation
Download as zip from github (Code▼ -> Download ZIP)

In Arduino IDE: Sketch -> Include Library -> Add .ZIP Library

## Usage
See examples on how to use!

## Sources
Original DigiCDC Library:

https://github.com/digistump/DigistumpArduino/tree/master/digistump-avr/libraries/DigisparkCDC

The only changes I made are in usbconfig.h; I added port and interrupt settings for the ATtiny88 which I got from here:

https://github.com/micronucleus/micronucleus/blob/master/firmware/configuration/t88_default/bootloaderconfig.h

## Extending
All the other V-USB libraries by Digistump should also work with the usbconfig.h from this project but I didn't try any.

## Enjoy Wishing
Enjoy!
