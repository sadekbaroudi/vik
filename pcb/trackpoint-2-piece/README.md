# Trackpoint 2 piece module

## Overview

This is a VIK module made to connect the [trackpoint 2 piece](https://deskthority.net/wiki/TrackPoint_Hardware#2-piece_Trackpoint) breakout board.

The through holes should be used if connecting this to a controller that uses 5v logic. The VIK connector is assumed to be connecting to a 3.3v controller, so the logic levels are 3.3v.

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

## Credit

Thank you to crehmann for testing this module with their design of the following keyboard, clear instructions and images. This was monumentally helpful in getting this ironed out quickly:  
https://github.com/crehmann/TPS42  

Thanks to quappo for doing the research on existing solutions for trackpoint connectivity  

Thanks to Pete Johanson for adding the logic level conversion circuitry.  

Images: from https://deskauthority.net/wiki/TrackPoint_Hardware  
