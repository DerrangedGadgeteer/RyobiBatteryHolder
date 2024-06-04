# Derranged Engineering Battery Holder: Neon Green & Grey Edition

For further details: See my video on YouTube.

This is a file repo for a personal project I'm sharing in case others might be working on something similar.  These designs are experimental, and offered without warranty.  It's entirely possible to ruin your battery or worse, even if you follow my work exactly.

## Negative Space Subtractable
The file: RyobiBatteryAdapterCutout.FCStd is a FreeCAD document, a fusion of primitives which I designed to accept Ryobi One+ 18v batteries.  It can be brought into another project and subtracted from whatever shape you want to make into a battery holder.

The two circular cutouts to either side of the battery pocket are intended for a pair of 25mm (1") O.D. Fender washers.  These secure with 3mm screws (#6) and engage with the battery latches, since 3D printed tabs would be susceptible to snapping off.  (See the example holder for details)

The two deep rectangular cutouts are where metal contacts can be run.  They were sized to accept 1/4" male automotive-style blade quick disconnects bent over as shown in in the assembly of the example holder.

## Example Holder Project
The file: RyobiBatteryAdapter.FCStd is a FreeCAD document in which I modeled a simple block shape and subtracted the cutout file above.  This is a demonstration of a way the subtractable file can be used.

The file: RyobiBatteryAdapter.STL is an exported version of the same model, ready to be sliced and printed.  It can be used to test fitment, or even, as shown in the video, To make a simple breakout adapter for connecting a battery to another electronic project.  

I printed the test parts:
 - on a Creality CR-10
 - using plain PLA filament
 - 215 degree hotend
 - 50 degree bed
 - sliced in Ultimaker Cura
 - using the Draft Quality (0.32mm layer) setting
 - With 4 walls
 - 4 top and bottom layers
 - 10% gyroid Infill

I've done no long-term durability testing.
