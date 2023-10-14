# TeensyPoly41

This is loosely based on [TeensyPoly6](https://github.com/albnys/TeensyPoly6)'s schematic, but with many significant changes:

* It uses a Teensy 4.1, as the 3.5 wasn't available when this was designed.
* It takes the form of a single 2-layer PCB with all pots, switches, and buttons directly affixed. I suppose you could run wires to a front panel if you *really* wanted to.
* It leans much more heavily into the multiplexers, with 8 instead of 1. This results in a more efficient use of pins. 
* It adds a few more controls and enables full ADSR envelopes on the amp and filter.
* It adds LEDs to indicate system state (and greatly aid debugging).
* It adds a rotary dial to select the desired MIDI channel.

### What it looks like
![TeensyPoly41 top view](/doc/teensypoly41_revA_top.jpg)
![TeensyPoly41 bottom view](/doc/teensypoly41_revA_bottom.jpg)
