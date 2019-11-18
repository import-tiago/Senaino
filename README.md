# Senaino (CH340)
[![Version](https://img.shields.io/badge/Version-FT232-blue.svg)](https://github.com/TiagoPaulaSilva/Senaino) [![Status](https://img.shields.io/badge/Status-Finished-green.svg)](https://github.com/TiagoPaulaSilva/Senaino)

[![Version](https://img.shields.io/badge/Version-CH340-blue.svg)](https://github.com/TiagoPaulaSilva/Senaino/tree/CH340) [![Status](https://img.shields.io/badge/Status-Finished-green.svg)](https://github.com/TiagoPaulaSilva/Senaino/tree/CH340)

[![Donate](https://img.shields.io/badge/Donate-Buy%20Me%20a%20Coffee-yellow.svg)](https://www.buymeacoffee.com/TiagoPaulaSilva)


Senaino is a board inspired by Arduino UNO. With components that can easily be found in Brazil, this board will allow the students of SENAI (an important school of technical education in Brazil) to learn about soldering, electronics and programming.

![Image](https://github.com/TiagoPaulaSilva/Senaino/blob/CH340/2.%20Mounting/Mounted%20Board%20Photo.jpeg)


## Recommended CH340 Driver: [CH340](https://sparks.gogo.co.nz/assets/_site_/downloads/CH34x_Install_Windows_v3_4.zip)

## Bootloader
For extremely optimized bootloader burning, see my new project: [GimmeSoul](https://github.com/TiagoPaulaSilva/GimmeSoul)

## Schematic
![image](https://github.com/TiagoPaulaSilva/Senaino/blob/CH340/2.%20Mounting/Schematic.png)

## Bill of Materials
To mount the components on the board, follow the instructions: [Designator References](https://github.com/TiagoPaulaSilva/Senaino/blob/CH340/2.%20Mounting/Components%20Silk%20Screen.png)

| Qty | Parts | Description | Value | Package |
|--|--|--|--|--|
1|R2|PTH Resistor|150Ω ±5%|CR25 (1/4W)
1|R1|PTH Resistor|330Ω ±5%|CR25 (1/4W)
4|R3/R4/R6/R7|PTH Resistor|1 kΩ ±5%|CR25 (1/4W)
1|R5|PTH Resistor|10 kΩ ±5%|CR25 (1/4W)
5|C2/C3/C4/C7/C8|PTH Ceramic Capacitor|100 nF x 50 V|Disc
4|C5/C6/C15/C16|PTH Ceramic Capacitor|22 pF x 50 V|Disc
1|C1|PTH Electrolytic Capacitor|100 uF x 35 V|Radial
1|D1|PTH Rectifier Diode|1N4007|DO-41
1|D2|PTH Schottky Diode|BAT43|DO-35
1|D3|PTH Zener Diode|1N4728|DO-41
1|LED1|PTH LED|Green|3mm
2|LED2/LED3|PTH LED|Yellow|3mm
1|Q1|PTH Crystal|16 MHz|HC49/S
1|Q2|PTH Crystal|12 MHz|HC49/S
1|U1|PTH Microcontroller|ATmega328P-PU|DIP-28N
1|U1|PTH IC Socket|28 Pins|DIP-28N
1|U4|SMD USB/Serial Converter|CH340G|SOP-16
1|U3|PTH Voltage Regulator|L7805CV|TO-220
1|X1|PTH Connector|Jack J4|2.1 mm (3 Terminals)
1|X2|PTH Connector|Female USB Type-B|PCB 90°
1|-|PTH Pin Header|Female 180°|1x10
2|-|PTH Pin Header|Female 180°|1x8
1|-|PTH Pin Header|Female 180°|1x6

### Contributing
0. Give this project a :star:
1. Create an issue and describe your idea
2. [Fork it](https://github.com/TiagoPaulaSilva/Senaino/fork)
3. Create your feature branch (`git checkout -b my-new-feature`)
4. Commit your changes (`git commit -a -m "Added feature title"`)
5. Publish the branch (`git push origin my-new-feature`)
6. Create a new pull request
7. Done! :heavy_check_mark:

### License Information
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Senaino</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/TiagoPaulaSilva" property="cc:attributionName" rel="cc:attributionURL">Tiago Silva</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://store.arduino.cc/usa/arduino-uno-rev3" rel="dct:source">https://store.arduino.cc/usa/arduino-uno-rev3</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="https://twitter.com/tiagopsilvaa" rel="cc:morePermissions">https://twitter.com/tiagopsilvaa</a>.
