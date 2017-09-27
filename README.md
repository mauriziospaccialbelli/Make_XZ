**ENGLISH** / [ITALIANO](README(IT).md)

Make XZ is the first project 3D printer born in [3Dingegno.com](http://www.3dingegno.com/stampa-3d/3d-printer-make-xz/) by MaurinoWeb and Marco Spaccialbelli. Is a precise and silent 3d printer with different configurations thanks to the different modules and native support for the dual X carriage and multimaterial.

For example: Up to 7 colors with one X carriage. Up to 6 colors to divide for two x carriages. Double X carriage independent or in copy. Use filaments with different diameters during printing.

The v-slot structure is rigid and silent, even the electronics are silent!

>The Make XZ is in full Development and there is a lot to do...

![3d printer make xz](http://www.3dingegno.com/wp-content/uploads/2017/09/3d-printer-make-xz.jpg)

We are developing documentation, installation manual and files for calibration... all will be shared soon.

The printable models file are already available, but in the final version they may change some parts. For now I recommend printing models only if you are really interested in experimentation or development.

All parts of this 3D printer are Open Source and are part of the RepRap project. Can Replicate all its components excluding only: bolts, nuts, screws, electronics, bearings and aluminum profiles (Laser cutting is not required).

You can follow the project on [3Dingegno.com](http://www.3dingegno.com/stampa-3d/3d-printer-make-xz/).

Main features of the Make XZ:

Ready for easy closure (work in progress)
	
Electronics: [Duet Wifi](https://www.duet3d.com/DuetWifi) with possibility to use Duex2 and Duex5 expansion boards, and the touch screen "PanelDue" 4.3 / 5/7 inch.

Predisposed for double X carriage (X1 and X2).

Printable area with only X1: 300x210x200 (A4)
Printable area with X1 and X2: 250x210x200

The bearings on motors axes (X1/X2, Y, Z).

Z sistem with one Z motor, closed belt and two trapezoidal screw Tr8 * 8-2p (4 starts). Less calibrations, more synchronization.

Beld tensioner on each axis and gcode file to adjust the same tension on X1, X2, Y. (gcode file work in progress)

Module X1 and X2:
The first X module that mount the Make XZ, uses e3dv6 hotend with inductive probe for the hot bed (soon, we change the type of probe). The probes cross and reach only 40mm of offset between the modules "e3dv6_X1" and "e3dv6_X2". The e3dv6 module has two secondary modules: multimaterial module and fan nozzle module.

Module multimaterial:
Multimaterial module (work in progress) allows you to have different combo for the multimaterial with both X module, with double carriage things become even more interesting
Minimum two colors/materials(1.75 or 2.85)

Fan nozzle module:
The nozzle fan module allows to quickly disassemble the air conveyor, or to mount another type.

Predisposition to clean nozzle on X1 / X2 (work in progress). This allows material changes only where necessary, no color limit, no use of intelligent towers, less filament consuming, less print times, more print area

The heated plate is removable in aluminum with PEI sheet.

The frame is rigid because we have chosen v-slot profiles by openbuilds, but instead of using Eccentric Spacer for v-wheels, we used other systems.

We are testing a extruder for 1.75mm / 2.85mm interchangeable bowden with steps filament pressure, that use Geared Stepper Motor In addition to ensuring a excellent extrusion, you can easily share the settings of materials

Thanks to the features and components of Make XZ, you can print most types of filaments, including technical/special. Any material that is being tested then added to the list of calibrated materials, we are creating a macro containing all the calibrated materials settings to quickly set up the materials.

All projects born in 3dingegno.com are developed and maintained only with free software and opensource. Where we can use open hardware, for example openbuilds and duet wifi.

Thanks to all free software and opensource projects around the globe.
Special thanks to the community of [RepRap](http://forums.reprap.org/index.php), [Duet3d](https://www.duet3d.com/forum/), [FreeCAD](https://forum.freecadweb.org/).

Sorry for bad english, we're working on it :-)

In all images missing most of screws and other details, soon the first photos and videos of make XZ.


