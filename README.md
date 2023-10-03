# Arduino 8x PCB Smart Charger/Discharger - Enhanced Version

## Original Project
Created by Brett Watt on 20/07/2018 Copyright 2018 - Under Creative Commons license 3.0:

This software is furnished "as is", without technical support, and with no warranty, express or implied, as to its usefulness for any purpose.

This is the Arduino 8x 18650 Smart Charger / Discharger Code

Current implementation: TP4056, Rotary Encoder KY-040 Module, Temp Sensor DS18B20 Ethernet Module W5500, Mini USB Host Shield (Barcode Scanner), LCD 2004 20x4 with IIC/I2C/TWI Serial, Discharge (MilliAmps and MillOhms)

Link: https://github.com/brettwatty/Arduino-8x-PCB-Smart-Charger-Discharger
Email: info@vortexit.co.nz Web: www.vortexit.co.nz


## Modification objectives
- Conversion of the system into a standalone device.
- Add of multiple charge/discharge cycles functionality for more accurate testing of cell capacity.
- Add cell revive mode for safely charging cells from deep discharge and testing their capacity.

## Status
- Removed the Ethernet module and the barcode scanner.
- Removal of unnecessary files.
- Changed menu layout and logic.
- Added multiple charge/discharge cycles functionality.
- Cell revive mode not finished. This mode toggles TP4056 while cells are not inserted and some safety checks are missing.
- TODO: temperature sensor not working.

Last revised and tested in 2020.
This Project is left unfinished due to time constraints and the availability of new ready consumer devices at a low price point.

## Libraries Used
- [Encoder_Polling.h](https://github.com/frodofski/Encoder_Polling/)
- [DallasTemperature.h, OneWire.h](https://github.com/milesburton/Arduino-Temperature-Control-Library)
- [LiquidCrystal_I2C.h](https://github.com/marcoschwartz/LiquidCrystal_I2C)

