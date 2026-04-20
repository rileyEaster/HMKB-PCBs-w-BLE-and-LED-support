# HMBK70 PCB with BLE and LED

A PCB designed in KiCad based on the [nice!nano](https://nicekeyboards.com/nice-nano/) that enables LED and wireless functionality for custom builds that use a [HMKB70](https://heavymetalkeyboards.com/collections) chassis and Cherry style switches. 

## Overview

This project currently contains a single schematic and PCB file, supporting monochromatic LEDs. Wireless functionality has not yet been addressed. An unconventional layout, which uses 4 and 3 keys on the left and right of the space bar respectively, has been implemented used here. Note this if you plan to make any edits to the schematic for your own build. 

## Features

- Key switch matrix connected to the micro controller
- Footprints with holes for Cherry switches and 3mm, 3v LEDs
- Easy to adapt for other layouts or microcontrollers

## Project Files

- `HMKB70_Nicenano_LED.kicad_pro` — KiCad project file
- `HMKB70_Nicenano_LED.kicad_sch` — schematic file
- `kHMKB70_Nicenano_LED.kicad_pcb` — PCB layout file

## Status

- [x] Schematic for monochromatic LEDs
- [x] PCB precise layout
- [ ] Designs for solder mask
- [ ] Battery integration
- [ ] Wireless Functionality

## Intended Additions

- Full spectrum, adjustable RGB
- CAD models of the HMKB70 integrated into KiCad's 3D viewer