# PER56 Scroll Ring with Cirque Trackpad and LEDs

## Overview

This is a VIK module designed to mount a [PER56 scroll ring](https://www.mouser.com/new/bourns/bourns-per56-incremental-ring-encoders/), with a 35mm [Cirque Trackpad](https://www.cirque.com/glidepoint-circle-trackpads) and optional WS2812B LEDs.

This was used to demonstrate a build for [vulpes minora](https://github.com/sadekbaroudi/vulpes-minora). See the repo for pictures.

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
| Uses: SPI               | Optional                | :heavy_check_mark: |
| SPI used for SPI only   | Strongly recommended    | :heavy_check_mark: |
| Uses: I2C               | Optional                | :x:                |
| I2C used for I2C only   | Strongly Recommended    | N/A                |
| I2C pull ups            | Required                | N/A                |
| Uses: RGB               | Optional                | :heavy_check_mark: |
| Uses: Extra GPIO 1      | Optional                | :heavy_check_mark: |
| Uses: Extra GPIO 2      | Optional                | :heavy_check_mark: |
| Standard PCB Size/Mount | Strongly recommended    | Large              |

## PCB images

![pcb front](images/per56-cirque-leds-module-front.png)

![pcb back](images/per56-cirque-leds-module-back.png)