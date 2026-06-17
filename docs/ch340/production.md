# Production Files

The CH340 fabrication files are in [../../hardware/gerbers/ch340-v1.0](../../hardware/gerbers/ch340-v1.0).

## Available Files

| Path | Purpose |
|---|---|
| `CAMOutputs/GerberFiles/copper_top.gbr` | Top copper layer |
| `CAMOutputs/GerberFiles/copper_bottom.gbr` | Bottom copper layer |
| `CAMOutputs/GerberFiles/soldermask_top.gbr` | Top solder mask |
| `CAMOutputs/GerberFiles/soldermask_bottom.gbr` | Bottom solder mask |
| `CAMOutputs/GerberFiles/silkscreen_top.gbr` | Top silkscreen |
| `CAMOutputs/GerberFiles/silkscreen_bottom.gbr` | Bottom silkscreen |
| `CAMOutputs/GerberFiles/profile.gbr` | Board outline/profile |
| `CAMOutputs/DrillFiles/drill_1_16.xln` | Drill file |
| `CAMOutputs/Assembly/Senaino.txt` | Assembly export |
| `CAMOutputs/Assembly/PnP_Senaino_front.txt` | Front pick-and-place export |
| `CAMOutputs/Assembly/PnP_Senaino_back.txt` | Back pick-and-place export |

## Packages

- Open files: [../../hardware/gerbers/ch340-v1.0/CAMOutputs](../../hardware/gerbers/ch340-v1.0/CAMOutputs)
- ZIP package: [../../hardware/gerbers/ch340-v1.0/senaino-ch340-v1.0-gerbers.zip](../../hardware/gerbers/ch340-v1.0/senaino-ch340-v1.0-gerbers.zip)

## Fabrication Notes

Before ordering boards, open the Gerbers in a viewer and confirm:

- Board outline.
- Layer alignment.
- Drill positions.
- USB connector footprint.
- Silkscreen readability.
- Solder mask clearance.

Typical low-cost fabrication settings for this type of board are 2 layers, 1.6 mm FR-4 and 1 oz copper, but confirm the final specification with the selected manufacturer before ordering.
