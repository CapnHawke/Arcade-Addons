# PCB Adapter Mount Designed for ROS Core v1.x arcade controllers

## Attribution

The following text must be included in any distribution of derivatives of this file. All Links must also be included.

Based on the [RP2040BB Mount Rev 1](https://github.com/CapnHawke/Arcade-Addons/blob/main/PCB%20Files/RP2040BB%20Mount%20Rev%201.stl) from [Hawkeye](https://github.com/CapnHawke)

Copyright 2024 [Hawkeye](https://github.com/CapnHawke)

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Changes from the original design:
 - Frame Perfect branding and design removed
 - 3mm holes added, centered over the corners of an 81.0mm x 30.146mm rectangle originating from the center of the mount.
 - Quarters of the mounting posts removed to accommodate space for original mounting posts in ROS CORE arcade controller.

List any additional changes you may have.

## Summary

This PCB mount was designed for the ROS Core. The official instagram for Roro Otaku Studios has showcased the ROS Core controller [here](https://www.instagram.com/roro_otaku_studio/p/C0KDqHdtrof/?img_index=1). The ROS Core is a premium quality all-metal enclosure. Modifications can be made to the controller by accessing the internals through a flush fitting bottom panel, held onto the body of the enclosure with powerful magnets. 

Some versions of the ROS Core have mounting posts intended to hold a PCB. The mounting posts are spaced in a rectangle having dimensions approximately 81.0mm x 30.15mm. Although there are PCBs fitting these dimensions, they do not match the popular form factor of a Brook Universal Fighting Board or the RP2040 Breakout Board series (advanced boards, basic boards, passthrough edition boards, screw terminal editions, etc.) developed by [TheTrain](https://github.com/TheTrainGoes) and hosted by the Open Stick Community in their [Hardware Repository](https://github.com/OpenStickCommunity/Hardware/tree/main). 

This PCB mount adapts the existing screw terminals in early versions of the ROS Core for use with this popular form factor. 

## Design

The adapter mount should be printed in the following orientation:

![ROS Core PCB Mount Adapter](https://github.com/CapnHawke/Arcade-Addons/blob/main/PCB%20Files/Images/ROS%20Core%20PCB%20mount%20adapter.png)

Once printed, The adapter mount may be installed either in right-side or upside-down configuration. In order to use a Brook 20-pin wiring harness, it will be necessary to install the PCB mount in an upside-down configuration pictured below:

![ROS Core Adapter Installed](https://github.com/CapnHawke/Arcade-Addons/blob/main/PCB%20Files/Images/ROS%20Core%20PCB%20Adapter%20mount.jpeg)

This will allow clearance for the wiring harness while also allowing the bottom plate of the enclosure to close flush.

## Assembly

The PCB mount will require M3 screws for all posts. M3*8 is suggested for all eight mounting holes. Pictured below is a completed PCB install with a 20 pin wiring harness:

![ROS Core PCB Installed](https://github.com/CapnHawke/Arcade-Addons/blob/main/PCB%20Files/Images/ROS%20Core%20PCB%20Adapter%20installed.jpeg)
 
Enjoy!

## Disclaimer
These files and instructions are provided as-is, and without warranty. Your results may vary, and by using these files and instructions, you assume the risks associated with that activity. 