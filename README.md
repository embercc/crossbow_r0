# crossbow_r0
It is an XXYY cross-gantry 3d printer.

The first prototype got 3:21 speedboatrace score, and the 5th(by score), 3rd(by machine/ID), 1st(all machines with direct drive extruders) on the rank list.

* speedboatrace video: 
  * https://youtu.be/H7nYXnaKUYE
* speedboatrace leaderboard (ember_cc#3959):
  * https://docs.google.com/spreadsheets/d/1lFiJi-X3Xm3hh3I9Ty9dfACMiBWxHFAOUeiU1km9m6I/edit#gid=106736391

The final design is underway.

## Main Feature
* XY system
    * Frame size 300x300
    * Full movement range (always larger than heated bed size): 170x170. 
        * An aluminum heated bed of 150x150 or 180x180 is recommended.
    * nema14 55mm or 60mm stepper x4 (voron v0 xy stepper)
    * Designed from sketch and aluminum CNC oriented.
    * maximum 140k mm/s^2 @ 600mm/s with TMC2209 24V (tested)
    * maximum 160k mm/s^2 @ 600mm/s with TMC5160 55V (tested, nema14 is not as powerful as expected, but way far enough for daily fast printing)
* Z: Voron 2.4 Z architecture (not ready)
    * "*belt-driven 4Z lifting the heated bed*" seems weird but works fine and can reach 20000mm^2/s @ 60mm/s, so this architecture is keeped in the project.
* No electronics bay. 
    * As my testing platform, the electronics changes frequently. 
    * I placed some aluminum extrusions at the left and right and bottom to mount PSU and MCU boards and RPIs.
* No full enclosure.

## 3D Model Link
* https://a360.co/3otfhes 
  * This is the online preview for those who do not have fusion360 installed. The f3d file is free to be downloaded.
* https://a360.co/3nV5nW3
  * Latest work.

## Misc
* Z system is not ready.
* The whole project is overkilled for daily use, but it is just good enough as my testing platform.
* I am not planning to build a BOM, *someone can count bolts and nuts by himself*.
* ABS-printed project is deprecated because the CNC version is WAY better. 
    * But you will find it's easy to enforce models to be stronger enough, and then print with ABS.
