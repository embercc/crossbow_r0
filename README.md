# crossbow_r0
It is an XXYY cross gantry 3d printer.

The first generation got 3:21 speedboatrace score, and the 4th on the ranklist.

* speedboatrace video: 
  * https://youtu.be/H7nYXnaKUYE
* speedboatrace leaderboard (ember_cc#3959):
  * https://docs.google.com/spreadsheets/d/1lFiJi-X3Xm3hh3I9Ty9dfACMiBWxHFAOUeiU1km9m6I/edit#gid=106736391

The second generation is underway.

## main feature
* XY system
    * Frame size 300x300
    * Full movement range (always larger than heated bed size): 168x168. so I prefer 150x150 or 180x180 aluminum heated bed.
    * nema14 55mm or 60mm stepper x4 (voron v0 xy stepper)
    * Designed from sketch and aluminum CNC oriented.
* Z: voron 2.4 Z architecture (not ready)
    * "*belt-driven 4Z lifting the heated bed*" seems weird but works fine and can reach 20000mm^2/s @ 60mm/s, so this architecture is keeped in the project.
* No electronics bay design. 
    * As my testing platform, the electronics changes frequently. 
    * I placed some aluminum extrutions at left and right and bottom to mount PSU and MCU boards and RPIs.
* No fully enclosure design.

## 3D model link
* https://a360.co/3b0XKa3
  * This is for preview. The f3d file will be free to download when the design is completed.

## Misc
* Z system is not ready.
* The whole project is overkilled for daily use, but is just good enough as my testing platform.
* I am not planning to build a BOM, *someone can count bolts and nuts by himself*.
* ABS-printed project is deprecated because the CNC version is WAY better. But you will find it is easy to make our own ABS-printed project.
