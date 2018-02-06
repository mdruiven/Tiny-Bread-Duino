# Tiny-Bread-Duino
ATTiny85 Arduino on a breadboard
Created for ACSE 2018 conference.
Everything here is open source.
Everything else is here: https://goo.gl/QbjK1i

This circuit can be assembled for less than $5 using wholesale prices and overseas suppliers.

STEP 1.
Assemble and solder the USB breakout.

STEP 2.
Assemble the circuit as shown below. Work from the top down. The 5 pin header shown below shows the positioning for the USB breakout board. Make your jumpers neat and cut leads to achieve the look shown below. Diodes marked Z are 3.6V zener diodes (2). The diode at the top is a 1N4148 (1).


STEP 3.
Load the Digistump AVR Boards by Digistump using the Boards Manager in Arduino. Select “Digispark (default-16.5 Mhz)” board in Arduino. Do not plug your board into the computer.

STEP 4
Load the BlinkBreadDuino program found in Github or in the shared cloud folder https://goo.gl/QbjK1i. The Green LED is a power LED. The red LED is connected to Pin 1 (address) (pin 6 physical).

NOTES
1. Github also contains the micronucleus boot loader that can be “burned” to the chip using an AVR programmer. This is in an archive called “isp.zip”.
2. If the Bread Duino is run from an external supply then 2 capacitors, 0.1uF and 10uF should be added between supply plus and minus, near the chip on the breadboard.
3. The cloud folder at  https://goo.gl/QbjK1i contains USB drivers and also contains an older version of the Arduino IDE in the Digispark-Arduino-1.0.4.zip archive. 
4. The Digispark Windows drivers (USB) is also on Github.
