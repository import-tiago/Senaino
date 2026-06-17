# Board Variants

Senaino has two documented USB-to-serial variants in the `main` branch.

| Variant | USB-serial IC | Notes |
|---|---|---|
| FT232 | FT232RL | Original classroom version. |
| CH340 | CH340G | Lower-cost alternative kept in the same repository. |

## FT232 Version

The FT232 version is useful when the priority is a traditional USB-to-serial interface with broad documentation and known behavior.

## CH340 Version

The CH340 version is useful when production cost, local availability and USB-to-serial sourcing risk matter more than keeping the original FT232RL interface.

It also reduces the sourcing risk around FT232RL parts. ZeptoBars documented a real-vs-fake comparison of FT232RL dies and described counterfeit/protocol-compatible parts that behaved differently with FTDI driver updates: [FTDI FT232RL: real vs fake](https://zeptobars.com/en/read/FTDI-FT232RL-real-vs-fake-supereal).

## Choosing A Variant

| Situation | Recommended variant |
|---|---|
| Reference documentation and traditional FTDI workflow | FT232 |
| Classroom production with lower cost target | CH340 |
| Debugging with known FTDI tooling | FT232 |
| Bulk manufacturing where CH340 is easier to source or FT232 authenticity is uncertain | CH340 |
