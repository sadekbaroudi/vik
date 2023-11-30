# Trackpoint 2 piece module

## Overview

This is a VIK module made to connect the [trackpoint 2 piece](https://deskthority.net/wiki/TrackPoint_Hardware#2-piece_Trackpoint) breakout board.

Credit for images: from https://deskauthority.net/wiki/TrackPoint_Hardware

## Fabrication and BOM

For PCB fabrication, you can use the files in the production folder.

* gerbers.zip - the file used to fabricate the pcb
* bom.csv - used for PCBA. You can also use the part numbers in this file to look up the exact parts as [lcsc.com](https://lcsc.com)
* positions.csv - used for PCBA

Using the 3 files above, this has been tested at [jlcpcb.com](https://jlcpcb.com)


## VIK module certification

| Category                | Classification          | Response           |
| ----------------------- | ----------------------- | ------------------ |
| FPC connector           | Required                | :heavy_check_mark: |
| Breakout pins           | Recommended             | :x:                |
| Uses: SPI               | Optional                | :x:                |
| SPI used for SPI only   | Strongly recommended    | N/A                |
| Uses: I2C               | Optional                | :x:                |
| I2C used for I2C only   | Strongly Recommended    | :x:                |
| I2C pull ups            | Required                | :x:                |
| Uses: RGB               | Optional                | :x:                |
| Uses: Extra GPIO 1      | Optional                | :heavy_check_mark: |
| Uses: Extra GPIO 2      | Optional                | :heavy_check_mark: |
| Standard PCB Size/Mount | Strongly recommended    | :x:                |

## PCB images

![pcb front](images/trackpoint-module-front.png)

![pcb back](images/trackpoint-module-back.png)

## Trackpoint module images

![trackpoint module front](images/Trackpoint_2_piece_module_front.png)

![trackpoint module pinout](images/Trackpoint_2_piece_module_pinout.png)
