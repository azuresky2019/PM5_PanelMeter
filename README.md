# PM5_PanelMeter

This is the source code for our PM5 panel meter which is a gneral purpose PID controller. The product page and documentation is here: 
https://temcocontrols.com/shop/pm-5e-temperature-controller/

The code is done in C and compiled with the Keil compiler. The project roadmap (in the next month or two) is to migrate the hardware to the same 32bit Arm CPU which the Tstat8 is using and merge this repo with the Tstat8 repo. Currently the device only supports modbus communications, once the migration to the Arm cpu is done it will also support bacnet protocol.
