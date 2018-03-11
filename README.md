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

1.04 - **X Gantry Idler 9MM V2** was missing the heat-sert insert holes to mount the cable box. Updated and fixed with **X Gantry Idler 9MM V3**. If you have already printed V2, you can keep the part and manually drill 2x 4mm holes spaced 9mm wide and 6mm deep.

1.1 - Major Prusa MK3 Update. This updates an update of many of the original MK2s based parts to MK3 Based parts. This includes;
        - MK3 Based Part Cooling shroud and mount. It performs much better than the original Thorped based one. flawless @60 degree overhang with some sagging @70 degree overhang. The original would show artefacts [@60 degrees.](https://raw.githubusercontent.com/OmNomNomagon/ReDuplicator-MK2sx/master/Pics/9%20Titan/overhang.jpg). Almost comparable to the [Dii Cooler.](https://www.reddit.com/r/3Dprinting/comments/7kexdv/a_nearly_comprehensive_study_of_cooling_fans_and/) 
        - Much improved X Carriage. This uses the new [MK3 belt mounting method](https://raw.githubusercontent.com/OmNomNomagon/ReDuplicator-MK2sx/master/Pics/4%20Hotend/CarriageNew.jpg) which is much easier to install under tension. The whole extruder assembly can now also easily slide on and off the rods to greatly simplify installation and maintenance. 16mm M3 screws are used to secure the bearings. I've also made and tested changes which allow the extruder assembly to be built without heat-serts and can be substituted with M3 nylocks. NOTE: due to these changes the Rear carriage plate is NOT compatible with the existing Front extruder plate as the hole spacing has been changed. The New Front extruder plate must be used.
        - Front Extruder Plate. Better spacing around the hotend to improve the filament path. Updating Hole Spacing to be compatible with the new Rear Carriage Plate. Strengthened BLTouch mount. Increase spacing around heater block to reduce residual heat. Not compatible with old extruder plate.
        - X Axis Motor Mount. Incorporates the new MK3 design. Better Spacing to ensure a straighter belt path. Includes new MK3 tensioner to easily tension X belt. Requires M3nS Nut and 20mm M3 screw. (Enough tension can be applied by without the M3nS) Installation is similar to the Prusa instructions [here, steps 11-18.](http://manual.prusa3d.com/Guide/4.+Z-axis+assembly/509?lang=en)
        - as this project  contains dozens of files already, Older retired files are retired to the [Retired Versions directory in github](https://github.com/OmNomNomagon/ReDuplicator-MK2sx/tree/master/STLs%20Reduplicator%20Core%20Parts/Retired%20Versions)
        - Thank you!

