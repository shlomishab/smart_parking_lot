# smart_parking_lot
Arduino C project that simulates the entrance and exit systems, to and from a smart parking-lot.

*******************************
	Smart Parking-Lot Project,
	Embedded Systems Course
	
	Created by: Shlomi Shabtai
	Date: August, 2020
********************************
This project simulates the entrance and exit systems, to and from a smart parking-lot.


An LCD show the number of available parking spots.

If the ultra-sonic sensor measures a car within 1.5 meter, the driver needs to press the entry key.
Once pressed correctly, the entry gate opens for 4sec, and closes.

The exit system implemented with an Interrupt. 
Once the PIR senses a movement - the exit gate opens for 4sec, and closes.

For each gate that opens, the number of available spots is updated accordingly. 
The Neo-Pixel is a taken/free spots visualiztion, 
and change its lights according to the available Spots.

In addition to that, the RGB-Led changes form red to green, to notify that the gate is open.
When either gate is closed, the RGB-Led lights is red.
**************************************************************************************************
