# UTD356 Mini (with Type-C aftermarket PCB)


Make example for this keyboard (after setting up your build environment):

    make ieox/utd356mini_usbc:vial
	
Flashing example for this keyboard:

	sudo dfu-util -a 0 -s 0x08000000:leave -D ieox_utd356mini_usbc_vial.bin


## Bootloader 

Enter the bootloader in 3 ways:

* Bootmagic reset: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* Keycode in layout: Press the key mapped to `QK_BOOT` if it is available
* Physical reset button: Hold the button on the back of the PCB
