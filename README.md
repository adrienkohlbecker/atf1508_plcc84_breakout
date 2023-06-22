# ATF1508 Breakout

Breakout board for Atmel's AFT1508 CPLDs in a through-hole PLCC-84 socket. The size is friendly for breadboard use, with two rows of holes left available on each side of the breadboard for wires to come in. A spot for an optional clock oscillator (SMD 7.5x5.0mm), connected to the first global clock input (GCLK1), is also provided.

## Board

![board-1](./images/board-1.png)

![board-2](./images/board-2.png)

![board-3](./images/board-3.png)

## Schematic

![schematic](./images/schematic.png)

## BOM

| Refs | Qty | Component | Description |
| ----- | --- | ---- | ----------- |
| C1 | 1 | 10u | Polarized capacitor, through hole D4.0mm P1.5mm |
| C2, C3, C4, C5, C6, C7, C8, C9, C10 | 8 | 100n | Unpolarized capacitor, 0805 SMD |
| J1 | 1 | Atmel-JTAG-10 | Atmel 10-pin JTAG connector, 2x5 IDC |
| J2, J3 | 2 | Conn_01x35 | Generic connector, single row, 01x35 |
| U1 | 1 | ATF1508AS-xJx84 | Microchip CPLD, in PLCC-84 through-hole socket |
| X1 | 1 | xMHz | Clock Oscillator, SMD 7.5x5.0mm (optional) |
