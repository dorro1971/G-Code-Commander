# G-Code-Commander
web page based utility to modify pre-sliced files and convert from absolute to relative extrusion (for Bambu printers)

I wanted to print a pre-sliced file, however, the file was sliced with absolute extrusion and my Bambu H2d requires relative extrusion!, so with a little help from chatgpt G-Code commander emerged and allowed me to convert the file from absolute to relative!


Allows modification of:-
Printing acceleration and speed 
Travel moves and acceleration (G0 and G1)
Nozzle tepmerature
Bed Temperature
Extrusion multiplier
Addition of purge line

Usage:-
Open G-code Commander with your web browser
Adjust any settings, if any setting is left untouched, the original sliced settings will remain
Click on convert to start the conversion process
Click on download relative G-Code and save to you desired location
Save and Load recipes as required to save time later!

Load the converted file to a usb stick and insert into printer
Manually load filament 
Print as usual from Bambu control panel

V1.2 added retract and un-retract / prime settings too!

## Disclaimer

**G-Code Commander** is provided free of charge as an experimental utility.

While every effort has been made to ensure it works correctly, use of this software is entirely at your own risk. Always review any modified G-code and monitor the first print after making changes.

The author accepts no responsibility for failed prints, printer damage, material loss, or any other consequences resulting from the use of this software.

By using G-Code Commander, you acknowledge that you are responsible for verifying that the generated G-code is suitable for your printer and application.



