# Nexus-Hackpad
  Nexus Pad is a 9-key macro pad with a rotary encoder and an OLED, with the switches illuminated by LED backlighting! It is made for compact keyboard gaming, specifically Valorant, and, in the future, a Home Control Panel for smart devices; it functions using QMK firmware.

## Features:
- 9 MX-Style switches
  
- Rotary Encoder
  
- 0.91 inch, 128x32 OLED Screen
  
- 9 SK6812 Mini-E LEDs
  
- 70mm x 100mm Custom PCB
  
- 2 Part Custom Case
  
- All brought together with the Seeed XIAO RP2040 using QMK firmware
  
## CAD Model:
  It is made with a sandwich-style mount, using supports to elevate the PCB so the USB port can fit, and the switches and everything else have the necessary tolerance. 

  The PCB is sandwiched between the bottom case, which has the supports, and the top plate, all fastened with M3 Heat Inserts and screws.
Additionally, I rounded everything for moderate viewing angles for the OLED and a more aesthetic look.


<img width="1338" height="961" alt="Screenshot 2026-07-10 at 6 52 28 PM" src="https://github.com/user-attachments/assets/a9d91f8d-a52d-40ac-97c6-9b047e9ab322" />

<p align="center">Exploded View:</p>

<img width="1290" height="1172" alt="Screenshot 2026-07-10 at 6 53 29 PM" src="https://github.com/user-attachments/assets/54afd137-218f-46f3-b3eb-b15a5b977a50" />

## PCB:
This is the PCB that connects all of my components and houses the brain of the Nexus Pad; it was all made in KiCAD.

<p align="center">Schematic:</p>

<img width="1641" height="753" alt="Screenshot 2026-07-10 at 6 45 49 PM" src="https://github.com/user-attachments/assets/06f4fecb-31e7-4683-85c9-6e8b8fd1f53d" />


<p align="center">PCB:</p>

<p align="center">
  <img width="469" height="645" alt="Screenshot 2026-07-10 at 6 48 32 PM" src="https://github.com/user-attachments/assets/ad7bd397-7f33-42be-b779-46bce05811ae" />
</p>

## Firmware Overview:

The Nexus Pad uses QMK (https://qmk.fm/) to operate.

- Key Bindings
  - 4 for abilities in Valorant
  - A Left Shift to walk in Valorant
  - Another layer in the future will be added for productivity tools
  - Will include support for VIA in the future for more customizability!
- The rotary encoder can control the volume; the press function doesn't work.
- I plan for the OLED to show CPU and GPU temperatures in the future using plugins, but for now it just displays "Nexus Pad"
- The LEDs have three lighting effects: breathing, rainbow mood, and snake.

## BOM:
- 1x SEEED Xiao RP2040
- 9x 1N4148 DO-35 Diodes
- 9x MX-Style switches
- 9x DSA Keycaps
- 9x SK6812 MINI-E LEDs
- 1x EC11 Rotary Encoder
- 1x 0.91" 128x32 OLED Display
- 1x PCB
- 4x M3x16mm screws
- 4x M3x5mx4mm heatset inserts
- 1x Bottom case (3D Printed)
- 1x Top plate (3D Printed)












