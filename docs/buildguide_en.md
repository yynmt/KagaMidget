# KagaMidget Build Guide

## Parts

|| Name | Qty | Notes |
|:---:|---|---:|---|
|1|PCB|1||
|2|Top plate|1||
|3|Middle plate|2||
|4|Bottom plate|1||
|5|Tact switch(3x6mm)|50|Available for purchase [here](http://akizukidenshi.com/catalog/g/gP-08073/)|
|6|Diode(1N4148W)|50|Available for purchase [here](http://akizukidenshi.com/catalog/g/gI-07084/)|
|7|Pin socket(14x1)|2|Available for purchase [here](http://akizukidenshi.com/catalog/g/gC-00661/)|
|8|Screw(M3 15mm)|4||
|9|Cap nut(M3)|4||
|10|ProMicro/Proton C/Elite-C|1|ProMicro available [here](https://yushakobo.jp/shop/promicro-spring-pinheader/)|
|11|Pin header(12x1)|2|Included in ProMicro|
|12|USB cable|1|   |

## Build process

1. Yell for motivation.
2. Trim the feet of the tact switch with a nipper (easier to do now than later).
3. Fold the included socket to 12 pins and trim the legs with a nipper.
4. Solder 48 diodes to the bottom of PCB - pay attention to the direction of the diodes. Lines on the diodes should match the lines on the PCB.
5. Solder two pin sockets to the bottom of the PCB.
6. Solder 49 tact switches to the top of the PCB.
7. Insert the pin header supplied with Microcontroller into the pin socket and trim the correct length.
8. Flash `kagamidget` in [QMK](https://qmk.fm) onto the Microcontroller.
9. Solder the trimmed header to the Microcontroller.
10. Test all the buttons.
11. Screw the PCB between the plates.
12. You're finished! Have fun :)

## Plates data

Distributing plate data.
The thickness of the middle plate needs 6 mm.

- [all](../plates/all.svg)
- [top](../plates/top.svg)
- [middle](../plates/middle.svg)
- [bottom](../plates/bottom.svg)
