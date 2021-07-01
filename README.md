# ARDUINO-MKR-WAN-1300-5G-detector-shield

This is a 5G detector shield compatible with Arduino MKR WAN 1300.

The PCB software used is KiCAD. The project is archived, you can unarchive it with KiCAD.

There is two project inside, one simply named 5G, has a UMCC connector for the antenna.

The second one is called 5G_SMA, and has a SMA connector for the antenna.


The device contains:

- an antenna connector
- a 5G n78 band filter
- a RF detector (LTC5531)
- a first RC filter (to remove the highest frequencies)
- a second active RC filter (to filter and add an enventual gain)
- a fird RC filter (to filter again, especialy the 48 MHz of the Arduino CPU that will come from the power supply, because the 3V3 of the board is used)


This device is a part of a project on a 5G weather IoT device. A paper is availiable at: (link will be added soon)

The code to use this shield is there: https://github.com/Louis-GUENEGO/5G-shield-program

The 5G antenna is here : https://github.com/Louis-GUENEGO/5G-n78-custom-antenna
