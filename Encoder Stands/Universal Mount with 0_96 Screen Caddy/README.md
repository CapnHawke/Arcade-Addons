# PCB Mount With Caddy for rear-facing 0.96" I2C screens

## Attribution

The following text must be included in any distribution of derivatives of this file. All Links must also be included.

Based on the [RP2040BB Mount Rev 1](https://github.com/CapnHawke/Arcade-Addons/blob/main/PCB%20Files/RP2040BB%20Mount%20Rev%201.stl) from [Hawkeye](https://github.com/CapnHawke)

Copyright 2024 [Hawkeye](https://github.com/CapnHawke)

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Changes from the original design:
 - Frame Perfect branding and design removed
 - Length and Width of mount slightly adjusted to improve tolerances, better match the size of the RP2040 Breakout Boards, and eliminate flex with screws inserted. 
 - Mounting holes expanded from M2.5 to M3
 - Surplus material removed
 - Size of stand-offs extended to 8.5mm from surface of mount, to allow space for DuPont and/or JST XH connector to be installed beneath I2C screen.

For the protruded screen version:
 - Size of stand-offs reduced to the surface of the mount.
 - 8.5mm of height added nearer to screen mount, to allow for installations in enclosures where space constraints may necessitate a smaller caddy for the screen. 

List any additional changes you may have.

## Summary

This PCB mount was designed to be installed in arcade stick enclosures with an acrylic top or a window. A caddy for a rear facing, I2C enabled, 0.96" OLED screen is included on the back side of the PCB mount. 

## Design

The PCB mount is tall enough to allow the user to attach a JST XH connector to striaght pin DuPont connectors on the back of the I2C screen, and to run a wire from there to Ground, VCC, SCL and SDA pins on the mounted PCB. 

This caddy was designed to be used with M3x25 screws or longer. The protruded screen version of this mount may use smaller screws if the user has another, preferred method of attaching the PCB mount to the enclosure.

## Assembly

M3 screws are recommended for all mounting posts. They should be at least M3x25 or longer. The screen mounts on the internal screw holes using M2x6 or longer. 

The following hardware is recommended for installation:
 - Four M3x25 screws or longer, depending on depth of acrylic or windowed mounting layer.
 - Four Mxx6 screws to mount an I2C screen.
 - An I2C screen such as those available [here](https://www.aliexpress.us/item/2251832770994631.html).
 - Suitable wiring, to attach the screen to a compatible PCB such as an [RP2040 Advance Breakout Board v5.6e](https://github.com/OpenStickCommunity/Hardware/tree/main/Boards/GP2040-CE Official Boards/RP2040 Advanced Breakout Board/RP2040 Advanced Breakout Board - Passthrough)

Enjoy!

## Disclaimer
These files and instructions are provided as-is, and without warranty. Your results may vary, and by using these files and instructions, you assume the risks associated with that activity. 