# Assembly Guide

This guide is intended for classroom assembly of the Senaino FT232 board.

## Reference Files

- Component placement reference: [../../assets/reference/senaino-ft232-components-silkscreen.png](../../assets/reference/senaino-ft232-components-silkscreen.png)
- Schematic PDF: [../../hardware/exports/senaino-ft232-schematic.pdf](../../hardware/exports/senaino-ft232-schematic.pdf)
- BOM: [bill-of-materials.md](bill-of-materials.md)

## Recommended Assembly Order

1. Inspect the PCB for scratches, broken traces or solder mask damage.
2. Solder the lowest-profile passive components first: resistors and small diodes.
3. Solder ceramic capacitors.
4. Solder the crystal.
5. Solder the IC socket for the ATmega328P-PU. Do not insert the microcontroller yet.
6. Solder LEDs, observing polarity.
7. Solder the electrolytic capacitor, observing polarity.
8. Solder the voltage regulator and power jack.
9. Solder pin headers.
10. Solder the USB connector.
11. Solder or inspect the FT232RL USB-to-serial IC.
12. Clean flux residue and visually inspect all joints.
13. Insert the ATmega328P-PU only after the power checks pass.

## Polarity Notes

| Part | What to check |
|---|---|
| D1, D2, D3 | Match the diode stripe with the board marking. |
| LED1, LED2, LED3 | Match anode/cathode orientation with the silkscreen. |
| C1 | Match the negative stripe on the capacitor with the negative pad. |
| U1 | Align pin 1/notch with the IC socket and board marking. |
| U3 | Confirm orientation before powering the board. |

## Soldering Notes

- Start with components that are mechanically easy to hold flat against the PCB.
- Keep solder joints shiny, conical and limited to the pad area.
- Avoid overheating the FT232RL and USB connector pads.
- Recheck for bridges around the FT232RL before connecting USB.
- Do not insert the ATmega328P-PU until the 5 V rail has been tested.

## Final Assembly Checklist

- No visible solder bridges.
- No loose component leads.
- USB connector mechanically firm.
- Power jack mechanically firm.
- Headers aligned vertically.
- ATmega328P-PU inserted with correct orientation.
- Board passes the electrical tests in [testing.md](testing.md).
