# PowerGen-ADCBreakout
Changes Made from V1 to V2

The biggest issue in V1 was the breaking of isolation through shared grounds, which I wasn’t sure how to fix before, and overlooked. Ishaan suggested an isolated DC-DC converter which would allow me to have a separate 5v power supply and GND for the two isolated sections of the board. I implemented this in the V2 design using part UCC12040DVE. Additionally, I added the Nucleo to the board and changed the screw terminals to banana clips. Then I made some changes to the labeling according to Lakshay’s suggestions, added test points to the analog inputs, and gave the capacitors values. 

Full documentation can be found in the link below:
https://cloud.wikis.utexas.edu/wiki/spaces/LHRSOLAR/pages/205261146/Power+Generation+Current+Voltage+Sensor+PCB
