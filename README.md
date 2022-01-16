# Elegoo Neptune, Neptune 2 and Saturn profiles for Cura

The configurations are taken from the Elegoo-branded Cura version 4.8 that comes with the printers.
I extracted and clean the configurations files to be able to use the regular Cura distribution, and its updates.

=======================================

To use them, just open your Cura installation folder, and go to the resources folder,
for example, C:\Program Files\Ultimaker Cura 4.12.1\resources

Copy following files in place and restart Cura. Go to add printer, and search for Elegoo models.

Files to copy :

Folder  .\resources\definitions\
  elegoo_neptune.def.json
  elegoo_neptune_2.def.json
  elegoo_saturn.def.json

Folder .\resources\extruders\
  elegoo_neptune_extruder_0.def.json
  elegoo_neptune_extruder_1.def.json
  elegoo_neptune2_extruder_0.def.json
  elegoo_neptune2_extruder_1.def.json
  elegoo_saturn_extruder_0.def.json
  elegoo_saturn_extruder_1.def.json
  
=======================================
List of changes:
v1  Jan 2022
  - Renamed Elegoo-modified custom extruders as Elegoo extruders, correcting Elegoo spelling.
  - Corrected references to Elegoo extruders from Elegoo printers
  - Moved Elegoo-modified code from fdmprinter and fdmextruder to the Elegoo files

  
