RostockMarlin
=============

Marlin Firmware with Rostock Autocalibration

IMPORTANT:  In this codebase, the pins.h for RAMBO has the pins for E0 and E1 all swapped
because my own E0 on my own RAMBO board is toast.  Be sure to change that before you
attempt extrusion!

ALSO IMPORTANT: While the autocalibration is working quite well for me right now, it's in a 
bad state in this current version.  You must calibrate after you home, every time.  If you do not
power on -> home -> calibrate (with optional later home -> calibrate) your printer will attempt to
kill itself.



