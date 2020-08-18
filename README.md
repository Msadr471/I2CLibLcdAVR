# I2CLibLcdAVR
i2c LCD Library for AVR 


Mohammad Sadr Notes
-----------
This library has been slightly modified to run on Atmel Studio.



lcdpcf8574 lib

= Copyright (c) Davide Gironi, 2013
= http://davidegironi.blogspot.it/



This library implements a driver for HD44780 lcd connected through PCF8574
port expander.
Data is transmitted using only 2 wire over i2c with the PCF8574.
Lcd driver is based upon Peter Fleury's lcd implementation.

Setup parameters can be found in file lcdpcf8574.h and pcf8574.h


Devel Notes
-----------
This library was developed on Eclipse, built with avr-gcc on Atmega8 @ 1MHz.


License
-------
Please refer to LICENSE file for licensing information.


DataSheet 
-------
The PCF8574 is a silicon CMOS circuit. It provides general purpose remote I/O expansion for most microcontroller families via the two-line bidirectional bus (I2C). ... The PCF8574 has a low current consumption and includes latched outputs with high current drive capability for directly driving LEDs.
