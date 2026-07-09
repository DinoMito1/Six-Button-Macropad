# Six-Button-Macropad

A simple macropad with 4 keys and a rotary encoder that uses KMK firmware

Good for playing simple games that only use a few buttons

<img width="1552" height="873" alt="Image" src="https://github.com/user-attachments/assets/abaedad7-0d3e-4c99-9165-da6212d7e490" />

## Features:

  + Fully 3D printed case
  + 6 Keys
  + A rotary encoder

## CAD:

The case was fully made in Fusion360

The top and bottom halves of the case fit together using four heatset inserts and four M3 Screws

<img width="987" height="687" alt="Image" src="https://github.com/user-attachments/assets/4e7b12c1-54ef-4f7c-ad17-ac67fe683c9c" />

## PCB:

The PCB for this macropad was designed in Kicad
Since there are only seven switches overall, there was no need to use a matrix and instead everthing is wired directly

#####  Schematic:
<img width="1337" height="623" alt="Image" src="https://github.com/user-attachments/assets/fafbf6f7-f3d9-4649-af28-21d6bb6cd32c" />
  
#####  PCB:
<img width="1247" height="677" alt="Image" src="https://github.com/user-attachments/assets/d2922a5b-6893-4705-98bf-45cdafede12c" />

## Firmware Overview:

The marcopad uses KMK Firmware

The rotary encoder adjusts the volume. Pressing will mute the volume
The six keys normally funtion as W, A, S, D, Z, and X, but they are pretty easy to change to fit your needs

## BOM:
Everything you'll need to make this
  + 1x case (2 3D printed parts)
  + 4x M3x5x4 heatset inserts
  + 4x M3x16 screws
  + 6x Cherry MX Switches
  + 6x Cherry DSA keycaps
  + 1x EC11 Rotary encoder
  + 1x XIAO RP2040
