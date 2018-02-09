## ReDuplicator-MK2sx

This project is a complete overhaul of the original Wanhao i3 with a few main objectives:
- Keep the core components of the printer while upgrading its structure.  
- Create maximum rigidity through a sturdy 3030 Aluminium extrusion frame. 
- Allow for future proofing and commonality of parts by basing all printed parts on the current Prusa MK2s files. 
- Reduce the weight of the X and Y carriages where possible to improve print speed and quality.

The Wanhao i3 is a fabulous printer, but lately, new generations of printers have begun pushing the boundaries. In comparison it has become apparent that the Wanhao has a dew deficiencies. Deficiencies which we will address in this project. The key improvements of this upgrade include:
- Much better rigidity through 3030 extrusions and metal brackets. Even with my or Azza’s z braces the printer was still susceptible to slight wobble, especially under twisting forces (pull left tower and push right tower). When moving the printer it would require constant releveling due these small movements. Now i can barely get any movement using full strength. 
- Comfortably increase Z height to ~200+mm
- Reduce noise. By not screwing the motors directly onto the metal frame, motor vibrations and noise is reduced significantly. 
- Move towards more standard Prusa files, but with added strength improvements.
- Modular hotend, This design allows for the hotend to be replaced easily by removing 4 few screws. I will be creating a Titan Aero mount and possibly a E3DV6 mount.
- Sturdier 4 bearing Prusa style X-gantry. Not sure if it was specific to my printer or a wanhao wide problem, but my X gantry always had a lot of wobble which may have been a source of printing artefacts.  
- Noticeably better print quality due to a combination of everything above. I am able to print faster with better quality.

![noooice](https://raw.githubusercontent.com/OmNomNomagon/ReDuplicator-MK2sx/master/Pics/1%20Glamor%20Shots/main.jpg) 

![Oh hai](https://raw.githubusercontent.com/OmNomNomagon/ReDuplicator-MK2sx/master/Pics/1%20Glamor%20Shots/side.jpg)

Sample of improved print quality. 0.24mm layer height @ 70mm/s (titan aero).

![boatyMcboat](https://raw.githubusercontent.com/OmNomNomagon/ReDuplicator-MK2sx/master/Pics/1%20Glamor%20Shots/boaty1.JPG)

This project will be maintained both at [github](https://github.com/OmNomNomagon/ReDuplicator-MK2sx) and at [thingiverse](https://www.thingiverse.com/thing:2686588).


## Table Of Contents

- [1. Bill Of Materials](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/1.--Bill-Of-Materials)
- [2. Printing Parts & Pre Assembly](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/2.-Printing-Parts-&-Pre-Assembly)
- [3. Base](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/3.-Base)
- [4. Begin The ZTower](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/4.-Begin-The-ZTower)
- [5.1 Hotend MK10 Original](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/5.1-Hotend-MK10-Original)
- [5.2 Hotend Titan Aero Upgrade](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/5.2-Hotend-Titan-Aero-Upgrade)
- [6. XAxis Gantry](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/6.-XAxis-Gantry)
- [7. Complete the ZTower](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/7.-Complete--the-ZTower)
- [8. YAxis](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/8.--YAxis)
- [9. Cabling](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/9.-Cabling)
- [9.1. Recommendations & Future Dev](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/wiki/9.1.-Recommendations-&-Future-Dev)


## Thanks and Acknowledgements
- [Prusa Research MK2s](https://github.com/prusa3d/Original-Prusa-i3) 
- [Datvr's Prusa MK2S-x](https://www.thingiverse.com/thing:1692666)
- [Thorped's excellent Wanhao Fan Duct ](https://www.thingiverse.com/thing:1246425)
- [Cyul's spool holder](https://www.thingiverse.com/thing:1635585)


## Changelog
1.0 - Initial Release

1.01 - Updated idler files with multiple z endstop mount points for upcoming Titan Aero upgrade. Sturdier cable cover box. Added 1Meter GT2 belt to BOM as the stock belt may not be long enough (can anyone confirm?)

1.02 - Updated the **Part Fan Bracket** to **Part Fan Bracket V1.1** The original doesn't align with the carriage plates properly. Please print the revised one.

1.03 - Uploaded a new Y Carriage Belt Holder. This one is based on the current MK3 design and is much easier to fix and tension.

1.04 - **X Gantry Idler 9MM V2** was missing the heat-sert insert holes to mount the cable box. Updated and fixed with **X Gantry Idler 9MM V3**. If you have already printed V2, you keep the part and manually drill 2x 4mm holes spaced 9mm wide and 6mm deep.
