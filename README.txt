This version of Marlin has the Elefu changed backed into a newer release of Marlin than
the original release that came with the Elefu board. It fixed several problems,
esp the fan PWM adjustment turning the board on and off when doing a front panel adjust.
It still needed extruder calibration, but most other things worked.
. bug: 5V fan PWM does not seem to work, change the pin to extruder 2 (0..2) Hotend PWM channel
   and only use 2 extruders with this version. Or steal an I/O from the un-used header bank
    (assuming it can be used as a fan PWM control, maybe not with hardware, but with software and INTs ?)
    
Moved all the /Marlin files to a git repository  ElefuRA_MM2 on 6/16/2014
Shortcut links to the local git working directory and staging area (file)