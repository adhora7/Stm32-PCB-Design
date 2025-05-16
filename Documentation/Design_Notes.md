# Design Notes for STM32 PCB

## Overview  
This PCB is designed around the STM32F103C8T6 MCU with a two-layer layout, USB interface, and voltage regulation.

## Component Choices  
- **MCU:** STM32F103C8T6 chosen for its balance of performance and power consumption.  
- **Voltage Regulator:** AMS1117 3.3V for stable power supply from USB 5V.  
- **Crystal Oscillator:** 8 MHz crystal for clock stability.

## Routing Considerations  
- USB differential pairs routed with controlled impedance.  
- Decoupling capacitors placed close to MCU power pins for noise reduction.

## Future Improvements  
- Add optional debugging header.  
- Improve thermal relief for voltage regulator.

