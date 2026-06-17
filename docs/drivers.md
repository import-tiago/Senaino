# Driver Notes

Do not store driver installers in the repository. Download USB-serial drivers from the official vendor pages when needed.

## CH340 Version

This branch uses the CH340G USB-to-serial converter.

- Official WCH CH341/CH340 driver page: https://www.wch-ic.com/downloads/CH341SER_EXE.html
- On Windows, install the official driver only when the board is not detected automatically.
- On Linux, the CH341/CH340 serial driver is commonly available through the kernel.

## FT232 Version

The FT232 version uses the FT232RL USB-to-serial converter and is available in the `main` branch.

- Official FTDI VCP drivers: https://ftdichip.com/drivers/vcp-drivers/

## Repository Policy

Binary installers such as `.EXE` files are intentionally not versioned here. Keeping drivers as external links avoids stale binaries, reduces repository size and makes the hardware documentation easier to audit.
