# Changelog

## [2.2.2] - 2023-10-06

Component replacements for PCBA/costing and related layout work.

### Major changes

- Tactile switches swapped out for bigger components
- LDOs swapped out for more efficient components
- USB-C connector changed for unit that only handles power
- layout positioning of 1 symbol -> 2 placements for carrier board

## [2.2.0] - 2023-10-01

Rework and complete re-route for the TT 1-3 mainboard.

### Major changes

- Flipped the input DIP switch so physical and logic match-up (ON is high)
- Fix: reset and clock only affect project, i.e. mapped to in 0 and 1
- Fix: debouce circuits reworked, positive edge on button press
- Mapped Caravel HK SPI to Pico
- Remapped external pin headers
- Removed resistor networks as we can rely on caravel pull-downs
- Routed such that manual remap of output to 7-segment display won't involve avoiding traces while cutting jumpers   

## [2.1.0] - 2023-07-19

Mainboard for TT 01, 02 and 03 released, with DIP switches for inputs and selection, PMOD I/O,
7-segment display and Raspberry Pi Pico footprint.

This is the preliminary release of the schematic, for review and prototyping.
