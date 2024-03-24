![Screenshot](./amigaps2front.png)
An experimental PCB to enable using existing Arduino Nano based sourcecode to convert PS/2 mouse to Amiga mouse signals. Also has an additional Gameport connector wired to appropriate analogue input pins on Arduino Nano, to enable connecting an analogue old PC joystick, a button (for selecting mouse resolution), and even an I2C connection for PinSockets 2.54mm, to allow for connecting other I2C devices (accelerometers or screens).

Pins were selected to suit this software opensource project : https://github.com/asig/amiga-ps2-mouse-adapter

Licensed under GPL3.
The PCB is provided "AS IS", no warranties of correctness or fitness for purpose are implied nor expressed. You use the schematic on your own responsability, if you break something usig it it is not my fault. Be warned.\par

Caution! Please note!
NEVER connect Arduino Nano to  USB power source and Amiga at the same time! The design only has a diode from power source pin from Amiga joyport, to prevent powering Amiga from the device, but other considerations were not made.

This is a small revision of v1.1 of the design. As v1.0 had wrongl wired gnd, so wire had to be added from DB9 to gnd on the mounting hole of DB9 connector. I also modified and used the PCB for an PS/2 to MSX mouse convertor project, tested working OK, and I shall be adding that version to a separate repository soon.
![Screenshot](./amigaps2back.png)
If you make it and sell it, please consider I declare my opengiveback.org principle requirements at 15% (FAIR) of earnings. Check out more about my opengiveback.org concept at www.opengiveback.org
