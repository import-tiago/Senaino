# Design Decisions

Senaino CH340 was designed as an educational board, so the engineering choices prioritize teaching value, repairability, local sourcing and lower production cost.

## Arduino UNO-Inspired Format

The board follows the familiar Arduino UNO learning model because students can move from soldering and electrical testing to embedded programming without changing ecosystems.

## ATmega328P-PU

The ATmega328P-PU was selected because it is widely documented, classroom friendly and available in a DIP package. The removable DIP package also makes the board easier to inspect, replace and teach.

## Through-Hole Components

Most components are through-hole because the project is intended for soldering practice. This improves visibility during instruction and makes errors easier to diagnose.

## CH340G USB-Serial Interface

The CH340G version prioritizes lower cost and local availability. It adds a 12 MHz crystal for the USB-to-serial converter while preserving the same ATmega328P programming workflow.

## Separate Production And Teaching Artifacts

The repository keeps Eagle sources, Gerber files, schematic exports, BOM data and assembly references in separate folders so that each audience can find what they need:

- Students use assembly and testing documents.
- Instructors use BOM and troubleshooting notes.
- Fabricators use Gerbers and production notes.
- Portfolio reviewers use the README and design notes.
