# Introduction
Source files for Arduino based boards designed for Souliss

Souliss runs on most of the Arduino compatible boards (with AVR microcontroller) and a complete list of compatible boards is avialable in the [wiki](https://github.com/souliss/souliss/wiki) and in the relevant [hardware](https://github.com/souliss/souliss/wiki/Supported%20Hardware%20Platform) section.

Some special design has been shared publicly and you can build them by your self. This repository contains schematics and PCBs.

### Battery Operated Board
![](https://github.com/yoosofpiran/Hardware/blob/MyBranch/Battery_Operated_Board/Ver1/Altium/Picture/1.PNG)

#Overview
The Battery Operated Board is a microcontroller board based on the ATmega32u4. It has digital input/output and Analoge 4 pin Grove connector,UEXT connector, an 8 MHz resonator, a micro USB connection, a JST connector for a 3.7V LiPo battery, and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with a battery to get started.

the ATmega32u4 has built-in USB communication, eliminating the need for a separate USB-to-serial adapter. This allows the Battery Operated Board to appear to a connected computer as a mouse and keyboard, in addition to a virtual (CDC) serial / COM port. 

#Power

The Battery Operated Board can be powered via the micro USB connection or with a 3.7V LiPo battery (connected to the JST connector on the board). Either power source is regulated down to the operating voltage (3.3V) by the on-board MCP1640.
The board contains a MCP73831 LiPo battery charging chip. If the board is connected to both USB and a battery, the USB power will charge the battery.The LED above the Board lights up while the battery is being charged. The charging will stop automatically when the battery is fully charged.

The power pins are as follows:

+ The regulated 3.3V power supply used to power the microcontroller and other components on the board. This can come either from the USB connection or a battery, both via the on-board regulator.
- Ground pin.


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Souliss Boards</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="http://souliss.github.io" rel="dct:source">http://souliss.github.io</a>.
