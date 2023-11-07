# Azoteq Proxsense (TPSXX) VIK module

## Overview

This is a VIK module made to add a VIK connector to the [Azoteq Proxsense (TPSXX)](https://www.azoteq.com/images/stories/pdf/proxsense_i2c_trackpad_datasheet.pdf)(e.g. 43, 65) trackpads.

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
| SPI used for SPI only   | Strongly recommended    | :x:                |
| Uses: I2C               | Optional                | :heavy_check_mark: |
| I2C used for I2C only   | Strongly Recommended    | :heavy_check_mark: |
| I2C pull ups            | Required                | :heavy_check_mark: |
| Uses: RGB               | Optional                | :x:                |
| Uses: Extra GPIO 1      | Optional                | :x:                |
| Uses: Extra GPIO 2      | Optional                | :x:                |
| Standard PCB Size/Mount | Strongly recommended    | :x:                |

## PCB images

### horizontal fpc

![pcb front](horizontal-fpc/images/azoteq-tps-module-front.png)

![pcb back](horizontal-fpc/images/azoteq-tps-module-back.png)

### vertical fpc

![pcb front](vertical-fpc/images/azoteq-tps-module-front.png)

![pcb back](vertical-fpc/images/azoteq-tps-module-back.png)

#### assembled vertical

![assembled-vertical-1](vertical-fpc/images/assembled-vertical-1.jpg)

![assembled-vertical-2](vertical-fpc/images/assembled-vertical-2.jpg)

