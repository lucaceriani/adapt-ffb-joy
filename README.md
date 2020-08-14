### Force feedback working with Microsoft Sidewinder Force Feedback Pro
I forked for future ference. I found online the correct HEX file to make Force Feedback work reliabily.
I tested with Microsoft Sidewinder Force Feedback Pro and it works perfectly.

Below the orginal README.

***

# What is Adapt-FFB-Joy #

Adapt-FFB-Joy is an AVR microcontroller based device that looks like a joystick with advanced force feedback features in a Windows machine without need for installing any device drivers to PC.

This project contains the software for the AVR microcontroller as well as basic instructions for [building the hardware](https://github.com/tloimu/adapt-ffb-joy/blob/wiki/HowToBuild.md).

Currently, it allows connecting a Microsoft Sidewinder Force Feedback Pro (FFP) joystick (with a game port connector) to various MS Windows versions as a standard **USB joystick with force feedback** and **no need to install any device drivers**. The adapter also allows to solder a few additional trim pots to work e.g. as elevator trims, aileron trims and rudder pedals in your favorite simulator game.

For more information, see [Adapt-ffb-joy Wiki] (https://github.com/tloimu/adapt-ffb-joy/blob/wiki/README.md)

The firmware software project is configured to compile for ATmega32U4 with WinAVR-20100110 or newer version.
