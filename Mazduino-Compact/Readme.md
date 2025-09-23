# Mazduino Compact
![Assembled Mazduino ECU](v2.1/assembled.jpeg)

## Mazduino ECU Schematic v1.1
[Download Schematic (PDF)](https://github.com/amrikarisma/Mazduino/releases)

## Mazduino ECU BOM v1.1
[Download BOM](https://github.com/amrikarisma/Mazduino/releases)

## Changelog

### v1.0
- Initial testing

### v1.1
- Fixed USB-C to USB-C connection: rerouted 5.1k resistor to CC1 & CC2  
- Corrected silkscreen typo  

### v1.2
- Added low-current output for main relay  
- Added spare analog input  
- Added jumper footprint  

### v2.0
- Replaced connector with a 33-pin Yamaha automotive connector  
- Changed 12V capacitor size from 5x5 to 6x5  

### v2.1
- Added one high-current low-side MOSFET for boost/VVT/Idle2 control  
- Added direct knock sensor support using an op-amp IC  
- Supported two types of CAN bus transceivers: MCP2551 or TJA1051T/3  
- Added a dedicated connector for CAN bus communication  
- Added a pin header footprint for VBAT, allowing real-time clock backup with a 3.3V battery  
