![PFCT MX 3 Aux board](https://github.com/CapnHawke/Arcade-Addons/blob/main/Button%20mods/Open%20Source%20Button%20solutions/AllFightSticks%20Aux%20Panel%20PCB/Images/PFCT%203aux%20design%20render.png)
![PFCT MX 3 Aux install](https://github.com/CapnHawke/Arcade-Addons/blob/main/Button%20mods/Open%20Source%20Button%20solutions/AllFightSticks%20Aux%20Panel%20PCB/Images/Install.jpg)

## Attribution

The AllFightSticks "PFCT 3Aux" mod is based on OSBMX by TheTrain and Rana Labs - https://ko-fi.com/ranalabs/

Copyright © 2023 [TheTrain](https://github.com/TheTrainGoes) and [Rana Labs](https://ko-fi.com/ranalabs/) Copyright @ 2024 [CapnHawke](https://github.com/CapnHawke) for derivative portions of this design.

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
3q13w4wq
Any derivatives of PFCT 3Aux should provide attribution to the original source material by TheTrain and RanaLabs in accordance with the OSBMX Creative Commons 4.0 license, and should comply with all other terms and conditions of that license, including listing the OSBMX repository in sales pages, etc. Attribution to this revision should also be provided.

Changes from the original design:
 - The PCB has been enlarged to accommodate three buttons instead of one, and traces have been drawn to a pin connector, which can be used to simplify wiring and assembly. 

[Licensed under CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

If you make further changes to this design, please list them here: 
  - list any changes you make here

---
Summary:

The PFCT MX 3 Aux is based on the OSBMX 24 buttons from the TheTrain and RanaLabs.

OSBMX 24 allows for a compact all-in-one button to be constructed and placed securely into a small form factor case (total of 2.00mm thick). The PFCT MX 3 Aux is a one-board solution designed to minimize user-performed assembly steps, and to allow for easy, clean wiring. 

A massive thank you to TheTrain and RanaLabs for making the OSBMX button housings and original files, and to TheTrain for consulting on parts selection and building advice.


---

Board design choices:

The center of each MX switch is located 35mm from the center of the next switch in the series. This allows three 24mm buttons to be installed on a panel, in a line, with 11mm of clearance between each mounting hole. This configuration is found on several AllFightSticks enclosures. As of the time of publication, it should fit on AFS cases which are 12" and larger. There are several unique features of the PCB used for these buttons.  

A right angle 5-pin JST-NH connector was chosen for this project because of the easy commercial availability of wiring harnesses that are compatible with this connector. The needed connector is the same as a Sanwa JLF/JLX lever and is also used by many Seimitsu and Hori levers. There are two ground pins, meaning that a user can expand their ground loop by using the spare ground wire to extend their ground daisy chain. If the extra ground wire is not desired, the user can simply snip the wire off the wiring harness.

---

Assembly:

Solder the three hot swap socket on. After the board is assembled, button housings and locking rings should be installed directly into the enclosure/controller and oriented such that the switch holes and screw holes are aligned and the PCB may be installed. The PCB assemblage may then be aligned with button housings and screwed into place using six M2 screws. If necessary, locking rings can be loosely threaded until after the PCB assemblage is screwed into the button housings. Afterwards, the locking rings can be hand-tightened. Switches and plungers may then be installed from the outside of the controller.

Parts necessary for assembly:

1 x PFCT MX 3 Aux board<br/>
3 x MX hot swap socket (https://www.aliexpress.com/item/4001051840976.html)<br/>
6 x M2 5mm Hex Hexagon Socket Cap Head Self Tapping Screws (https://www.aliexpress.com/item/10000350027047.html)<br/>
1 x OOSBMX 24 housing<br/>
1 x OSBMX 24 plunger<br/>
1 x OSBMX 24 washer<br/>
3 x MX switch (3) (https://www.aliexpress.com/item/1005004679651313.html)<br/>
1 x Five pin JST-NH wiring harness, such as those used for a Sanwa JLF lever.

---

How to order a board:

All of the boards so far have been ordered though JLCPCB.  Please note that recently JLCPCB changed some of their prices for the PCB color, ensure you choose a color like black or green to get the lowest possible cost.

1 - Go to JLCPCB.com<br/>
2 - Click on `Instant Quote`<br/>
3 - Click on `Add Gerber file` and choose the file named `Gerber_PFCT-Mx-3-aux.zip`<br/>
4 - Choose the following options for the board:<br/>
- Base Material = FR-4<br/>
- Layers = 2<br/>
- Dimensions = (should auto-populate) 110 * 20 mm<br/>
- PCB Qty = as needed<br/>
- Product Type = Industrial/Consumer electronics<br/>
- Different Design = 1<br/>
- Delivery Format = Single PCB<br/>
- PCB Thickness = 1.6<br/>
- PCB Color = (up to you)<br/>
- Silkscreen = (defaults to white for all except white boards which is black)<br/>
- Surface Finish = HASL(with lead)<br/>
- Outer Copper Weight = 1oz<br/>
- Gold Fingers = No<br/>
- Confirm Production file = No<br/>
- Flying Probe Test = Fully Test<br/>
-  Castellated Holes = No<br/>
- Remove Order Number = as needed (If the order number is left on, it should be placed on a part of the board which will not be visible after final assembly)<br/>
- No advanced options<br/>

5 - Click on `SAVE TO CART`<br/>
6 - Go through checkout process, ensure to select economic shipping to keep costs low
7 - When prompted, upload the Bill of Materials (BOM) and Components Placement List (CPL, also known as "Pick and Place") files that can be found in this repository alongside the Gerber file.

---

How to order a button housing:

All of the button housings so far have been ordered though JLCPCB.  Due to the size of the buttons you can order a full sprue for a very small cost depending on the material you choose.  You will get the best quality out of PA12 nylon, but they are the most expensive.  If you are ordering in resin, several larger sprue configurations are available in the `other sprue configurations` folder hosted at the Hardware GitHub repository [here](https://github.com/OpenStickCommunity/Hardware/tree/main/3D%20Prints/OSBMX) hosted by the OpenStick Community.

1 - Go to JLCPCB.com<br/>
2 - Click on `Instant Quote`<br/>
3 - Click on `3D Printing` <br/>
4 - Click on `Add 3D files` and choose the file named `OSBMX 24 - Single Sprue.stl`<br/>
4 - Choose the following options for the board:<br/>
- 3D Technology = MJF (Nylon) (1)<br/>
- Material = PA12-HP Nylon (2)<br/>
- Color = Dyed Black<br/>
- Build Time = 72 hours<br/>
- Quantity = As needed (multiples of three recommended)<br/>
- Product Description = Anything you like<br/>
- 3D Remarks = "Please print facing flat down."<br/>

5 - Click on `SAVE TO CART`<br/>
6 - Go through checkout process, ensure to select economic shipping to keep costs low

(1) - These are best done in MJF (Nylon).  If you want to make cheaper buttons you can do them in SLA (Resin).  The sprues have been optimized for ordering in MJF (Nylon).  If you would like to order these in resin please check out some of the other files I have in here which have greater sized sprues.
(2) - PA12-HP Nylon is recommended due to finish and feel, although it is more expensive.  You can make these out of 9000R resin if you are looking to get a larger number for a lower cost, or want to experiment with doing dye jobs.