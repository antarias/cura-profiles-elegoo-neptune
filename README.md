# Elegoo Neptune 2D profile for Cura

Profile to use Neptune 2D in Cura, updated from the Elegoo-branded Cura version 4.8 that came with the printer.

## To use:

Copy files into `C:\Users\USER\AppData\Roaming\cura\VERSION\`, subfolders `definitions` and `extruders` :

- definitions\elegoo_neptune_2D.def.json
- extruders\elegoo_neptune2D_extruder_0.def.json
- extruders\elegoo_neptune2D_extruder_1.def.json 

Then select `Elegoo Neptune 2D` with author `antarias/custom`

## Changes:

#### May 2026
  - Print purge line with the initial extruder. So, if only using 1 extruders, it is not necesary a purge tower, and the correct extruder will be purged (using the right color)
  - Other minor errors suggested by Claude.

#### May 2026
  - Removed Elegoo Neptune 2 and Saturn, only keeping Elegoo Neptune 2D (same as 2 but with 2 extrusors)
  - Fixed error with extruders numbers, now can correctly use 1 and 2 extruders.
  - Simultaneous heating of bed and extruder (not in sequence, but at same time, to start printing faster)
  - Created with Gemini.

#### Jan 2022
  - Renamed Elegoo-modified custom extruders as Elegoo extruders, correcting Elegoo spelling.
  - Corrected references to Elegoo extruders from Elegoo printers
  - Moved Elegoo-modified code from fdmprinter and fdmextruder to the Elegoo files

#### Initial version 
- Configurations are taken from the Elegoo-branded Cura version 4.8 that comes with the printers. 
Extracted and cleaned the configurations files to be able to use the regular Cura distribution, and its updates.

