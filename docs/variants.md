# Board Variants

Senaino has two documented USB-to-serial variants.

| Variant | Branch | USB-serial IC | Notes |
|---|---|---|---|
| FT232 | `master` | FT232RL | Original version documented in this branch. |
| CH340 | `CH340` | CH340G | Lower-cost alternative available in the CH340 branch. |

## FT232 Version

The FT232 version is the main documented version in this repository. It is useful when the priority is a traditional USB-to-serial interface with broad documentation and known behavior.

## CH340 Version

The CH340 version is useful when production cost and local availability are more important than keeping the original USB-to-serial device.

## Choosing A Variant

| Situation | Recommended variant |
|---|---|
| Portfolio and reference documentation | FT232 |
| Classroom production with lower cost target | CH340 |
| Debugging with known FTDI tooling | FT232 |
| Bulk manufacturing where the CH340 is easier to source | CH340 |
