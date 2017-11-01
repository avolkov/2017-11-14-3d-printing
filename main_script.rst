=========
On building a 3D printer from scratch
=========
Or How I spent this spring, summer, autumn and the stupid thing is still going
---------

So the story started some time ago where I was looking to get into 3D printing, and I've been mercilessly exploiting/taking care of hacklab 3d printers, where I printer a phone car holder and a tabled holder (do you see a pattern here?)

I've been following Thomas Salandeerer channel toms3d on youtube, and at some point in february there was a featured series on how to build a 3D printer from scratch.

TOM'S Guide
===========

Here are the videos:
Tom's guilde -- [CIT001]_ on building the cheapest possible prusa i3


These video series didn't come out of nowhere, it is based on one of more simpler and popular commercial 3d printers that are completely open-source -- Prusa i3 mk2

Prusa i3 mk2 is a part of reprap project build by Joe Prusa, based on Prusa Mendel which itself is based on Prusa Mendel,

Prusa i3 wiki -- [CIT002]_

.. [CIT001] Tom's 3d building cheapes prusa clone https://www.youtube.com/watch?v=oVWLpvekby0&index=1&list=PLDJMid0lOOYkdh8jCqIw7AFIHQiuKbSKZ
.. [CIT002] Prusa i3  wiki page https://en.wikipedia.org/wiki/Prusa_i3


Prusa i3 MK 2

.. image:: images/001-prusa-i3-mk2.jpg
    :width: 200px


Prusa Mendel i2

.. image:: images/002-prusa-mendel-i2.jpg
    :width: 200


Prusa Mendel

.. image:: images/003-prusa-mendel.jpg
    :width: 200


Prusa as a company has been around for a while and is committed to open-source design. They published printed part schematics on Github under GPL v2 in OpenSCAD, frame schematics SVG, software -- a Marlin fork and smoothie board for electronics. Stepper drives situation is similar to the situation in computing in general, the chip hardware is closed source; the biggest players on the market

Prusa also publishes full assembly manual from nuts, bolts, printer parts and 3d-printer specific parts [CIT003]_

.. [CIT003] Original Prusa i3 MK2S kit assembly http://manual.prusa3d.com/c/Original_Prusa_i3_MK2S_kit_assembly


Allegro A4988 [CIT004]_
TI DRV8824 [CIT005]_
Trinamic TMC2100 [CIT006]_


.. [CIT004] -- http://www.allegromicro.com/en/Products/Motor-Driver-And-Interface-ICs/Bipolar-Stepper-Motor-Drivers/A4988.aspx
.. [CIT005] -- http://www.ti.com/product/DRV8825
.. [CIT006] -- https://www.trinamic.com/fileadmin/assets/Products/ICs_Documents/TMC2100_datasheet.pdf


Honorable mention -- Aleph objects, the makers of Lulzbot, even more hardcore than Prusa and release development files during every 15minutes during development.


######################
Starting out the build
######################


Ordering stuff:

* 3D printer parts from China
    * Talk about e3d v6 clones
* Metric hardware
    * Possible imperial hardware replacement
    * Things that absolutely need to be metric of spec M5 Rod
    * Talk about Z-woble
    * hardware suppliers
* 3D printed parts, printing ABS
* Frame/particle board

* Assembly

* Custom parts

* Compiling Marlin
    * Mesh bed leveling and tuning

* Tuning
    * Extruder calibration
    * probe leveling with a piece of paper
    * G28


* Issues
    * motors not working
    * nozzle hits the bed
    * layer adhesion issues
        * kapton tape
        * bed levelling
        * pre-bent rods (and how to buy the right ones)
    *

########
Software
########

* Arduino
* Marlin
* pronterface and printrun package
* Slicer and Slic3r (or cura)
* Octoprint (with raspberry pi)

####################
Learning to 3d print
####################

Common 3d printing issues.
* Z wobble
* bed leveling issues
    * prints fail
    * overextrusion
    * bent rods
* temperature
* cooling
    * part cooling fan for

* Tools
    * Alcohol spray bottle
    * Kapton tape (old school)
    * spatula
    * pincers
    * Metric hex screwdriver
    * snips
    * smaller pincers
    * automotive pincers for heater block
    * acetone
* Printing with materials properties -- advantages/downsides
* PLA
* ABS
* ABS+ (stronger but not any easier to print)
* PETG (Only slightly more expensive than pla)

Exotics: Nylon, ASA, Solubles



Issues
* temperature
* cooling
* overhangs
* slicer settings

Debugging
* 3D benchy

--------------
Heated chamber
--------------

* Purpose
    * Improvements:
    * layer adhesion
    * layer shifting
    * ABS / ASA layer improvement
* Version 1 -- really cheap, Lacking + polyurethane tape
* Version 2 --
==============
Gcode commands
==============

G1
G0
G28
G29 -> needs to be adjusted because frame is thinker than aluminum one


========
projects
========
* project parts
* stuff on thingiverse
* thingiverse (with caveats)
* youmagine
* parametric parts (good stuff) for openscad -- basically a source code that every admin/programmer can understand.
* onshape
* fusion 360 (with caveats)

===========
Final notes
===========

Still easier than learning javascript ecosystem

