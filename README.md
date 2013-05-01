eagle2kicad
===========

Eagle to KiCAD schematic conversion script.

Installation
============
* [Download the script](https://raw.github.com/SupplyFrame/eagle2kicad/master/eagle2kicad.ulp)
* Copy to Eagle 'Program Files' directory (C:\Program Files\EAGLE-5.8.0\ulp)

Usage
=====
In Eagle, open the schematic you want to export, select "Run..." from the "File" menu, select the file named "eagle2kicad.ulp" and then click "Open".

A window will open that allows you to choose where to save the new files so pick a location and then press the "OK" button. It's recommended you save them to somewhere other than where your existing Eagle files are saved.

CAUTION: The script will overwrite any existing files in that directory that have the same names.

You should now have three files in the directory you selected. A .pro project file, a .sch schematic file, and a -cache.lib library file that contains all the symbols used in the circuit.
