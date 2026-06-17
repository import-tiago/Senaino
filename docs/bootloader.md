# Bootloader Notes

Senaino CH340 uses an ATmega328P-PU with a 16 MHz crystal, so it can be programmed using the same general workflow used for Arduino UNO-compatible boards.

## Typical Workflow

1. Insert the ATmega328P-PU after power checks are complete.
2. Connect an ISP programmer to the board.
3. Select an Arduino UNO-compatible target.
4. Burn the bootloader.
5. Disconnect the ISP programmer.
6. Connect the board through USB.
7. Upload a simple Blink sketch.

## Educational Flow

For classroom use, the bootloader step is a good opportunity to teach:

- The difference between firmware, bootloader and sketch.
- Why the ATmega328P needs a clock source.
- How reset, serial upload and ISP programming relate to each other.
- How a blank microcontroller becomes Arduino-compatible.

## Related Project

For a specialized bootloader-burning workflow, see [GimmeSoul](https://github.com/import-tiago/GimmeSoul).
