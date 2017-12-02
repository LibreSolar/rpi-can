# Libre Solar CAN interface for Raspberry Pi (Zero W)

**Caution:** Developed using nightly build of KiCAD because of several nice features. Unfortunately, the files are not compatible with the current stable version, but a new compatible stable release (v5) of KiCad is expected soon.

## CAN to Wifi Gateway

This interface PCB allows to read data from the CAN bus connecting the Libre Solar components. So the Raspberry Pi can be used as a gateway to IoT applications and energy monitoring (e.g. using Open Energy Monitor).

![Raspberry Pi CAN interface PCB](CAN_RPi-ZeroW.png)

## Features:
- CAN interface using MCP2515 controller and TJA1042T/3 transceiver
- Power supply of Raspberry Pi via bus connector (RJ45)

