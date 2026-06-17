# Production Files

The FT232 fabrication files are in [../hardware/gerbers/ft232-v1.0](../hardware/gerbers/ft232-v1.0).

## Available Files

| File | Purpose |
|---|---|
| `Senaino.top` | Top copper layer |
| `Senaino.bot` | Bottom copper layer |
| `Senaino.smt` | Top solder mask |
| `Senaino.smb` | Bottom solder mask |
| `Senaino.skt` | Top silkscreen |
| `Senaino.skb` | Bottom silkscreen |
| `Senaino.drd` | Drill data |
| `Senaino.dri` | Drill report/info |
| `Senaino.drl` | Drill rack/settings |
| `Senaino.gpi` | Gerber photoplotter information |

## Packages

- Open files: [../hardware/gerbers/ft232-v1.0](../hardware/gerbers/ft232-v1.0)
- ZIP package: [../hardware/gerbers/ft232-v1.0/senaino-ft232-v1.0-gerbers.zip](../hardware/gerbers/ft232-v1.0/senaino-ft232-v1.0-gerbers.zip)

## Fabrication Notes

Before ordering boards, open the Gerbers in a viewer and confirm:

- Board outline.
- Layer alignment.
- Drill positions.
- USB connector footprint.
- Silkscreen readability.
- Solder mask clearance.

Typical low-cost fabrication settings for this type of board are 2 layers, 1.6 mm FR-4 and 1 oz copper, but confirm the final specification with the selected manufacturer before ordering.
