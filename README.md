This is the router table lifter project.

## ingredients

### List of software needed :
- Inkscape
- http://lokspace.eu/anet-a8-3d-printer-laser-engraver-mod/ (plugin for engraving the outline)
- https://github.com/305engineering/Inkscape (idem but with full pass engraving, can be used to print like ink printer (not just the outline)


### List of the Hardware needed

#### Electronics
- 1 arduino uno (or clone)
- 1 2.4inch  tft color screen for arduino (like https://www.ebay.fr/sch/sis.html?_nkw=2.4%22+TFT+LCD+Shield+Socket+Touch+Panel+Module+for+Arduino+UNO+R3+New+UR&_id=371439864552&&_trksid=p2057872.m2749.l2658)
- leds of your choice
- (optional) led support (like https://www.ebay.fr/itm/50-pcs-5MM-Chrome-Metal-Silver-Bezel-LED-Holder-Panel-Display-Mount-Base-Rubber-/253065839214?hash=item3aebe6426e)
- 5 Buttons (like https://www.ebay.fr/sch/sis.html?_id=302039146961&_nkw=5%2F+10Pcs+16mm+Waterproof+Momentary+Action+Metal+Push+Button+Switch+for+Auto+Car&rt=nc&LH_BIN=1 , Mounting Cut Hole: 16mm, Head Diameter: 18mm)
- 

#### Motor
- 1 stepper motor NEMA 23 (need to calculate the torque needed to choose the motor)
- 1 motor driver (homemade or not?)

## Interface

![button_image](https://github.com/yooonie/router_table/blob/master/button_function.png)

|id |	Button |	function|	menu function	|
|----|---------|----------|--------------|
|1	|Up|	move lift up|	move up	|
|2	|Lock|	Lock up or down (push again up or down to stop)|select / set|
|3	|Down|	move lift down	|move down|
|4|	Speed	|set the number of rotation or speed (one brief push), tare the up and down (push and maintain 2sec or more)|
|5	|Set	| -  to choose between manual or mm setting (one brief push), to enter menu on screen (push and maintain 2sec or more)|exit	|
