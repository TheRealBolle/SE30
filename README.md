# Macintosh SE/30 Logicboard recreation

This is a recreation of the Macintosh SE/30 logicboard.
It is not a 1:1 copy of the original logicboard but instead the original schematics were used to completely redesign and route a lookalike board.

![fully populated board](/Logicboard_populated.jpg)

The provided logicboard files are licensed under CC-BY-NC-SA - they are NOT intended for commercial use.



# Reverse engineered PALs

The original PALs have been reverse-engineered and equations were rewritten to match the behaviour of the originals - the provided
JEDEC files are not dumps of the content of the original chips.

The provided JEDEC files are intended to be used with a 16V8-type device (GAL16V8, PALCE16V8, ATF16V8) as a replacement
for the video, clock and RAM-signalling PALs. Certain low power ATF16V8B don't work. ATF16V8C use pinkeepers instead of internal pullups and might be problematic as well.

Board locations and original part number reference:

UI6 341-0665-A
UH7 341S0689-C
UG6 341-0747-A
UG7 341-0746-A
UE6 341-0754-A
UE7 341-0755-A



# Board Files

The provided gerber files have been generated using the JLCPCB EAGLE cam job files.
Pick and place data is intended to be used with JLCPCB as well.
Other manufacturers might have different requirements to the gerbers.



# BOM

A BOM is available at:
https://docs.google.com/spreadsheets/d/1CAzGjHxQaQrduQC-hQ8sB2I6Y56fUlCWdJMCUDho0NE
