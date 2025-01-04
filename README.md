# Raspberry Pi Pico W KiCad Library

This library contains the schematic symbol, PCB footprint, and 3D model for the Raspberry Pi Pico W microcontroller board.

## Features
- Accurate schematic symbol with labeled GPIOs and power pins.
- Detailed PCB footprint with proper dimensions and mounting hole locations.
- 3D model for realistic visualization and enclosure design.

## Files Included
- **Symbol Library (`RaspberryPi_PicoW.kicad_sym`)**: Schematic symbol for the Raspberry Pi Pico W.
- **Footprint Library (`RaspberryPi_PicoW.pretty`)**: PCB footprint for the Raspberry Pi Pico W.
- **3D Model (`RaspberryPi_PicoW.step`, `RaspberryPi_PicoW.wrl`)**: 3D model for PCB visualization.

## How to Use
1. **Import Symbol Library**:
   - Open KiCad's Symbol Editor.
   - Go to `Preferences` > `Manage Symbol Libraries`.
   - Add `RaspberryPi_PicoW.kicad_sym` to your project or global library.

2. **Import Footprint Library**:
   - Open KiCad's Footprint Editor.
   - Go to `Preferences` > `Manage Footprint Libraries`.
   - Add the `RaspberryPi_PicoW.pretty` folder to your project or global library.

3. **Link 3D Models**:
   - Ensure the 3D models are in the same folder as the footprint library or update the 3D path in the footprint properties.

## License
This library is licensed under the MIT License. You are free to use, modify, and distribute it, but attribution is appreciated.

## Contributions
Feel free to submit issues or improvements via pull requests on the repository.

