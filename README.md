# Senaino CH340

[![Hardware](https://img.shields.io/badge/hardware-open%20source-2f855a.svg)](LICENSE)
[![Variant](https://img.shields.io/badge/variant-CH340-blue.svg)](hardware/eagle)
[![Status](https://img.shields.io/badge/status-finished-brightgreen.svg)](CHANGELOG.md)
[![License](https://img.shields.io/badge/license-CERN--OHL--S--2.0%20%2B%20CC--BY--SA--4.0-lightgrey.svg)](LICENSE)

Senaino CH340 is the lower-cost USB-to-serial variant of the Senaino educational microcontroller board. It keeps the same classroom goal as the FT232 version: helping SENAI students practice soldering, electronics, bootloader recording and embedded programming with components that are easy to source in Brazil.

![Senaino CH340 assembled board](assets/images/senaino-ch340-mounted-board.jpg)

## Overview

This branch documents the CH340G variant. The main engineering difference is the USB-to-serial interface: this version uses a CH340G instead of the FT232RL used by the main branch. That makes the board more cost-sensitive while preserving the educational workflow.

The goal was not only to make an Arduino-compatible board, but to create a reproducible hardware kit that could be fabricated, assembled and tested by students in a classroom or lab environment.

The work included schematic design, PCB layout, component selection, production files, assembly references, documentation and validation of the mounted board.

## Highlights

- Arduino UNO-inspired board based on the ATmega328P-PU.
- CH340G USB-to-serial interface for a lower-cost production option.
- 16 MHz ATmega328P clock plus 12 MHz CH340G clock.
- Through-hole component strategy for beginner-friendly soldering practice.
- Open hardware files for Eagle, Gerber fabrication, schematic export and BOM.
- Dedicated assembly, testing, driver and bootloader documentation.

## Repository Map

```text
assets/
  images/          Project photos.
  reference/       Visual references for assembly.

docs/
  assembly-guide.md
  bill-of-materials.md
  bootloader.md
  design-decisions.md
  drivers.md
  production.md
  testing.md
  variants.md

hardware/
  bom/             Spreadsheet and CSV bill of materials.
  eagle/           Original Eagle schematic and board files.
  exports/         Schematic image/PDF exports.
  gerbers/         Fabrication files.
```

## Documentation

- [Assembly guide](docs/assembly-guide.md)
- [Bill of materials](docs/bill-of-materials.md)
- [Bootloader notes](docs/bootloader.md)
- [Citation and DOI guide](docs/citation.md)
- [Design decisions](docs/design-decisions.md)
- [Driver notes](docs/drivers.md)
- [License notes](docs/licensing.md)
- [Production files](docs/production.md)
- [Testing checklist](docs/testing.md)
- [Board variants](docs/variants.md)

## Hardware Files

- Eagle schematic: [hardware/eagle/Senaino.sch](hardware/eagle/Senaino.sch)
- Eagle board: [hardware/eagle/Senaino.brd](hardware/eagle/Senaino.brd)
- Schematic PDF: [hardware/exports/senaino-ch340-schematic.pdf](hardware/exports/senaino-ch340-schematic.pdf)
- Gerber package: [hardware/gerbers/ch340-v1.0](hardware/gerbers/ch340-v1.0)
- BOM spreadsheet: [hardware/bom/senaino-ch340-bom.xlsx](hardware/bom/senaino-ch340-bom.xlsx)
- BOM CSV: [hardware/bom/senaino-ch340-bom.csv](hardware/bom/senaino-ch340-bom.csv)

## Board Variants

The `CH340` branch documents this lower-cost version. The FT232 version is available in the [`main`](https://github.com/import-tiago/Senaino/tree/main) branch.

| Variant | USB-serial IC | Main advantage | Recommended use |
|---|---|---|---|
| FT232 | FT232RL | Traditional and widely documented | Original classroom version |
| CH340 | CH340G | Lower component cost | Cost-sensitive production |

## Credits

Senaino was designed by Tiago Silva for educational use with [SENAI](https://www.sp.senai.br/) students. The board is inspired by the Arduino UNO reference design and keeps the educational spirit of open hardware.

## Citation

Citation metadata is available in [CITATION.cff](CITATION.cff). For DOI-based citation, archive a GitHub release through Zenodo after enabling the repository in Zenodo.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

The hardware design files are licensed under CERN-OHL-S-2.0. Documentation, images and educational material are licensed under CC BY-SA 4.0. See [LICENSE](LICENSE) and [docs/licensing.md](docs/licensing.md).
