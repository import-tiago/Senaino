# Driver Notes

Do not store driver installers in the repository. Download USB-serial drivers from the official vendor pages when needed.

## FT232 Variant

The FT232 variant uses the FT232RL USB-to-serial converter.

- Official FTDI VCP drivers: https://ftdichip.com/drivers/vcp-drivers/
- On many modern Linux distributions, FTDI VCP support is already available through the kernel.
- On Windows, install the official VCP driver only when the board is not detected automatically.

## CH340 Variant

The CH340 variant uses the CH340G USB-to-serial converter.

- Official WCH CH341/CH340 driver page: https://www.wch-ic.com/downloads/CH341SER_EXE.html

## Repository Policy

Binary installers such as `.exe` files are intentionally not versioned here. Keeping drivers as external links avoids stale binaries, reduces repository size and makes the hardware documentation easier to audit.
