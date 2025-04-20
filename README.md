# eink-breakout
Kicad project for a Dalian Good Display Epaper breakout board. The
display (GDEW042T2) has a 24pin flat panel cable. The display is
controlled with the SPI bus, so the display SPI pins are passed to a
JST PH connector. The rest of the conductors on the flat panel cable
are powered or grounded as shown in the datasheet example
wiring. There is no bus translation, everything is set at 3.3VDC.

## Functions
The main function of the board is to translate the signals from the
flat panel cable to the JST PH connector. The JST connector has
signals for the SPI bus, D/C, Busy from the eink display. Also power
and ground at 3.3VDC.

## Schematic
[Eink-breakout v1 Schematic](eink-breakout-sch-v1.pdf)

## Parts List
A parts list as an LibreOffice Calc file
[Parts List](eink-breakout.ods)

## PCB by OshPark

![Generated image of front of pcb](/osh-park-pcb-front.png)

## License

Licensed under

- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)
