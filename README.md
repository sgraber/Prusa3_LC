Prusa3_LC
=========

Laser cut files for the Prusa i3 printer frame - both Standard Single Sheet and Mini versions: https://github.com/josefprusa/Prusa3/

Published under GPL v3, same as the Prusa 3.

The goal of this revision is to allow people to use frame material that is less rigid than the 6mm aluminum, which is specified for the Single Sheet Frame Prusa i3 Printer (http://reprap.org/wiki/Prusa_i3#Single_Sheet_Frame) and have it laser cut instead of water jet cut. Laser cutters are more accessible for people either at their local makerspace or at local laser cutting businesses. Laser cut material is also less expensive and people can source different frame colors and materials, such as 5mm birch plywood, 6mm double-faced melamine, and 1/4" acrylic.

To achieve this goal, two angular braces are designed and added to the bill of materials and the stock Prusa i3 Single Sheet Frame is slightly modified to accept these braces. A major goal of this revision is to keep the Prusa i3 frame as stock as possible so that people can continue to print and use Josef Prusa's i3 parts from his Github repository: https://github.com/josefprusa/Prusa3/ In this release, the frame dimensions were not changed at all. The only additional items added to the i3 bill of materials are the two laser cut braces and six 25mm/1-inch M3/6-32 SAE screws and washers.

This frame was designed for use with 6mm-thick material. Thicknesses less than or greater than 6mm will require the brace tab lengths to be decreased/increased and the square tab-accepting holes in the Prusa i3 frame to be decreased/increased accordingly. I have found that oversizing the tab-accepting holes by 0.2mm works but each laser cutter is slightly different and may require adjustments different than this.

More photos are found on my photostream at Flickr: http://www.flickr.com/photos/sbgraber/8351936888/in/photostream/

This repository contains two different frame sizes: the Standard Single Sheet Frame and the Mini Single Sheet Frame. The Standard frame is for 200mm (8") square heated beds. The Mini frame is for 100mm (4") square print beds, and is a smaller version of the Prusa i3.


Changed and New Parts
=====================

4/22/2015 - Fork by Thetazzbot
Changes made by Thetazzbot:
* Removed electronics mounting holes.  Double sided tape works better.
* Resized the support wings so the entire arrangement fits a 24 inch by 16 inch panel so it can be
  efficiently cut from a standard 4 foot by 8 foot sheet of material.
  
Changes to the stock Prusa i3 frame:

* Screw hole size increased from 2.5mm to 3.5mm to allow for either 3mm or 6-32 SAE screws
* Added square tab holes for braces
* Increased bottom 8mm circular holes to 16mm oblong holes to allow pre-wired motor connectors to fit through
* Moved RAMPS 1.4 mounting holes to the braces
* Added "i3" text to top of frame
* removed two heat sink for extruder motor as wood / acrylic makes for poor heat sink material
* removed y-alignment tool and associated holes in frame as the new braces take care of this

New braces (2):

* Measure 370mm tall x 178mm wide (14.6" x 7")
* Oblong holes in brace bottom allow for pre-wired motor (and other) connectors to fit through
* Mounting holes for both RAMPS 1.4 and RAMBo one one brace (Sanguinololu and RUMBA holes on the other brace forthtcoming)
* 80mm x 8.8mm slot in bottom ties into the top-back y-axis threaded rod using four washers and nuts and an extended y-axis threaded rod
* Nut traps accept either M3 or 6-32 hardware (Nyloc nuts, 25mm / 1 inch screws)

Changes to the stock Prusa i3 Mini frame:

* Added square tab holes for braces
* Moved RAMPS 1.4 mounting holes to the braces
* Removed y-alignment tool and associated holes in frame as the new braces take care of this
* Beefed up perimeter of y-carriage by 2mm
* Swapped out LM8UU printed bearing holders for LM8UU mounting holes, like the Standard Prusa i3 y-carriage

New Mini braces (2):

* Measure 273mm tall x 100mm wide (10.75" x 4")
* RAMPS 1.4 mounting holes moved from frame to braces
* 54mm x 8.8mm slit in bottom ties into the top-back y-axis threaded rod using four washers and nuts and an extended y-axis threaded rod
* * Nut traps accept either M3 or 6-32 hardware (Nyloc nuts, 25mm / 1 inch screws)


How to obtain laser cut frames
==============================

I have provided three file types for people to use when laser cutting: dxf, eps, and pdf. Your local makerspace or laser cutting business should be able to utilize one of these three file formats to cut your frame and braces for you. "frame-6mm-colored-lines.dxf" and "frame-6mm-mini-colored-lines.dxf" has the lines colored for easier laser cutting: green=raster, yellow=1st cut, orange=2nd cut, brown=3rd cut, red=last cut.

If you would prefer to purchase one of these frames and associated braces online, I will soon provide these parts on Ebay along with my printed parts, which conform to the latest versions found at https://github.com/josefprusa/Prusa3/ branch. This way you can source most of what you need from one place: http://myworld.ebay.com/sbgraber

I worked with the guys at SeeMeCNC during development of this frame revision and they are also providing the frames for purchase from their website: http://shop.seemecnc.com/  These guys are great to work with and I highly recommend them and their products.


Assembly
========

Materials:

* Frame (1)
* Brace (2)
* M3 / 6-32 SAE screw, 25mm / 1-inch long (6)
* M3 / 6-32 SAE washers (6)
* M3 / 6-32 SAE nut / nyloc (6)

Slide the tabbed braces into the frame. Slide a washer onto an M3/6-32 SAE screw and insert the screw into each nut trap hole. Use either a standard or nyloc M3/6-32 SAE nut and screw tight.

Assemble the remainder of the printer per the instructions in Prusa's repository: https://github.com/josefprusa/Prusa3/blob/master/doc/manual.txt
