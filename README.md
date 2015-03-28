# Introduction
Source files for Arduino based boards designed for Souliss

Souliss runs on most of the Arduino compatible boards (with AVR microcontroller) and a complete list of compatible boards is avialable in the [wiki](https://github.com/souliss/souliss/wiki) and in the relevant [hardware](https://github.com/souliss/souliss/wiki/Supported%20Hardware%20Platform) section.

Some special design has been shared publicly and you can build them by your self. This repository contains schematics and PCBs.

### Power Socket based on nRF24L01 radio

The powersocket is a small radio node (2.4 GHz based on Nordic nRF24L01) that allow you to control remotely a 110/220 VAC device through a relay.

![](https://github.com/souliss/boards/blob/master/Power_Socket_nrf24_mini/Power_Socket_nrf24_mini_pcb_copperside.png)

Two design are available:
  
* [Power socket based on Arduino MINI](https://github.com/souliss/boards/tree/master/Power_Socket_nrf24_mini)
* [Power socket based on Atmel ATmega328P](https://github.com/souliss/boards/tree/master/Power_Socket_nrf24_dil)
