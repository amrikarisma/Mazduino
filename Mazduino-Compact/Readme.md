# Mazduino Compact
![Assembled Mazduino ECU](v2.1/assembled.jpeg)

Mazduino Compact is compatible with firmware from rusEFI and can also be used with Speeduino.  
For tuning and configuration, you can use the Tuner Studio software.

## Downloads

### Latest Version (v2.3)
- [Download Schematic (PDF)](https://github.com/amrikarisma/Mazduino/blob/main/Mazduino-Compact/v2.3/schematic.pdf)
- [Interactive BOM v2.3](https://www.mazduino.com/ibom/compact-2-3-ibom.html)

### Other Versions
- [Interactive BOM v2.2](https://www.mazduino.com/ibom/compact-2-2-ibom.html)
- [Interactive BOM v2.0](https://www.mazduino.com/ibom/compact-2-0-ibom.html)
- [Interactive BOM v1.3](https://www.mazduino.com/ibom/compact-1-3-ibom.html)
*Interactive BOM for other versions will be available soon*

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

### v2.2
- Added high-side MOSFET for 12V switching control (alternator and other components requiring 12V switching)  

### v2.3
- Fixed MCU mapping for 12V battery input and knock sensor input  
- Optimized component selection and PCB layout for improved reliability and manufacturing efficiency  
- Added JST connector footprint for usb connector options  
- Added CR1220 battery holder footprint for real-time clock backup power  
