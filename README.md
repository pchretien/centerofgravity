I just finished building a CNC kit from Shapeoko and started cutting stuff. I needed a simple project that would be a bit more challenging than engraving my name on a piece of scrap wood. I decided to give a try to the Wobbly Circle presented by Matt Parker on the Numberphile Youtube channel.

In this video, Matt Parker explains the mathematics required to assemble two disks perpendicular one to the other in such a way that their combined center of gravity always remains at the same height, making the assembly behave like a ball when rolling on a plane surface.

I wanted to use Free and Open Source software as much as possible for this project. I designed the profile in DraftSight, a free CAD program from Dassault Système. I then exported the drawing in DXF and converted it to SVG using Inkscape. This conversion is not optimal because of the way Inkscape handles line thicknesses. Finally I opened the SVG in Makercam.com, an online CAM software to generated the G-Code for the milling machine.

Inkscape is great to produce art pieces and engraving but not really usable as a CAD program. I am still searching for the best free and Open Source solution out there, if you have any suggestion please let me know in the comment section.

The truncated version of the gcode file has been produced using the metric-gcod-truncator by Jeremy Hessig https://github.com/jhessig/metric-gcode-truncator
