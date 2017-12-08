# NodeMCU I²C and 1-Wire Breakout Board

Have you  ever tried connecting more than one I²C device to a NodeMCU board? While I²C and 1-wire are designed to allow dozens of devices connected to the same bus, most boards - including the NodeMCU - provide only one pin for the I²C lines (SCL and SDA). To connect multiple I²C devices, one usually needs to resolve to clumsy breadboards.

This board is a simple, small breakout board for the NodeMCU, which is attached to only one side of the NodeMCU. It provides multiple I²C and 1-wire connections. The pin order of the I²C connectors is the one used by most I²C sensors:
* VCC
* GND
* SCL
* SDA

Please note that the SparkFun sensors use a different order!

The pin order of the 1-Wire connectors is:
* GND
* DATA
* VCC

One can solder either male or female pin headers to the breakout board and connect the sensors using Dupont wires, or use female pin headers with the sensors directly plugged into the breakout board.


![NodeMCU I²C breakout board](https://github.com/open-tools/NodeMCU-i2c-Breakout-Board/blob/master/images/IMG_0616.JPG "The breakout board with some I²C sensors connected")
![NodeMCU I²C breakout board](https://github.com/open-tools/NodeMCU-i2c-Breakout-Board/blob/master/images/IMG_0613.JPG "The breakout board with some I²C sensors connected")
![NodeMCU I²C breakout board](https://github.com/open-tools/NodeMCU-i2c-Breakout-Board/blob/master/images/IMG_0614.JPG "The breakout board with some I²C sensors connected")
