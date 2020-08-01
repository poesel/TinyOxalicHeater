# TinyOxalicHeater
ATTiny controlling a heating element to evaporate oxalic acid


WORK IN PROGRESS! (01.08.20)


Purpose:
Beekeepers need to fight the varroa mite. One method is to evaporate oxalic acid in the hive. 
There are some devices that are pushed through the entrance under the hive and evaporate there.
This device is supposed to be put inside an empty super on top of the hive (with closed lid of course). This has the advantage that the fumes have to pass through the hive and out of the entrance and thus passing through the complete hive. 
If this is better is debatable as everything with bee keeping. :) Since I'm making this you can guess my opinion.

Why this method:
The old method used a tea light. While being simple it is also a bit messy and it requires the super to be totally bee free. Any bee inside the super will sacrifice herself to kill the flame.
So I wanted an electrical solution.
You will need a screen mat on top of the hive to let the fumes pass (and not the bees preferably). Those are available for cheap in DIY markets. The are used for pouring concrete.

Parts:
ATTiny85 - for controlling
Heating element - from aliexpress (link TBD)
DS18B20 - temperature sensor
P-channel MOSFET - TBD
7805 voltage regulator - to power the ATTiny
Battery - to power everthing
Buzzer - optional
Switch - optional

Schematic:
I've used KiCAD 1.5.6 for the schematic (there will be a pdf when it is finished). It is quite simple. 
There is also a PCB layout but it is not meant for an actual PCB. I've used it as a help to position the parts on a perfboard.

Code:
I'm using VSC & PlatformIO here. But the code should run in the Arduino IDE, too.
You will need a programmer for the ATTiny85. That is not covered here.