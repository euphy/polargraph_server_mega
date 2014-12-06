THIS IS DEPRECATED AND NO LONGER SUPPORTED
==========================================

There have been a few significant changes in the _polarshield and the _a1 branches that diverge from this.

- Use polargraph_server_polarshield if you have a MEGA with a Polarshield.
- Use polargraph_server_a1 if you have anything with any other kind of motor driver (eg Adafruit).

 

polargraph_server_mega
======================

Polargraph Server for ATMEGA2560 based arduino boards using AFMotor (Adafruit Motorshield v1).

The program has a core part that consists of the following files that are common to all Polargraph Server versions:

- comms.ino
- configuration.ino
- eeprom.ino
- exec.ino
- penlift.ino
- pixel.ino
- util.ino

and 
- polargraph_server_mega.ino

which is named for the project.

The other source files include the extended functionality available on ATMEGA2560 boards.

The file called impl_mega contains implementations of a few functions, and also
contains the extended impl_executeCommand(...) which is the jumping-off point for those 
extended functions.


Written by Sandy Noble

Released under GNU License version 3.

http://www.polargraph.co.uk

http://code.google.com/p/polargraph/

