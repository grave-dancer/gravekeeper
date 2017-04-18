# gravekeeper10

Gravekeeper10's firmware is written in C++ for the MSP430FR59XX series MCU's.
Gravekeeper is a USB MSC device that offers hardware steganography + cryptography.

One MSP430FR5994 is used for data manipulations, 
with AES256 for Crypto, 
LEA Module + HW MPY for Stegano, 
and SPI+DMA for SD Card Access.

One MSP430F5529 is used for MSC device class communication between SD card and computer.

One FTDI FT232RL is used for flashing the MSP430F5529 and MSP430FR5994 through USB client.

Target Operating Systems:
Linux (Ubuntu/Debian)
Windows 7/8/10

hardware/ - KiCad Schematics/PCB files
firmware/ - MSP430FR5994 + MSP430FR5529 related firmware
software/ - Software Client in Python
