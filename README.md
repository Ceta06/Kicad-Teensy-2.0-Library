Teensy++2.0 
Teensy++ 2.0 library for kicad

Library

This just contains library file with external pinout (not represented smd pins on bottom side).

Module footprint

Footprint of external pinout (not represented smd pins on bottom side).

How to: Add library

Go to Preferences/Set Active libraries then use add button and look for your libraries. It can be wherever you want.

If you move the library to another path, you must relocated it to keep using it.

How to: Add Module

In lasts versions you must store the module footprint on a .pretty folder.

Move module to your project folder and create a modules.pretty folder.
Go to preferences/Edit Library Table and and select Append with wizard
Select Kicad(*.Pretty folder) containing .kicad_mod files)
Click on Next and select Use enviroment variable in path and select your project folder path.
Clic on Next and click on Add FP Libraries. In the new window that just openned look for your *.pretty folder, click ok and Finish and you're done!
License

This work is under CC-BY-SA 3.0 license

cc-by-sa License
