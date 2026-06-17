# Bill Of Materials

This is the human-readable BOM for the Senaino FT232 version. The spreadsheet version is available at [../hardware/bom/senaino-ft232-bom.xlsx](../hardware/bom/senaino-ft232-bom.xlsx), and the CSV version is available at [../hardware/bom/senaino-ft232-bom.csv](../hardware/bom/senaino-ft232-bom.csv).

| Qty | Parts | Description | Value | Package |
|---:|---|---|---|---|
| 1 | R2 | PTH resistor | 150 ohm +/-5% | CR25 1/4 W |
| 3 | R1/R3/R4 | PTH resistor | 330 ohm +/-5% | CR25 1/4 W |
| 2 | R6/R7 | PTH resistor | 1 kohm +/-5% | CR25 1/4 W |
| 1 | R5 | PTH resistor | 10 kohm +/-5% | CR25 1/4 W |
| 5 | C2/C3/C4/C7/C8 | PTH ceramic capacitor | 100 nF x 50 V | Disc |
| 2 | C5/C6 | PTH ceramic capacitor | 22 pF x 50 V | Disc |
| 1 | C1 | PTH electrolytic capacitor | 100 uF x 35 V | Radial |
| 1 | D1 | PTH rectifier diode | 1N4007 | DO-41 |
| 1 | D2 | PTH Schottky diode | BAT43 | DO-35 |
| 1 | D3 | PTH Zener diode | 1N4728 | DO-41 |
| 1 | LED1 | PTH LED | Green | 3 mm |
| 2 | LED2/LED3 | PTH LED | Yellow | 3 mm |
| 1 | Q1 | PTH crystal | 16 MHz | HC49/S |
| 1 | U1 | PTH microcontroller | ATmega328P-PU | DIP-28N |
| 1 | U1 | PTH IC socket | 28 pins | DIP-28N |
| 1 | U2 | SMD USB/serial converter | FT232RL | SSOP-28 |
| 1 | U3 | PTH voltage regulator | L7805CV | TO-220 |
| 1 | X1 | PTH power connector | Jack J4, 2.1 mm | 3 terminals |
| 1 | X2 | PTH USB connector | Female USB Type-B | PCB 90 degrees |
| 1 | - | PTH pin header | Female 180 degrees | 1x10 |
| 2 | - | PTH pin header | Female 180 degrees | 1x8 |
| 1 | - | PTH pin header | Female 180 degrees | 1x6 |

## Sourcing Notes

- Prefer through-hole components for the student assembly workflow.
- Keep extra resistors, LEDs and ceramic capacitors available during classes.
- Treat the FT232RL, ATmega328P-PU and USB connector as critical components.
- Confirm the USB-to-serial IC package before ordering replacement parts.
