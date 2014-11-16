10 Amp Buck
===========

Based on TI SimpleSwitcher.

Designed as a quick way to get plenty of power for our servos or avionics. More reliable under load than the 3A BECs you can buy off of the shelf
TI offer free sampling of these parts for academic or student projects. 

Now also features an optional 3v3 LDO. 

Need to look at the heat dissipation, it's a switcher, but the board area may need to be increased to dissipate heat if we're using these at near full capacity. 
With 2 square inches of copper for heat dissipation we hit 21degs/W rise. 
This gives us about 3W of dissipation to play with before things get too hot, or 6A switching down. This isn't much of an improvement over the current power supply board on the quad from last year, but it is in a far smaller package (1.85x1.5 inches). If we increased the board area, we'd be fine. The package is also compatible with D3-pak smd heat sinks. 


