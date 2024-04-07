# Qanba JCV8 square actuator mod

## Attribution

The following text must be included in any distribution of derivatives of this file. All Links must also be included.

Copyright 2024 [Hawkeye](https://github.com/CapnHawke)

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Changes from the original design:
 - list any changes you make here

##Summary

The Qanba JCV8 is a lever that uses Cherry Speed Silver switches. The stems of the switches are narrow, and the spacing between the switches is wide. The actuator included with the joystick is round. As a result, the actuator cannot depress two adjacent switches simultaneously, unless it travels very deep into the diagonal. On a Qanba square gate, for example, a diagonal input cannot be pressed unless the actuator is contacting the corner of the gate. Reaching diagonal inputs requires an extremely high level of precision and necessitates contacting the gate. This results in a less user-friendly experience. 

The actuator in this repository aims to fix this problem by changing out the round design for a square design. This square actuator is able to more easily depress two adjacent at the same time. As a result, diagonal inputs are greatly increased, making it much easier for a player to reach their diagonal inputs. 

Additionally, the inner diameter of this actuator is very slightly increased, meaning that it fits less tightly on the lever shaft. This allows the shaft to rotate without twisting the actuator, and keeps the actuator aligned perpendicular to the switch stems.

## Print instructions

- Printed on a Bambulabs P1S
- Bambu Lab P1S 0.4 nozzle
- Textured PEI Plate
- Bambu PLA

Object/Part Settings:
- Layer Height = 0.2mm
- Wall loops = 2
- Infill Density = 15%
- Support = yes
- Brim = Auto
- Outer wall speed = 200

Quality:
- Layer Height = 0.2mm
- Initial Layer Height = 0.2mm
- Default Line width = 0.42mm
- Initial Layer = 0.5mm
- Outer wall = 0.42mm
- Inner wall = 0.45mm
- Top Surface = 0.42mm
- Sparse infill = 0.45mm
- Internal solid infill = 0.42mm
- Support = 0.42mm

Seam:
- Seam position = Aligned
- Seam gap = 15%
- Wipe speed = 80%

Precision:
- Slice gap closing radius = 0.049mm
- Resolution = 0.012mm
- Arc fitting = yes
- X-Y hole compensation = 0mm
- X-Y contour compensation = 0mm

- Ironing type = no ironing
- Wall generator = Classic

Advanced:
- Order of walls = inner/outer
- Print infill first = unchecked
- Bridge flow = 1
- Thick bridges = unchecked
- Top surface flow ratio = 1
- Initial layer flow ratio = 1
- Only one wall on top surfaces = Top Surfaces
- Top area threshold = 100%
- Only one wall on first layer = unchecked
- Detect overhang walls = yes
- Avoid crossing wall = unchecked

Supports:
- Enable support = yes
- Type = normal(auto)
- Style = Default
- Threshold angle = 30
- On build plate only = unchecked
- Remove small overhangs = yes
- Raft layers = 0

## Visual guide information

Below is a render of the acutator.
![Squareish Actuator render](https://github.com/CapnHawke/Arcade-Addons/blob/main/Arcade-Addons/Lever%20mods/images/image.png)

Below is an example image of the actuator installed in a JCV8, prior to screwing the gate back on. 
![Actuator installed](https://github.com/CapnHawke/Arcade-Addons/blob/main/Arcade-Addons/Lever%20mods/images/IMG_7519.jpg)

