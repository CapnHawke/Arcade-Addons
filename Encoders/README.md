# FP BBB-H version 1.1

![rp2040_BBB-H-FP-v1.1](https://github.com/CapnHawke/Arcade-Addons/blob/main/Encoders/Assets/Completed%20board.jpg)
![rp2040_BBB-H-FP-v1.1 drawing](https://github.com/CapnHawke/Arcade-Addons/blob/main/Encoders/Assets/RP2040-BBB-H%20drawing.png)
---

## Attribution

The following text must be included in any distribution of derivatives of this file. All Links must also be included.

Copyright 2023 [TheTrain](https://github.com/TheTrainGoes) 
With revisions in 2024 by [Hawkeye](https://github.com/CapnHawke)

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Changes from the original design:
 - Added right angle pin headers to each through hole on the original board.
 - Added a decorative copper fill area with no assigned NET, useful for applying a logo.

## Summary

The RP2040 Basic Breakout Board is an excellent solution for users who are looking for a PCB that is compatible with 20-pin wiring harnesses which have become standard in the home arcade-stick market. The main feature for this remix is the right angle header, which gives users the ability to use 1x1 DuPont connectors or jumper cables, to access more features on the board with easy, readymade, solder free wiring that fits inside a very slim case. 

## Assembly

These boards are designed to be made and assembled by JLCPCB.  As such, you will find a folder called `Hardware files` that contains a copy of the three files needed to have these boards made by JLC PCB.  

Those files are:
- A gerber file for the design of the board
- A BoM file for the list of parts to be assembled
- A Pick and Place file (also called a CPL) for the placement of the parts in the BoM file

This design includes both SMD and through hole parts from JLCPCB.  There are additional costs associated with having through hole parts added to the board.  You can reduce overall costs by removing headers that are not needed for your specific application of the board.  This can be done in EasyEDA directly by choosing to exclude the part from the BoM before exporting the necessary files.

These boards have been designed to be fully assembled by JLCPCB.  You will not need to do any soldering or assembly of any kind, should you order a batch of them.  The only thing you will need to do is flash the boards with the most recent version of GP2040-CE and then test the boards.

Please note that these files are provided without warranty. The providers are not responsible for issues that arise from the manufacturing of these boards done through JLCPCB or any other manufacturer.  These board files have been ordered and tested for functionality. 

## How to order a board

All of the boards so far have been ordered though JLCPCB.  Due to minimum order numbers you would get five of these basic breakout boards.  Here are the steps to make your first order and what options I choose along the way.

1 - Go to JLCPCB.com<br/>

2 - Click on `Instant Quote`<br/>

3 - Click on `Add Gerber file` and choose the file named `Gerber_PCB-RP2040-BBB-H-FP-v1.1.zip` from the `Fabrication files` folder<br/>

4 - Choose the following options for the board:<br/>
- Base Material = FR-4<br/>
- Layers = 2<br/>
- Dimensions = (should auto-populate) 96.3 mm x 45.31 mm<br/>
- PCB Qty = (however large your run will be, minimum of 5)<br/>
- Product Type = Industrial/Consumer electronics<br/>
- Different Design = 1<br/>
- Delivery Format = Single PCB (note 1)<br/>
- PCB Thickness = 1.6<br/>
- PCB Color = (up to you)<br/>
- Silkscreen = (defaults to white for all except white boards which is black)<br/>
- Surface Finish = HASL(with lead)<br/>
- Outer Copper Weight = 1oz<br/>
- Via Covering = Tented<br/>
- Board Outline Tolerance = +/- 0.2mm (Regular)<br/>
- Confirm Production file = Yes (note 2)<br/>
- Remove Order Number = Yes (note 3)<br/>
- Flying Probe Test = Fully Test<br/>
- Gold Fingers = No<br/>
- Castellated Holes = No<br/>
- No advanced options<br/>

Note 1 - If ordering under 50 units you can use single PCB.  For orders of more than 50 units JLCPCB will require you to make a larger plate for them.  I have compared the costs of doing this for runs in the hundreds and there is only a very small decrease in price over ordering 50 single PCBs at a time.  Ordering the 50 single PCBs has the added bonus of coming as individual pieces which do not require additional processing like the plated ones will.

Note 2 - This adds around $1 to the total cost of the order and is 100% worth doing as it will allow you one last chance to catch any issues that may have popped up.

Note 3 - This adds a small cost to the boards but removes the JLCPCB order number.  If you are looking to make a run as cheap as possible you can leave this on and either let them place it on the board or add `JLCJLCJLCJLC` somewhere on the board in silk screen and they will place the order number there.

5 - Choose the following options for the PCB assembly
- PCBA Type = Economic (note 4)<br/>
- Assembly Side = Top Side<br/>
- PCBA Qty = (however large your run will be, minimum of 2)<br/>
- Tooling holes = Added by Customer<br/>
- Confirm Parts Placement = Yes (note 5)<br/>

Note 4 - Economic assembly is much cheaper on smaller batch runs of 10-30 units.  Standard assembly will yield less dead on arrival boards but is more expensive to have done.  On average I expect a 5-10% failure rate on the boards from JLCPCB so please factor that in when making your order.

Note 5 - This adds around $1 to the total cost of the order and is 100% worth doing as they will check the placement of all SMD parts and make any necessary changes or reach out if there are concerns.  I cannot stress enough that this is the best $1 you will spend for the peace of mind of not messing up an entire batch.

6 - Make sure you have read the terms and conditions of JLCPCB assembly service and then click on the `Confirm` button if you agree <br/>

7 - The Bill of Materials page will show you a render of the board without parts.  You can click the `NEXT` button here unless you see any issues with the board<br/>

8 - You will now have the option to upload two files:
- For the `Add BOM File` you will need to choose the `BOM_PCB-RP2040-BBB-H-FP-v1.1.csv` file that is located in the Fabrication files folder
- For the `Add CPL File` you will need to choose the `PickAndPlace_PCB-RP2040-BBB-H-FP-v1.1.csv` file that is located in the Fabrication files folder<br/>
Once these two files have been uploaded you can press the `Process BOM & CPL` button.

9 - You will now see a list of components that will be used to assemble the boards.  If there are not listed issues here you can click on the `NEXT` button. (note 6), (note 7)

Note 6 - You can also use this page to omit parts from the assembly.  This can primarily be used to not include specific headers or the screw terminals.  Please only do this if you understand what you are doing as omitting main parts of the design will lead to non-functioning boards.  We are not responsible for any boards that are non-functioning. 

Note 7 - We have spent extensive time to ensure that the parts chosen will work for this board.  If there are any parts that are out of stock, or you get warnings about anything we would recommend you not proceed unless you understand how to find replacement parts.  If you are unsure, please feel free to join up in the Discord and ask us.  It is not uncommon for JLCPCB to have part shortages.  Most of the parts listed here come back in stock in a few days.  If that is the case, you may need to wait to place your order until all needed parts are in stock.

10 - There will now be a render of the board with parts on the Component Placements page.  Check this page to make sure that all parts are in the correct spots and orientation.  We have ordered based on these files before and they are known good.  If all looks well press the `NEXT` button. (note 8)

Note 8 - Please note that we are not responsible for boards made by JLCPCB or any other manufacturer that do note work.

11 - The quote & order page will give you a breakdown of the costs associated with the boards and assembly parts based on the quantity you have chosen. This does not include shipping.  Shipping will be calculated at a further step. 
- For Product Description I typically choose `Other` `Other` and type in `Controller board`.

If all looks well here you can click on the `SAVE TO CART` button.

12 - The `Secure Checkout` process will be different based on your location in the world.  We recommend researching your shipping options to choose the one that is right for your application. 


## How to upload firmware

If uploading the firmware before assembly you can hold the BootSel button on the Pico and plug the device into your computer.  It will show up as an external device.  You can download a copy of the necessary firmware files from the OpenStick Community GitHub repository. [A link to firmware Version 0.7.10 is provided here](https://github.com/OpenStickCommunity/GP2040-CE/releases/tag/v0.7.10). Copy the `GP2040-CE_0.X.X_RP2040AdvancedBreakoutBoardPassthrough.uf2` file to it and wait for the device to disconnect after copying completes.  

If uploading the firmware after assembly plug the Pico into your computer and quickly press the BootSel button twice on the Pico Basic Breakout Board.  You should see an external device show up on your computer.  Copy the `GP2040-CE_0.X.X_RP2040AdvancedBreakoutBoard.uf2` file to it and wait for the device to disconnect after copying completes.  

If something goes wrong and you want to upload the firmware again (or if you have tested out the configuration tool and made a mistake) you can enter BootSel mode via either of the methods above and drag over the included `flash_nuke.uf2` file.  This file will take a moment to write to the Pico, once completed you will see the device disconnect and then re-connect as an external device.  After it has shown up again you can copy the same `GP2040-CE_0.X.X_RP2040AdvancedBreakoutBoardPassthrough.uf2` firmware over to it again.

## How to add your own logo

Open the folder `Design files` and download the provided .json file. Load the file into EasyEDA. Navigate to your "Layers and Objects" pane and ensure that you are working on the TopLayer. Delete the image of the Frame Perfect Logo. Then, in your "Layers and Objects" pane, and select "TopSolderMaskLayer" and delete the image of the Frame Perfect Logo on top solder mask as well. 

While still working in the Top Solder Mask layer, navigate to the "Place" dropdown menu and select `Place > Image`. Import your own image into the design, and set it in the area designated for the logo. Copy the placed image and onto the top layer. Review both copies of the new logo to ensure that all the placement data is matching, including X and Y location, height, and width.

## Donations

Consider making a donation to the OpenStick Community! Every part of their project is open source, from the GP2040-CE firmware to the original Pico Fighting Board design and also the RP2040 Basic Breakout Board design.  

Donations are not necessary but always welcome!  TheTrain will typically use donations to pay for Discord boosts and try out new designs or sending boards to people for testing, iterations and helping people get board setups that might not be in an economic position to get one themselves.

https://www.paypal.com/donate/?hosted_button_id=2JMTZVCGLDYC2

## Revision History

v5.4E
- Initial design

Remixes:
BBB-H FP v1.1
- Added right angle headers
- Added decorative copper fill area for logo

## Disclaimer
These files and instructions are provided as-is, and without warranty. Your results may vary, and by using these files and instructions, you assume the risks associated with that activity. 