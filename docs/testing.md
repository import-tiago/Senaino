# Testing Checklist

Use this checklist before giving a mounted board to a student or using it in class.

## Before Power

1. Inspect the board under good light.
2. Check continuity between GND points.
3. Confirm there is no short between 5 V and GND.
4. Confirm there is no short between VIN and GND.
5. Confirm diode and electrolytic capacitor orientation.
6. Confirm the ATmega328P-PU is not inserted for the first power test.

## Power Rail Test

1. Power the board from the DC jack or USB, according to the test setup.
2. Measure the regulated 5 V rail.
3. Confirm the power LED behavior.
4. Disconnect power immediately if the regulator overheats.
5. Insert the ATmega328P-PU only after the power rail is correct.

## USB-Serial Test

1. Connect the board through USB.
2. Confirm that the operating system detects a serial port.
3. If the serial port does not appear, check [drivers.md](drivers.md).
4. Open the serial port with the Arduino IDE or another serial terminal.
5. Confirm that reset and upload behavior are stable.

## Bootloader And Blink Test

1. Burn the bootloader using the notes in [bootloader.md](bootloader.md).
2. Select the Arduino UNO-compatible target in the programming environment.
3. Upload a Blink sketch.
4. Confirm the expected LED behavior.
5. Repeat USB reconnection to confirm the board enumerates consistently.

## Acceptance Criteria

- 5 V rail is stable.
- No short is detected after power cycling.
- USB serial port enumerates.
- Bootloader can be recorded.
- Blink sketch uploads successfully.
- Board resets correctly during upload.
