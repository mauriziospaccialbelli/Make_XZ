**ENGLISH** / [ITALIANO](README(IT).md)

The Make XZ is a Cartesian 3D printer with a double X carriage that uses openbuilds profiles and the duet wifi board... in addition to being precise and silent, has several interesting features.

The Make XZ can have different configurations thanks to the different modules and the native support for the double X carriage.

For example: Up to 7 colors with one X carriage. Up to 6 colors to divide for two x carriages. Double X carriage independent or in copy. Use filaments with different diameters during printing.

>The Make XZ is in full development, we want to test the multi-material as soon as possible.

We are developing documentation, installation manual and files for calibration... all will be shared as soon as possible.

Can Replicate all its components excluding only: bolts, nuts, screws, electronics, bearings and aluminum profiles (Laser cutting is not required).

You can follow the project on [3Dingegno.com](http://www.3dingegno.com/stampa-3d/3d-printer-make-xz/).

####Main features of the Make XZ:

- Easy to close (everything is inside the structure, you only need to screw the panels on the structure!!)
	
- Electronics: [Duet Wifi](https://www.duet3d.com/DuetWifi) with possibility to use Duex2 and Duex5 expansion boards, and the touch screen "PanelDue" 4.3 / 5/7 inch.

- Predisposed for double X carriage (X1 and X2).

- Printable area with only X1: 300x210x200 (A4)
- Printable area with X1 and X2: 250(or more)x210x200

- The bearings on motors axes (X1/X2, Y, Z).

- Z sistem with one Z motor, closed belt and two trapezoidal screw Tr8 * 8-2p (4 starts). Less calibrations, more synchronization.

- Beld tensioner on each axis.

- Module X1 and X2: The first X module that mount the Make XZ, uses e3dv6 hotend with inductive probe for the hot bed (soon, we change the type of probe). The probes cross and reach only 40mm of offset between the modules "e3dv6_X1" and "e3dv6_X2". The e3dv6 module has two secondary modules: multimaterial module and fan nozzle module.

- Module multimaterial: Multimaterial module (work in progress) allows you to have different combo for the multimaterial with both X module, with double carriage things become even more interesting. However now we want to test a different approach... too many bowden tubes do not like us.

- Fan nozzle module: The nozzle fan module allows to quickly disassemble the air conveyor, or to mount another type.

- Predisposition to clean nozzle on X1 / X2 (work in progress). This allows material changes only where necessary, no color limit, no use of intelligent towers, less filament consuming, less print times, more print area

- The heated plate is removable in borosilicate glass with PEI sheet.

- We have chosen v-slot profiles by openbuilds, but instead of using Eccentric Spacer for v-wheels, we used other systems.

- We are testing a extruder for 1.75mm/2.85mm interchangeable bowden with steps filament pressure, that use Geared Stepper Motor(??).In addition to ensuring a excellent extrusion, you can easily share the settings of materials

Thanks to the features and components of Make XZ, you can print most types of filaments, including technical/special. Any material that is being tested then added to the list of calibrated materials, we are creating a macro containing all the calibrated materials settings to quickly set up the materials.

All projects born in 3dingegno.com are developed and maintained only with free software and opensource. Where we can use open hardware, for example openbuilds, duet wifi, ZPRep.

Thanks to all free software and opensource projects around the globe.
Special thanks to the community of [RepRap](http://forums.reprap.org/index.php), [Duet3d](https://www.duet3d.com/forum/), [FreeCAD](https://forum.freecadweb.org/), [OpenBuilds](http://openbuilds.org/).

The Make XZ is a RepRap project born in 3dingegno.com from Maurino Web and Marco Spaccialbellli.

Sorry for bad english :-)



