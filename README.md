
PCB Crown
=========
A fun experiment in 3D circuits and wearables, designed as a gift to Laen. It was unveiled at the 2014 Maker Faire Bring-a-hack party. 

![ ][images/2014-05-18 19.59.02.jpg]


About The Crown
---------------
The structure of the crown is 11 different panels, held together via PCB Castellations and solder. The 11 panels are made from
5 different designs, and used 3 copies of the tall face plate, and 2 copies of each other design.

The electrical side of the crown is primarily configured to drive 2 individually addressable LED strings. There's a total of 44 RGB LEDs, configured as 2 strings of 22 each
The top uses [8mm Diffused LEDs](https://www.adafruit.com/products/1734), and the faces use [WS2812B SMD LEDs](https://www.adafruit.com/products/1655). These are 
powered by a [SMDuino module](https://code.google.com/p/smduino/), with optional buttons for whatever nefarious purpose seems desirable.

Each module also has a tiny circuit that acts as a SMD equivilent to a breadboard, suitable for future additions of accellerometers, gyros, or light sensors. 
Here's the crown glowing with the full might of the NeoPixels running Adafruit's test patterns. 
![  ][images/2014-05-18 19.59.02.jpg]


WARNING!
--------
This is being published as an demonstration and example project, not as a completed work suitable for replication. 
As an experimental design, this is _highly_ unlikely to work properly for you. The chosen board interconnects are incredibly fragile, and will often stop functioning
if bumped, jostled, or left alone quietly in a dark room. Several part footprints, due to artistic constraints, are maddening to assemble and virtually impossible to test effectively. 
No individual panel will work at all without the adjacent panel, requires at least 1 cut trace, and the LEDs will not work properly without at 
least half the design completed and working. 

Full documentation, build notes, and additional details are posted at [tekdemo.github.io/](http://tekdemo.github.io). This includes things not to do, as discovered
in the course of designing and building the crown.

License
--------
Files under `/images/` and the contents of the `gh-pages` branch are liscenced under [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

All other files are released under the [MIT License](http://opensource.org/licenses/MIT). 

