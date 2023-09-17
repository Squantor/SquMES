# SquMES electronics
The backplanes and modules of the ModEleSys are stored here.
Backplanes are prefixed with ```bp``` and some extra description.
Mmodules are prefixed with ```mod``` and size in the form of ```W?``` where ? would be the size indicator. For example ```mod_W2_PSU_symmetrical``` is a module of 2 width units that contains a symmetric powersupply. One width unit is 14mm.
## Backplanes
* 30 pin DIN 41612 connector backplane for 10x10x5 cm extruded aluminium boxes
* 30 pin DIN 41612 connector backplane for larger cm extruded aluminium boxes
* 48 pin DIN 41612 connector backplane for larger aluminium boxes
* 48 pin DIN 41612 connector backplane for 2U box
## Modules
* Powersupply fed by one DC jack that provides symmetrical voltage rails and one logic supply using LD1117 LDO's
* LPC812 microcontroller board with USB to serial UART
* STM32G031 microcontroller board with USB to serial UART
* 22bit low speed ADC board
* 16bit high speed ADC board
