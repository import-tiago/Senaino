# Senaino

[![Hardware](https://img.shields.io/badge/hardware-open%20source-2f855a.svg)](LICENSE)
[![Variant](https://img.shields.io/badge/variant-FT232-blue.svg)](hardware/eagle)
[![Status](https://img.shields.io/badge/status-finished-brightgreen.svg)](CHANGELOG.md)
[![License](https://img.shields.io/badge/license-CERN--OHL--S--2.0%20%2B%20CC--BY--SA--4.0-lightgrey.svg)](LICENSE)

Senaino is an educational microcontroller board inspired by the Arduino UNO and adapted for technical training at SENAI. It was designed to help students practice soldering, electronics, bootloader recording and embedded programming with components that are easy to source in Brazil.

![Senaino FT232 assembled board](assets/images/senaino-ft232-mounted-board.jpg)

## Overview

The goal was not only to make an Arduino-compatible board, but to create a reproducible hardware kit that could be fabricated, assembled and tested by students in a classroom or lab environment.

The work included schematic design, PCB layout, component selection, production files, assembly references, documentation and validation of the mounted board.

## Highlights

- Arduino UNO-inspired board based on the ATmega328P-PU.
- Through-hole component strategy for beginner-friendly soldering practice.
- USB-to-serial interface using FT232RL on the main version.
- 16 MHz clock, 5 V regulation and familiar Arduino-style headers.
- Open hardware files for Eagle, Gerber fabrication, schematic export and BOM.
- Dedicated assembly, testing, driver and bootloader documentation.

## Repository Map

```text
assets/
  images/          Project photos and workshop/gallery images.
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
- Schematic PDF: [hardware/exports/senaino-ft232-schematic.pdf](hardware/exports/senaino-ft232-schematic.pdf)
- Gerber package: [hardware/gerbers/ft232-v1.0](hardware/gerbers/ft232-v1.0)
- BOM spreadsheet: [hardware/bom/senaino-ft232-bom.xlsx](hardware/bom/senaino-ft232-bom.xlsx)
- BOM CSV: [hardware/bom/senaino-ft232-bom.csv](hardware/bom/senaino-ft232-bom.csv)

## Board Variants

The `main` branch documents the FT232 version. A lower-cost CH340 version is available in the [`CH340`](https://github.com/import-tiago/Senaino/tree/CH340) branch.

| Variant | USB-serial IC | Main advantage | Recommended use |
|---|---|---|---|
| FT232 | FT232RL | Traditional and widely documented | Original classroom version |
| CH340 | CH340G | Lower component cost | Cost-sensitive production |

## Gallery

| | | |
|---|---|---|
| ![](assets/images/workshop-01.jpg) | ![](assets/images/workshop-04.jpg) | ![](assets/images/workshop-03.jpg) |
| ![](assets/images/workshop-02.jpg) | ![](assets/images/workshop-06.jpg) | ![](assets/images/workshop-05.jpg) |
| ![](assets/images/workshop-07.jpg) | ![](assets/images/workshop-08.jpg) | ![](assets/images/workshop-09.jpg) |

## Credits

Senaino was designed by Tiago Silva for educational use with [SENAI](https://www.sp.senai.br/) students. The board is inspired by the Arduino UNO reference design and keeps the educational spirit of open hardware.

## Citation

Citation metadata is available in [CITATION.cff](CITATION.cff). For DOI-based citation, archive a GitHub release through Zenodo after enabling the repository in Zenodo.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

The hardware design files are licensed under CERN-OHL-S-2.0. Documentation, images and educational material are licensed under CC BY-SA 4.0. See [LICENSE](LICENSE) and [docs/licensing.md](docs/licensing.md).
