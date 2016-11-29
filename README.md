# UART Battleship

UART Battleship implements a UART in hardware using Verilog. A top level battleship game is implemented using the NOIS II Micropocessor in C. The UART and game can be downloaded onto two Cyclone V FPGAs attached with by one IN/OUT bus. Using the Eclipse NIOS II IDE, players can generate a game board and send coordinates back and forth and try to sink the other player's battleship.

##UART Hardware Design

![alt text](https://github.com/Katieneff/UART-Battleship/blob/master/hardware.png "Hardware Design for UART")

This image shows the top level hardware design for the UART. The Verilog code is found in ```src/```
