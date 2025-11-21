# Mazduino Lite Edition v0.1

Mazduino Lite Edition is a compact ECU designed for **4-cylinder engines with full sequential injection and wasted spark ignition**. This lightweight version provides essential engine control features in a smaller form factor.

Mazduino Lite is compatible with firmware from rusEFI and can also be used with Speeduino.  
For tuning and configuration, you can use the Tuner Studio software.

## Specifications
- **Board Size**: 72mm x 74.7mm
- **Connector**: 33-pin Automotive Connector
- **Target Application**: 4-cylinder engines with full sequential injection and wasted spark ignition

## Preview
![Mazduino Lite Edition](v0.1/mazduino_lite.png)

## Features
- **Processor/MCU**: STM32F407
- **2 Channel Ignition** - Wasted Spark (Smart Coil/Coil On Plug/IGBT for Dumb Coil)
- **4 Channel Injector** outputs - Full Sequential Injection
- **2 Spare MOSFET** for Idle PWM/Boost/VVT/VTEC control
- **Analog Inputs**: CLT, IAT, MAP, TPS, O2 sensors
- **Digital Inputs**: CKP, CMP, VSS, Clutch
- **VR Conditioner Module Support** (Dual VR)
- **Low Side Outputs**: RPM, FAN, Fuel Pump, Main Relay, AC Compressor
- **Micro SD Card Support** for data logging via SPI
- **CANbus Communication** support
- **Compact Design** - Smaller footprint for space-constrained applications

## Downloads

### Latest Version (v0.1)
- [Download Schematic (PDF)](https://github.com/amrikarisma/Mazduino/blob/main/Mazduino-Lite/v0.1/Schematics.pdf)
- [Interactive BOM v0.1](https://www.mazduino.com/ibom/lite-0-1-ibom.html)

## Changelog

### v0.1 (Initial Release)
- Initial design and layout
- Compact 72mm x 74.7mm form factor
- 33-pin automotive connector
- 4-cylinder full sequential injection with wasted spark ignition
- 2-channel ignition and 4-channel injection
- Essential analog and digital inputs
- VR conditioner support
- CAN bus and SD card support

---

*This documentation will be updated as soon as possible... please wait.*
