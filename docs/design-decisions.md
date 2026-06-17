# Design Decisions

Senaino was designed as an educational board, so the engineering choices prioritize teaching value, repairability and local sourcing.

## Arduino UNO-Inspired Format

The board follows the familiar Arduino UNO learning model because students can move from soldering and electrical testing to embedded programming without changing ecosystems.

## ATmega328P-PU

The ATmega328P-PU was selected because it is widely documented, classroom friendly and available in a DIP package. The removable DIP package also makes the board easier to inspect, replace and teach.

## Through-Hole Components

Most components are through-hole because the project is intended for soldering practice. This improves visibility during instruction and makes errors easier to diagnose.

## USB-Serial Interface

The FT232RL version prioritizes a traditional and well-documented USB-to-serial interface. The CH340G variant exists as a lower-cost alternative when production budget is more important.

## Separate Production And Teaching Artifacts

The repository keeps Eagle sources, Gerber files, schematic exports, BOM data and assembly references in separate folders so that each audience can find what they need:

- Students use assembly and testing documents.
- Instructors use BOM and troubleshooting notes.
- Fabricators use Gerbers and production notes.
- Portfolio reviewers use the README and design notes.
