# crossbow_r0
It is an XXYY cross gantry 3d printer.

The first generation got 3:21 speedboatrace score, and the 4th on the ranklist.

* speedboatrace video: 
  * https://youtu.be/H7nYXnaKUYE
* speedboatrace leaderboard (ember_cc#3959):
  * https://docs.google.com/spreadsheets/d/1lFiJi-X3Xm3hh3I9Ty9dfACMiBWxHFAOUeiU1km9m6I/edit#gid=106736391

The second generation is underway.

## main change
1. xy: nema17 48mm stepper(voron 2.4 z stepper) -> nema14 55mm or 60mm stepper(voron v0 xy stepper)
2. z: stepper with planetary gear reducer -> voron 2.4 Z retarder
3. range: xy range (always larger than heated bed size) 110x110 -> 168x168
4. hotend from BIQU H2O to SE Mosquito Magnum+ or something with similar shape.
5. light weight Aluminum CNC XY design (yes this is the public version). All models is designed from sketch and CNC oriented.
6. ABS-printed project is deprecated because the CNC version is WAY better. But you will find it is easy to make our own ABS-printed project.
7. "*belt-driven 4Z lifting the heated bed*" seems weird but works fine and can reach 20000mm^2/s @ 60mm/s, so this architecture is keeped in the project.


## 3D model link
* https://a360.co/3b0XKa3
  * This is for preview. The f3d file will be free to download when the design is completed.

<iframe src="https://gmail856542.autodesk360.com/shares/public/SH35dfcQT936092f0e439c9277ba155ccada?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## One more thing
The whole project is overkilled for daily use, but is just good enough as my testing platform.

## Two more thing
I am not planning to build a BOM, *someone can count bolts and nuts by himself*.
