# Driver Notes

Do not store driver installers in the repository. Download USB-serial drivers from the official vendor pages when needed.

## FT232 Version

The FT232 version uses the FT232RL USB-to-serial converter.

- Official FTDI VCP drivers: https://ftdichip.com/drivers/vcp-drivers/
- On many modern Linux distributions, FTDI VCP support is already available through the kernel.
- On Windows, install the official VCP driver only when the board is not detected automatically.

## CH340 Version

The CH340 version uses the CH340G USB-to-serial converter.

- Official WCH CH341/CH340 driver page: https://www.wch-ic.com/downloads/CH341SER_EXE.html

## Repository Policy

Binary installers such as `.exe` files are intentionally not versioned here. Keeping drivers as external links avoids stale binaries, reduces repository size and makes the hardware documentation easier to audit.
