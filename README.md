# encore
A mini CoreXY 3D printer with a 3D printed frame.

![printer header imaeg](images/1.png)

Overview video: https://www.youtube.com/watch?v=9xukniyO6fI

This is my latest CoreXY design. It's a small printer with a 120x120x120mm build volume. The total size is slightly smaller than a Voron 0, with a footprint approximately the size of a box of filament.

Unlike my older printer designs, this one uniquely uses an entirely 3D printed chassis, with no aluminum extrusions or custom CNC'd parts. This significantly reduces the total part cost, while the solid panel construction keeps things sufficiently rigid.

All of the printed parts are designed to fit on a 225mm bed, so common printers like the Ender 3, Bambu A1/P1, etc. should have no problem printing them.

For this design I focused on keeping things compact yet modular. Each major assembly (e.g. the CoreXY mechanism, the Z axis, and the outer panels, can be independently swapped out without major disassembly of the other assemblies.

| Specs |  |
| --- | --- |
| Build volume | ~120x120x120mm |
| Body dimensions (excl. Bowden parts)| 219x221x262mm|
| Extrusion| Bambu-style hotend, Bowden extruder|
| Motion| MGN9C X/Y gantry, 8mm linear rod Z + 8mm leadscrew|
| Cooling| 4015 blower (print head) + dual 7515 blower (aux)|

# BOM and assembly
View the list of printed and non-printed parts [here](documentation/BOM.md).

Assembly guide is available [here](documentation/build%20guide/build%20guide.md). Note: still WIP