# Prusa-MK3-Material-Profiles
A collection of Slic3r profiles for a variety of materials for the Prusa i3 MK3

The Excel sheet contained within this repository serves as a record of which profiles were used for which specific material. 

These are not what I would consider 'production grade' material profiles, some of these profiles are more mature than others, see the excel sheet for notes. 

I use the Benchy model to do all my filament testing, so these profiles are built around successfully printing a Benchy.

Some 'Printer Settings' profiles contain some gcode in the 'Custom G-code' section and the 'Start G-code' box that are specific to my printer, namely the line that starts 'M92 X99.65 Y99.90 Z396.03 E280.00 ; sets corrected steps per mm' This can be altered for your specific printer, there are generic values that are used, so you can just remove the whole line if you don't want to specify your steps per mm. 
