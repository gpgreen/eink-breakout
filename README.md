# Eink-Breakout
Kicad project for a [Dalian Good Display](https://www.good-display.com/) Epaper breakout board. The
display [GDEW042T2](https://www.good-display.com/product/226.html) has
a 24pin flat panel cable. The display is controlled with the SPI bus,
so the display SPI pins are passed to a JST PH connector.

Note: R1 is shown on the datasheet example circuit. It is not needed so should not be
populated on the board.

## Functions
The main function of the board is to translate the signals from the
flat panel cable to the JST PH connector. The JST connector has
signals for the SPI bus, D/C, Busy from the eink display. Also power
and ground at 3.3VDC.

The rest of the conductors on the flat panel cable are connected as
shown in the datasheet example wiring. There is no bus translation,
everything is set at 3.3VDC.

 - [Schematic](eink-breakout-sch-v1.pdf)

## PCB

 - ![PCB front](/osh-park-pcb-front.png)
 - [Parts List](eink-breakout.ods)

## License

Licensed under

- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)
