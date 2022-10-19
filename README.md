# raspberry-zero-han-interface

## Intruduction
This is a simple PCB to allow a raspberry pi zero to connect to smart meters to gather statistics of power comsumption and similar. 
It uses the HAN-interface that many new meters have and converts it to UART signals to the raspberry pi zero.

It adds as a shield for the raspbery pi zero and provides power to the pi from the 5V-line in the HAN-interface. 
The HAN-interface is specified for 250mA max, so even though is could be plugged in to a normal a normal raspberry pi, it is not a good idea...

This board uses a RJ12-connector. Swedish smart meters use this connector and many other countries at least in the EU, but there are variations.

THE BOARD IS NOT TESTED, USE AT YOUR OWN RISK!
