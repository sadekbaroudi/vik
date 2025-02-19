# Dilemma keyboard

This design is for the [dilemma keyboard](https://github.com/Bastardkb/Dilemma/tree/features/dilemma_3x0) by [Quentin](https://github.com/Bastardkb).

Git repository and branch reviewed:
https://github.com/Bastardkb/Dilemma/tree/features/dilemma_3x0/3x5_3

Notes:
* This keyboard requires a Type B fpc cable, instead of a Type A.
* If connecting an LCD to the keyboard with the breakout pins, you cannot use the SPI MOSI function through VIK on that half

## Controller pcb certification

| Category                 | Classification          | Response           |
| -----------------------  | ----------------------- | ------------------ |
| FPC connector            | Required                | :heavy_check_mark: |
| Breakout pins            | Recommended             | Partial            |
| Supplies: SPI            | Required                | :heavy_check_mark: |
| Supplies: I2C            | Required                | :heavy_check_mark: |
| I2C on main PCB          | Discouraged             | :x:                |
| I2C pull ups             | Informative             | 4.7k               |
| Supplies: RGB            | Required                | :heavy_check_mark: |
| Supplies: Extra GPIO 1   | Required                | Digital only       |
| Supplies: Extra GPIO 2   | Required                | Digital only       |
